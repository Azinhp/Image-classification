🖼️ Image Classification Model Comparison

Project Goal

This project compares three powerful image classification models—a custom CNN, ResNet50, and EfficientNetB0—to find out which one works best when you only have a very small dataset (300 total images) to train with.

This is important because in real-world projects, we often don't have millions of images!

📈 Model Performance Summary

We evaluated all models on the test data to see their final performance. The results show how well each model learned from the limited 300-image dataset.

Custom CNN ------> 65%

ResNet50 ------> 82%

EfficientNetB0 ------> 100%

Conclusion

The experiment clearly shows that EfficientNetB0 was the most effective model, achieving a perfect 100% accuracy. This suggests that modern models that use Transfer Learning (like ResNet50 and EfficientNet) are far superior to a custom-built CNN when the amount of training data is very small.

⚙️ Repository Details & Setup

1. Project Files

CNN.ipynb: Code for the Custom CNN model.

resnet.ipynb: Code for the ResNet50 model (using Transfer Learning).

efficientnet.ipynb: Code for the EfficientNetB0 model (using Transfer Learning).

requirement.txt: List of all necessary Python libraries.

2. How to Run the Project

Clone the repository:

git clone [https://github.com/Azinhp/Image-classification.git](https://github.com/Azinhp/Image-classification.git)
cd Image-classification


Install dependencies:

pip install -r requirement.txt


Data Requirement: The project uses the Plant Village Dataset from Kaggle:

Dataset Link: https://www.google.com/search?q=https://www.kaggle.com/arjuntejaswi/plant-village

The project needs the 300 images subset from this dataset to be placed in a folder named tomatoimages/. This folder must have a train/ and a validation/ subfolder:

Note: The actual images are not included here because they are too large for GitHub.

Run the Notebooks: Open the three .ipynb files in a Jupyter environment to train and test the models yourself.

✍️ Author

Azin Homayounpour - www.linkedin.com/in/azin-homayounpour
