# 50.039-Deep-Learning-Project-Audio-Emotion-Classifier-with-Song-Recommendation
A audio classifier network that suggests songs based on detected emotion for 50.039 Deep Learning Project 

## packages required
- gradio, numpy, librosa, torchaudio, pytorch.
- Versioning does not matter

## What is this?
Utilizing the dataset from https://www.kaggle.com/datasets/ritika0111/emotion-detection-dataset, we created a neural network predictor that outputs songs based on the input speech given in english. The whole process is as follows

![image](https://user-images.githubusercontent.com/72377837/163773262-c69f630e-4f86-4a26-a3cf-b67d92d55c83.png)

The inspriration came from wanting to have a song to reflect our moods. We developed this as a fun project to classify our voices into different emotions.


## What did we do?
- Tested and tried 5 different model architectures with training from scratch
- Only Xception has best model weights saved


## How to run a model:
- for 1., 2., 3., 5., download the .ipynb notebook and place somewhere in your Google Drive
- Copy the dataset over to a proper directory
- Change the directories within the notebooks to a suitable location, if read properly the notebooks will start executing code
- Make sure the individual dataset folders (angry,sad,fear,happy,disgusting,neutral) is in the **same directory** as the running notebook!
- Also make sure the _music_ folder is in the **same directory** as the running notebook!

### NOTE:
- for Xception, we have saved weights for this in a file _"model.pth"_, save this file along with the notebook in a suitable location.
- Run the cells for the interface WITHOUT the training code above to view the UI 

## Link to downloaded dataset
https://drive.google.com/drive/folders/1tBZWk5Ynl07TpRHQuKooG0iqKUN52nWQ?usp=sharing

## Link to video
