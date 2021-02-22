# Traffic_sign_Classification
This is a simple deep learning model to classify among the traffic sign boards from BelgiumTS dataset. 

**About Dataset:** The Dataset is taken from BelgiumTS Classification data. Which has two seprate folders for training and testing data along with its labels. The training data set consists of 4575 images in ppm format and testing data consist of 2520 images from different 62 classes of traffic sign boards.

**About Model:** A Simple 2D CNN model is used to classify among the different classes to detect traffic sign boards. The model consist of 5 conv layer with maxpooling layer and 2 fully connected layer and a softmax layer. we have used ReLU as activation function and Dropout layer is used for regularization.

The **input size** is (128,128,3)
**Training Image Set** is of 4540 image files
**validation Image Set** is of 1136 image files
**Testing Image Set** is of 1419 image files

The model is trained for 50 epoch with batch size of 32, Adam optimizer is used with categorical crossentropy loss.It gives the training Accuracy and Validation Accuracy  of **94.67% and 96%** respectively.
The Testing Accuracy is**97.18% **

**Attachments:**

**TSC_CNN_model.ipynb:** A jupyter notebook file trained and tested using Google Colab. It consists of preprocessing of images, CNN model and trained variables and tested predictions.

**Loss_Graph_CNN and Acc_Graph_CNN**: loss graphs and Accuracy Graphs

**TSC_CNN_model.html:** An downloaded Html file for trained and tested model.

**References:**

Radu Timofte, Victor Adrian Prisacariu, Luc J. Van Gool, and Ian Reid, Combining Traffic Sign Detection with 3D Tracking Towards Better Driver Assistance. Emerging Topics in Computer Vision and its Applications (editor: C.H. Chen). World Scientific Publishing. September 2011.

https://www.kaggle.com

https://colab.research.google.com
