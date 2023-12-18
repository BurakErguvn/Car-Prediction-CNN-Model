
# Car Prediction CNN Model

“Car Prediction CNN Model” is a model that predicts the car brand from an image using a Convolutional Neural Network (CNN). The model was built using Numpy, Pandas, Tensorflow, Keras, and Matplotlib libraries. Keras was used for data preparation, Matplotlib was used to create tables, and Tensorflow was used to build the model. The data set used in the model consists of 5 car brands: Audi, Bmw, Ford, Mercedes, and Nissan. The data sizes of the classes in the data set are not equal to each other, but they are close. Grayscale was used instead of RGB when processing the data set to prevent the colors of the cars from affecting the training.


## Data Set

![Pie Graph]()

## Accuracy

![Training and Test Accuracy Graph]()


The training accuracy of the model is 0.89 and the test accuracy is 0.76. To increase the accuracy, several techniques were used, including BachNormalization, Dropout, and LearningRateScheduler. Details about these techniques can be found in the “note.txt” file.

  
## Lessons Learnt

It should be noted that the predictions are not consistent for images outside the test set, especially in the “Bmw” and “Ford” classes. The solution would be to increase the processing size of the images (with a more powerful computer) and enlarge the data set.

  
## Contact 

As a beginner in the field of deep learning, I am proud of my achievement and look forward to hearing your feedback.This is my e-mail address erguvenburak.dev@gmail.com 

  
