The CNN_LSTM_Hybrid_Model.ipynb was our first attempt at creating a model that could hit the baselines presented by the competition organizers. Unfortunately, this model fell short on the majority of labels but the file will demonstrate quite a few of the changes made in order to improve our predictions. Further discussion in official write up.

In order to run the CNN_LSTM_Hybrid_Model.ipynb, please follow the instructions below to set up and activate the environment with all the necessary packages.

In the command terminal, navigate to the folder containing the environment.yml file included with our project files and enter the 2 commands below:

1. conda env create -f environment.yml
2. conda activate CNNLSTM
OR
select CNNLSTM from the kernel dropdown menu in the top right of VS Code

The first time you run this model, the code will download some word embeddings from this url (http://nlp.stanford.edu/data/glove.6B.zip). Once you've successfully downloaded it, be sure to comment out this code before future runs to save time and unnecessary downloads.
