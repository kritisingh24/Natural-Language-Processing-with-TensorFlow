# Natural-Language-Processing-with-TensorFlow

### 1) Text Classification using simple Neural Network
   #### Dataset : https://storage.googleapis.com/wdd-2-node.appspot.com/x1.json
   Classifying news headlines as sarcastic and non-sarcastic. Sequential neural network model has been used with the embedding layer, elatten layer, dense layer with activation function 'relu' and dense layer with activation function 'sigmoid'.
   
   Compilation of the model is performed using loss - binary_crossentropy, optimizer - adam and metrics - accuracy.
   
   #### Embeddings projection on TensorFlow projector:
   Created vector - vectors.tsv and meta file - vectors.tsv from embedding layer
   
   <img width="432" alt="image" src="https://user-images.githubusercontent.com/76790650/148669352-b04819a3-d6b7-4531-be93-03a32590e37f.png">

   #### Result:
   Training accuracy - 99.99% and testing accuracy 83.36%.
   
   #### Accuracy and loss graphs :
   ![image](https://user-images.githubusercontent.com/76790650/148669458-d1e23952-e247-444b-82a5-ab67dedc12c1.png)
   
### 2) Text Classification using LSTM
   #### Dataset : https://storage.googleapis.com/wdd-2-node.appspot.com/x1.json
   Implementation of an LSTM model to classify news headlines as sarcastic or not_sarcastic. We will analyse the accuracy and loss curves for training and validation sets.        Sequential neural network model has been used with the embedding layer, two bidirectional LSTM layers with 64 and 32 as number of outputs, dense layer with activation          function 'relu' and dense layer with activation function 'sigmoid'.
   
   Compilation of the model is performed using loss - binary_crossentropy, optimizer - adam and metrics - accuracy.

   #### Result:
   Training accuracy - 99.99% and testing accuracy 83.36%.
   
   #### Accuracy and loss graphs :
   ![image](https://user-images.githubusercontent.com/76790650/148669458-d1e23952-e247-444b-82a5-ab67dedc12c1.png)
