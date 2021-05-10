# NeuralNetwork
Link for dataset: https://drive.google.com/file/d/12_WTFi9ppvD-loaWUWpUar25Z3nT5k9P/view



STEPS FOR CODE EXECUTION:
first split the dataset of all all employees folder into test and train apply some transformations on the images

Define your CNN model with a set of convolutions followed by a non-linearity (ReLU in our case) and a max-pooling layer a linear classification layer for classifying an image into 1012 categories (these are the number of employees in the company)

We are using Adam optimizer with 0.0001 learning rate along with Cross Entropy Loss for our model

Finally we are training our dataset in by using Test train functions calulating train/test loss accuracy and predictions

After training and testing our model once we are satisfied with the accuracy we can provide two input one is the employee selfie and snother is passpost size image
after calculating our model will predict id(the employee ID of the pic) after comparing and the two image we will predict whether its a match or not and the confidence value will be predicted bt our function calculating mean of their accuracy

![Screenshot (22)](https://user-images.githubusercontent.com/83956407/117659919-248a2a00-b1ba-11eb-9722-a995ebc87d53.png)
![Screenshot (20)](https://user-images.githubusercontent.com/83956407/117660057-513e4180-b1ba-11eb-95b1-e1da5692b086.png)
