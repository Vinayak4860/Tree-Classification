# 🌳 Tree Species Classification – Week 1 Report

Welcome to the first week of the **Tree Species Classification** project! This repository presents the initial exploration and analysis of a tree image dataset aimed at developing an AI-powered classifier that can accurately identify various tree species based on images.

## 🔍 Project Overview

The goal of this project is to build a machine learning model that classifies tree species using leaf and tree images. This model can assist botanists, environmentalists, or nature lovers in identifying tree species quickly and accurately.

In **Week 1**, we focused on:

* Setting up the project environment in **Google Colab**
* Loading and inspecting the dataset
* Understanding class distributions
* Checking image dimensions and formats
* Displaying sample images from the dataset

## 📂 Dataset Details

* **Source**: [Kaggle – Tree Species Identification Dataset](https://www.kaggle.com/datasets/viditgandhi/tree-species-identification-dataset?resource=download)
* **Classes**: 30 Tree species
* **Images**: 1,596 total images
* **Data Structure**: Each class has its own folder containing respective images.

Here are some of the species in the dataset:

```
['shirish', 'pilikaren', 'pipal', 'simlo', 'vad', 'sugarcane', 'sitafal', 'sonmahor', 'saptaparni', 'other', 'kanchan', 'jamun', 'kesudo', 'motichanoti', 'mango', 'gulmohor', 'nilgiri', 'neem', 'khajur', 'gunda', 'cactus', 'coconut', 'bamboo', 'bili', 'amla', 'garmalo', 'asopalav', 'champa', 'banyan', 'babul']
```

> 📌 Note: The `other` category contains 150 images, likely representing miscellaneous or unidentified trees.

## 📊 Dataset Exploration

### ✅ Class Distribution

We analyzed the number of images available per class to ensure data balance. Here’s a summary:

* Most classes have **49–50 images**
* The `other` class has **150 images**
* Total classes: **30**
* Total images: **1596**

### 🖼️ Image Properties

Using OpenCV and NumPy, we examined 10 images from each class:

* **Min resolution**: 135 x 146
* **Max resolution**: 1699 x 1300
* **Average resolution**: \~254 x 290
* **Channels**: RGB (3 channels)

## 🧪 Sample Image Visualization

We visualized 15 random class images to get a visual understanding of the data variety:

![Sample Images](#) <!-- (Optional: You can add image links if hosted later) -->

Each subplot is labeled with the corresponding class name to make it easy to understand what the images represent.

## 🧰 Tools & Environment

* 📓 **Google Colab** (used for writing and executing the code)
* 🐍 **Python Libraries**:

  * `cv2` (OpenCV)
  * `numpy`
  * `matplotlib`
  * `collections`
  * `os`

## 🗓️ What's Next (Week 2 Plan)

In the upcoming weeks, we plan to:

* Preprocess and resize all images to a uniform shape
* Split the dataset into training, validation, and test sets
* Build and train a CNN-based classification model
* Evaluate model accuracy and tune hyperparameters

## ✍️ Author

**Bhavuk Vinayak**
Bachelor of Computer Applications (BCA) Student
Passionate about AI, Computer Vision, and Real-world ML Applications 🌿

## ⭐ Acknowledgements

* Special thanks to [Vidit Gandhi](https://www.kaggle.com/viditgandhi) for sharing the dataset on Kaggle.
* Google Colab for providing an easy and powerful cloud-based Python environment.
