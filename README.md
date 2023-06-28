# MNIST_Data_Classification
This code was written by Kien Le Tran, a high schooler, in June 2023.

This Python notebook showcases a simple convolutional neural network (CNN) to classify handwritten numbers. Also includes a part where you can input your custom images.

The Python notebook must be runned on Google Colab if you want to classify your custom images, because it has a library to access images uploaded to the Google Colab workspace.

After opening the notebook on Gooogle Colab, the code blocks in LIBRARIES IMPORT, DATA IMPORT, MODEL CONSTRUCTION, and MODEL TRAINING are required to run.

On the left of your screen, open the file menu (file symbol). Right-click to upload your .jpg or .png 28x28 images to the workspace.

Right-click your file and select "copy path". Plug it into the imread module of the second last code block, and run the last 2 code blocks.

There seems to be some bias in the dataset with the numbers 7 and 9 that affected the training process, so you shouldn't expect too much when inputting your handwritten 7 and 9.
