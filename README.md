# Text-Summarization

The News Summary dataset which is collection of articles from Hindu, Indian times and Guardian that has been used to work on the project can be found at this below link: 
https://www.kaggle.com/sunnysai12345/news-summary

Steps to run the code:

1. Open ‘3_Project_2_TT.ipynb' file in python notebook platform like jupyter notebook or Google colab platform.
2. You will need GloVe word embeddings file which can be downloaded from https://www.kaggle.com/terenceliu4444/glove6b100dtxt .
3. A trained model with the weights can be found in ‘3_Project_2_TT.json' and '3_Project_2_TT.h5' files.
4. You can load the trained model with the help of json file, but you will also need to load the weights for the trained model through h5 format file. You can find the code for loading the trained model and running it in last cell of the notebook. It will give you the validation accuracy on testing dataset.
5. To get the processed testing dataset, you need to run till the cell where we have performed padding of the sequences just before importing GloVe word embeddings.
