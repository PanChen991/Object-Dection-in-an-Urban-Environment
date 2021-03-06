# Object-Dection-in-an-Urban-Environment

In this project, you will apply the skills you have gained in this course to create a convolutional neural network to detect and classify objects using data from Waymo. You will be provided with a dataset of images of urban environments containing annotated cyclists, pedestrians and vehicles.

First, you will perform an extensive data analysis including the computation of label distributions, display of sample images, and checking for object occlusions.
![image](https://user-images.githubusercontent.com/94951202/162109046-394f63b2-634b-44a0-8ed0-05cf5fa01adc.png)

An example night image from the Waymo dataset, with annotations for vehicles and pedestrians.

You will use this analysis to decide what augmentations are meaningful for this project. Then, you will train a neural network to detect and classify objects.

You will monitor the training with TensorBoard and decide when to end it. Finally, you will experiment with different hyperparameters to improve your model's performance.

This project will include use of the TensorFlow Object Detection API, where you can deploy you model to get predictions on images sent to the API. You will also be provided with code to create a short video of their model predictions.
