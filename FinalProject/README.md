#PREFACE

In the final project, you need to train a model to conduct an image classification of the images of adults and children. Please download the dataset we uploaded on the E3 (the compressed file includes the training data and testing data). Please use the toolbox of PyTorch to build the model.

Try to achieve a higher accuracy. The higher the accuracy, the higher the score. Moreover, you need to consider both model complexity (number of parameters) and computational complexity (FLOPs). Approaches with smaller models and faster computation speed for testing will receive higher scores.

#ABSTRACT

Here, we first do some research on the model frequently applied to the image classification and compare their performance on our dataset to find out the most suitable model. Moreover, we refer to a paper “Improving Object Detection using Enhanced EfficientNet Architecture” [https://doi.org/10.25394/PGS.23497763.v1] and use its three proposed techniques to enhance the model's performance. Afterwards, we add a fully connected layer at the bottom of the model to converge the parameters into two outputs. Then we adjust the hyperparameters to optimize the model. It shows that our custom EfficientNet can classify the images more accurately than the original EfficientNet, which means our work somehow meet the criteria of the final project.

