# -22--SANE-
Нейроэволюционные вычисления -SANE Алгоритм
# Нейроэволюционные вычисления 8ВМ22 Цяо Иньсюань

## № 22. SANE Прямого распространения 1 скрытый слой
The aim of the work is the implementation of a neural network structure optimization based on SANE (Symbiotic Adaptive Neural Evolution) algorithm.
The SANE algorithm optimizes the structure of a neural network by crossover and gene mutation, thus improving the performance of the network. 
In the above code, a neural network with two hidden layers is trained using the SANE algorithm with input layer dimension X_train.shape[1] and output layer dimension 1. During the iterative optimization, the structure of the network at different epochs is recorded and the weights of the first hidden layer are visualized. Then, the best model generated by the training was used to plot the convergence of the training and validation sets, showing the change in accuracy during the training process. Finally, the accuracy scores on the test set are calculated and plotted.
The dataset was taken from the Breast Cancer Wisconsin dataset in the UCI machine learning repository. Its purpose is to perform a binary classification task. Specifically, the SANE algorithm is used to optimize the neural network structure to predict the classification of benign and malignant breast tumors on a given breast cancer dataset. The dataset used in the code is a breast cancer dataset (breast-cancer.csv) containing the features of the breast tumor (e.g. radius, texture, circumference of the mass, etc.) and the corresponding diagnosis (M for malignant tumor and B for benign tumor). The breast cancer classification is predicted using a neural network optimized by the SANE algorithm.
