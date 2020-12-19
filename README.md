# Chest-X-ray-Image-Classification-using-Decision-Tree-model
The dataset contains Chest X-ray images classified as Covid-19, Normal and Pneumonia. 
The first step is to extract features from the images using VGG16 - a pre-trained CNN and then train decision tree model. I have used GridSearchCV in order to identify the best value for the hyper-parameter, max_leaf_nodes.

Reference links for feature extraction using transfer learning & classification:

https://www.youtube.com/watch?v=PaSEVY9d4RI
https://www.kaggle.com/orion99/transfer-learning-cnn?select=seg_test
https://datascience.stackexchange.com/questions/51100/keras-how-to-connect-a-cnn-model-with-a-decision-tree
https://appliedmachinelearning.blog/2019/07/29/transfer-learning-using-feature-extraction-from-trained-models-food-images-classification/
