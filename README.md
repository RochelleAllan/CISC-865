# CISC-865
Image classification using CNN with Keras and VGG16

Convolutional networks in itself is a class of deep learning and plays a huge role in image recognition and classification. This is used at the core of different tagging algorithms like the one present in Facebook and even tagging in self-driving automobiles. They are found in security and the health industry. They are the popular choice because of how efficient they are along with the speed at which they work. To describe the image classification process, it starts with an input which is most often a picture (a dog) and receives an output that represents the class to which it belongs (“dog” in this case) which is nothing but the probability of to which that input belongs judged by the model. The project starts with an image classification problem implementing CNN with  Keras Sequential network to target it. 

In the case of image classification, the best way to validate the models are to check the accuracy with which a model correctly assigns the right label for a given input image. The performance is evaluated and the focus moves to using pre-trained VGG16 to extract features and address this challenge. VGG-16 is a type of CNN which is fine tuned and achieves a much better accuracy. 
These models are coded using python.

The images used for training and testing images used are dogs, pandas and cats. The training size is 9000 images in total and the testing size is 2696 in total. The final accuracy achieved is 94 percent. The proportion of the training data used.

A jupyter notebook named Image-classification-CNN-Keras-VGG16.ipynb :  https://github.com/RochelleAllan/CISC-865/blob/main/Image-classification-CNN-Keras-VGG16.ipynb is submitted along with the 2 datasets- training and test data called animal_train and animal_test respectively with each output shown clearly.
