# DeepZero
A Sensors Based Deep Learning Model for Unseen Locomotion Mode Identification using Multiple Semantic Matrices

Step 1: Download SHL dataset from: http://www.shl-dataset.org/activity-recognition-challenge/

Step 2: Preprocess the dataset

Step 3: Remove empty values and take means over 20 values to reduce length of dataset from 6000 to 300.

Step 4: Set path and run run.sh file to get feature vector,

Step 5: Using human annoated matrix as given in our paper (A sensors based deep learning model for unseen locomotion mode identification using multiple semantic matrices).

Step 6: Down load glove dataset and run glove.py to obatin word2vec matrix

Step 7: Perform fully connected operation on the matrices and obtain attribute matrix.

Step 8: Run zsl.py to obtain the label of seen and unseen instances.
