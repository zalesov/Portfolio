# Determining the age of customers

This project is an example of a computer vision problem.

**Goal**: to build a neural network that will determine the age of a person from a photo (The photo is input as a matrix with information about each pixel)

***The work was done on the Yandex.Practicum server, and in the work there are presented the functions of loading data, creating a neural network and training itm their output and result.***



### Libraries used:

* pandas
* numpy
* tqdm
* tensorflow.keras
* tensorflow.keras.models.Sequential
* tensorflow.keras.applications.resnet.ResNet50
* tensorflow.keras.optimizers.Adam
* tensorflow.keras.preprocessing.image.ImageDataGenerator
* tensorflow.keras.layers
 * Conv2D 
 * Flatten 
 * Dense
 * AveragePooling2D
 * AvgPool2D 
 * GlobalAveragePooling2D

*Project status*: finished

## Project conclusion: 

During the pre-analysis, the sizes of the incoming images were obtained (224,224)
A serial neural network was implemented in the model using a pre-trained ResNet50 network, without a "top", with one layer of pooling averaging information from the image, which ended with 1 neuron (since we need to get one number by task), with the activation function 'Relu', which allows you to discard to prevent negative values from being output. As a result, over 50 epochs, the model showed an average absolute error of 5.7.
