
# Emotion-Based Music Recommendation System

## Overview
This project focuses on **Music Information Retrieval and Multiclass Classification** using **Deep Learning**. The system classifies songs into different emotional categories and can be used to recommend music based on emotions.

##  Dataset
The dataset consists of **2500 .wav files** labeled with five emotions:
-  **Aggressive** (500 files)
-  **Dramatic** (500 files)
-  **Happy** (500 files)
-  **Romantic** (500 files)
-  **Sad** (500 files)

## Project Structure
The project contains three main Jupyter notebooks:

1. **`emotion-based-music-recommender-resnet50v2.ipynb`**  
   - Data Preprocessing  
   - Visualizing classes  
   - Deep Learning Model (ResNet50V2)

2. **`accuracy-96-6.ipynb`**  
   - Uses a trained model achieving **96.6% accuracy**  
   - Feature extraction and testing  

3. **`music-emotion-recognition.ipynb`**  
   - Data exploration and preprocessing  
   - Model training using deep learning (Librosa for feature extraction)  

##  Installation & Dependencies
To run the project, install the required dependencies:

```bash
pip install librosa numpy pandas tensorflow matplotlib seaborn
```

##  Running the Model
1. Load the dataset.
2. Run the preprocessing steps.
3. Train the model.
4. Evaluate accuracy and recommend music based on detected emotions.

##  Results
- Achieved **96.6% accuracy** on emotion classification.
- Effective in emotion-based music recommendation.

##  Datasets
You can download the datasets from Google Drive:

- [FER Dataset](https://drive.google.com/drive/folders/1FxptaxkxhxB930HSxEqxzUpS_hWUyAJF?usp=sharing)
- [278k Emotion Labeled Spotify Songs](https://drive.google.com/drive/folders/1FxptaxkxhxB930HSxEqxzUpS_hWUyAJF?usp=sharing)
- [Music Information Retrieval Dataset](https://drive.google.com/drive/folders/1FxptaxkxhxB930HSxEqxzUpS_hWUyAJF?usp=sharing)



