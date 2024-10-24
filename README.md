I made a ANN model for Akbank Deep Learning Course. Firstly, I used tensorflow library for the create model. By the way, I developed the model with Kaggle notebook area.
After importing step, I started with assignment step the dataset in the code blocks. We used a large fish image dataset.
In the third code block I defined the label and path. After that, I create a graph to visualize the classes and data numbers they contain.
To check the classes, they contain correct fish images or not, I visualized the first images of the each classes.
And after the I sure about the classification is correct, I split the data to train and test.
After the splitting the data I did normalization with 1./255 and I split the train data again to validation data.
I choose 224x224 img size for the more detailed pixel. We are going with batch size 64 for the best training.
Input layer 1024 nodes (dropout 0.2), hidden layers(512, 216(dropout 0.2), 128, 64(dropout 0.2)) and output layer 9 nodes.
I used adam optimizer, categorical crossentropy for the 9 classes and metrics will be accuracy.

I trained the model. Finally, its accuracy %77 (which not is best but not bad). 
I visualized the models predictions and their true classes. So, I compare them. So You can see the results.

https://www.kaggle.com/code/lorstann/akbank-dl-project
