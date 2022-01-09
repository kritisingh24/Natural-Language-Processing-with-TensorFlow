# Natural-Language-Processing-with-TensorFlow

1) Text Classification :
   #### Dataset : https://storage.googleapis.com/wdd-2-node.appspot.com/x1.json
   Classifying news headlines as sarcastic and non-sarcastic. Sequential neural network model has been used with the following layers:
   Embedding layer 
   Flatten layer
   Dense layer with activation function 'relu'
   Dense layer with activation function 'sigmoid'.
   Compilation of the model is performed using loss - binary_crossentropy, optimizer='adam' and metrics= accuracy.
   
   <img width="432" alt="image" src="https://user-images.githubusercontent.com/76790650/148669352-b04819a3-d6b7-4531-be93-03a32590e37f.png">

   ##### Result:
   Training accuracy - 99.99% and testing accuracy 83.36%.
