# Description
Food security for billions of people on earth requires minimizing crop damage by timely detection of diseases.Developing methods for detection of plant diseases serves the dual purpose of increasing crop yield and reducing pesticide use without knowing about the proper disease. Along with development of better crop varieties, disease detection is thus paramount goal for achieving food security. The traditional method of disease detection has been to use manual examination by either farmers or experts, which can be time consuming and costly, proving infeasible for millions of small and medium sized farms around the world.
This project is an approach to the development of plant disease recognition model, based on leaf image classification, by the use of deep convolutional networks. The developed model is able to recognize 38 different types of plant diseases out of of 14 different plants with the ability to distinguish plant leaves from their surroundings.

# Leaf Image Classification
![image](https://github.com/user-attachments/assets/633b6228-233a-4233-889e-d04cd860c1d6)
This process for building a model which can detect the disease assocaited with the leaf image. The key points to be followed are:

Data gathering

The dataset taken was "New Plant Diseases Dataset". It can be downloaded through the link "https://www.kaggle.com/vipoooool/new-plant-diseases-dataset". It is an Image dataset containing images of different healthy and unhealthy crop leaves.

Model building

I have used pytorch for building the model.
I used three models:-
The CNN model architecture consists of CNN Layer, Max Pooling, Flatten a Linear Layers.
Using Transfer learning VGG16 Architecture.
Using Transfer learning resnet34 Architecture.
Training

The model was trained by using variants of above layers mentioned in model building and by varying hyperparameters. The best model was able to achieve 98.42% of test accuracy.

Testing

The model was tested on total 17572 images of 38 classes.
The model used for prediction on sample images. It can be seen below:

![image](https://github.com/user-attachments/assets/c080fe01-2b98-4bf9-b682-df49d91072b9)
![image](https://github.com/user-attachments/assets/08833953-387f-4fa2-bc06-6e98cbed46fc)







