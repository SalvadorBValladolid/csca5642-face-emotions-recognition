## Face recognition model
#### This is the final project for the CSCA 5642 class, introduction to Deep Learning.

##### Dataset Description:

The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centred and occupies about the same amount of space in each image. Each face image belongs to one of the following expression categories:

- 0 = Angry
- 1 = Disgust
- 2 = Fear
- 3 = Happy
- 4 = Sad
- 5 = Surprise
- 6 = Neutral

##### Manas Sambare. (2013). Face expressions recognition . Kaggle. https://www.kaggle.com/datasets/msambare/fer2013/data

##### Problem Description:

- The task is to build an image-based facial emotion recognition model. The main challenges include low-resolution images, noisy labels, strong variation in lighting and pose, and class imbalance.

- The goal is to develop a model that accurately classifies the emotion in each image, using techniques such as data augmentation, class-balancing methods, and robust evaluation metrics. I'll use the following:
    - F1-Score
    - Accuracy
    - Confusion Matrix

- Also another objective is experiment and try different model architectures in order to see which is the best in terms of performance.

#### Pipeline:
- Exploratory Data Analysis
- Data preparation
- Model architecture definition
- Results
- Hyperparameter tuning
- Final results
