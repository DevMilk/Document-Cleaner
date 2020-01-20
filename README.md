# Document-Cleaner
Document Cleaner is a deep convolutional autoencoder model for generating a clean form of dirty documents.
------
Autoencoders can be used for ignoring the noise from image data. Here is a work for it.

Model trained for 300 epochs and its last loss is 0.0030. Loss function is "mean squared error" and optimizer is a "adamax" with 0.001 learning rate. Last layer's activation function is a custom function which maps values between -0.5 and 0.5 and other layers' activation functions are linear function.

-------

Other solutions to improve model:

-Getting more data by editing train images with rotating, transforming etc.

-Making experiments on more optimizer and more hyperparameters

-Trying more neuron counts on layers

-------
Here is the loss plot of model:

![alt text](https://github.com/DevMilk/Document-Cleaner/blob/master/Results/plot.png)

------
Cleaned Dirty Document examples:

![alt text](https://github.com/DevMilk/Document-Cleaner/blob/master/Results/result1.png)

![alt text](https://github.com/DevMilk/Document-Cleaner/blob/master/Results/result2.png)

![alt text](https://github.com/DevMilk/Document-Cleaner/blob/master/Results/result3.png)

![alt text](https://github.com/DevMilk/Document-Cleaner/blob/master/Results/result4.png)

![alt text](https://github.com/DevMilk/Document-Cleaner/blob/master/Results/result5.png)

![alt text](https://github.com/DevMilk/Document-Cleaner/blob/master/Results/result6.png)

![alt text](https://github.com/DevMilk/Document-Cleaner/blob/master/Results/result7.png)

![alt text](https://github.com/DevMilk/Document-Cleaner/blob/master/Results/result8.png)

![alt text](https://github.com/DevMilk/Document-Cleaner/blob/master/Results/result.png)




