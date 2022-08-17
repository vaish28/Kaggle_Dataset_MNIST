# Kaggle_Dataset_Mnist

MNIST ("Modified National Institute of Standards and Technology") is the de facto “hello world” dataset of computer vision. Since its release in 1999, this classic dataset of handwritten images has served as the basis for benchmarking classification algorithms. As new machine learning techniques emerge, MNIST remains a reliable resource for researchers and learners alike.

# Optidash-Challenge-OCR-for-hand-written-digits

- An implementation of an OCR for hand-written text  
- The algorithm takes a single file as input (JPEG, PDF) and returns all hand-written text (mostly digits) found and recognized on that input. 

"Note: Main goal for this challange is to make a Digit Recogonizer and I will be following the approach of using CNN and MLP model with some hyperparameter tunings to train the classifier. Training dataset for this part will be the MNIST dataset from the kaggle Digit Recogonizer Challange."

The presented code is a simple implementation of Convolutional Neural Network (CNN) for training a MNIST digit classifier.

CNN extracts the features of image and converts it into lower dimension without loosing its characteristics. 
The convolution layer and the pooling layer can be fine-tuned with respect to hyperparameters.

Input Layer - Input Layer in CNN should contain image data.Image data is represented by three dimensional matrix and needs reshaping into single column.

Convo Layer - Convo layer is sometimes called feature extractor layer because features of the image are get extracted within this layer. Result of the operation is single integer of the output volume. Convo layer also contains ReLU activation to make all negative value to zero.

Pooling Layer - Pooling layer is used to reduce the spatial volume of input image after convolution. It is used between two convolution layer. 

Framework used and Dependencies
- Keras
- Numpy
- Scikitlearn
- Matplotlib

According to the theory and observation from the Learning rate graphs, we can comment that the optimum and satisfactory results for the model had been obtained. 

Confusion Matrix:

![image](https://user-images.githubusercontent.com/43900410/185148126-ae24df81-605f-4059-96b2-47c72b2b11b4.png)


Detected integer:
![image](https://user-images.githubusercontent.com/43900410/185148193-dacb06ef-1884-44fe-8c4e-6726c83e9527.png)
