# Machine-Translation-using-RNNs-
We have built a profound neural network that capacities as a major aspect of a machine translation pipeline. The pipeline acknowledges English content/picture as info and returns the French interpreted content. We have also used Image to text conversion and then English text to French text translation.

## Approach
To translate a corpus of English text to French, we have built a custom Architecture as we have tried different combinations of layers and implemented the one which gave the best result. We have also used Image to text conversion and then English text to French text translation.

Dataset 
The Europarl is a standard dataset used for statistical machine translation, and more recently, neural machine translation.It comprises the proceedings of the European Parliament, hence the name of the dataset as the contraction Europarl. The proceedings are the transcriptions of speakers at the European Parliament, which are translated into 11 different languages.
![GitHub Logo](/images/dataset_wmt.png)

## Pipeline 
Below is a summary of the various preprocessing and modeling steps. The high-level steps include:
1. Preprocessing: converting text to sequence of integers.
1. Modeling: Creating a model which accepts a sequence of integers as input and returns a probability distribution over possible translations. 
1. Prediction: Running the model on English text. Model will convert the text into french so it compares it with the original french text.
1. Iteration: iterating on the models, experimenting with different architectures to find out the best model for our problem.
