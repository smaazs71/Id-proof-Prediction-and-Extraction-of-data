# Id-proof-Prediction-and-Extraction-of-data
A machine learning program executed in python that predicts the type of Identity proof and extracts the data from it.

The program is originally executed on google colaboratory.
Google colab provides processing with graphic card which is suited for training the model for free.

Working of program : It takes an image as its input and process it to predict for the type of Id proof. Then another function is used to extract the information from the Id proof.

Prediction: A model is trained using a number of distinguished type of Id proof categorised and stored separately. The training is done using a python library known as ImageAI. Trained model is then used for prediction. The input image is passed through the model to get the prediction. 

Extraction: The python library pyteseract is used to extract the information from the image. The Extracted Info is in the form of single string. This string is then segragated to get the useful structured data.
