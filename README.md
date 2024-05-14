## Galaxy Morphological Classification

### Overview–

This project aims to classify galaxies into three morphological classes using machine learning techniques. The classes represent different shapes and structures of galaxies observed in astronomical images. We explored three different classification models: Support Vector Machine (SVM), K-Nearest Neighbors (KNN), and Convolutional Neural Network (CNN) with transfer learning using VGG-16 pre-trained on the ImageNet dataset.

### Dataset –

We used the Galaxy Zoo SDSS dataset, which contains over 68,000 galaxy images labeled with their morphological classifications. The dataset was preprocessed to extract relevant features and ensure equitable distribution of the three classes to mitigate bias.

### Methodology –

#### Data Preprocessing: 
Images from the Galaxy Zoo SDSS dataset were preprocessed to extract features and prepare them for model training. This involved resizing, normalization, and augmentation to enhance the model's ability to generalize.

#### Model Training and Evaluation:
SVM: We trained a Support Vector Machine classifier on the preprocessed image features and evaluated its performance using various metrics such as accuracy, precision, recall, and F1-score.
KNN: Similarly, we trained a K-Nearest Neighbors classifier on the preprocessed image features and evaluated its performance using the same set of metrics.
CNN (Transfer Learning): We utilized the VGG-16 architecture pre-trained on the ImageNet dataset as a feature extractor. We fine-tuned the model on our galaxy dataset and evaluated its performance.

#### Comparison and Conclusion:
We compared the performance of the three models based on accuracy and other classification metrics.
The CNN model with transfer learning achieved the highest accuracy of around 68%, outperforming SVM and KNN.





## Additional Data and Saved Models

For further exploration and use, additional data and saved models trained on approximately 3000 images are available. You can access them through the following link:

[Additional Data and Models](https://drive.google.com/drive/folders/13Wb2dNOPanHMtm4T9WAXcjTCax7VhNs9?usp=drive_link)
