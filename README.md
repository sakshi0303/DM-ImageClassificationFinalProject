# DM-ImageClassificationFinalProject


Course: 2228-CSE-5334-001-DATA MINING

Name: Sakshi
Maverick ID : 1001993702
Email: sx3702@mavs.uta.edu
Contact No.: +1 3153851203
Course Name: Computer Sci-MS Non Thesis (2st SEM)

- Compare performance between
    -CNN with transfer Learning , CNN without Transfer Learning,
    -SVM with CNN for feature extraction,
    -SVM with flattened image,
    -Decision Tree with CNN for feature extraction,
    -Decision Tree with flattened image array,
    -K Nearest Neighbor with CNN for feature extraction,
    -K Nearest Neighbor with flattened image array,
    -Artificial Neural Networks

    Explored transfer learning by leveraging VGG pre-trained models (https://www.tensorflow.org/api_docs/python/tf/keras/applications/vgg16/VGG16) to extract features. Using these features, the accuracy improved from 98% to 100%.

-Explored using CNN for feature extraction and feeding them to an SVM, DT an KNN.

-SVM accuracy rate dropped from 90.38% with flattened image as input to 24% with feature extraction

-Decision Tree accuracy rate dropped from 35% with flattened image as input to 22% with feature extraction

-KNN accuracy rate improved from 84% with flattened image as input to 96% with feature extraction

-Tried different train-test split ratios, the test dataset performance was consistently above 95% after shuffling the dataset and feeding it to the models.

-For the CNN model without transfer learning, added a convolution layer and dense layer with relu activation function instead of softmax which brought significant accuracy improvements from < 20% to 99%

-Explored different pre-processing techniques which included gray scaling, data augmentation, histogram equalization and rotation. All of these approaches decreased the accuracy. 

-Added dropout for regularization and more dense layers which led to further improvements in accuracy

-Experimented with different optimizers, rms optimizer achieved >99% accuracy at the 10th epoch compared to adam which achieved the same at 22nd epoch

-Batch size of the training data did not have significant impact to performance