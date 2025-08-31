# BrainMriTumourSegmentation
A deep learning project on unsupervised brain tumour segmentation in ResUNet and DeepLabV3+ models. 
This project applies deep learning to brain MRI scans in order to segment tumour regions automatically. Two models were implemented, ResUNet and DeepLabV3+, with both being adapted for medical image segmentation tasks. The system is designed to act as a second-opinion tool, mimicking how doctors often seek additional opinions, by allowing users to view predictions from both models side by side.
# How to Run the program
To run the project, simply download the notebook from this repository and upload it to Google Colab or Jupyter online. The dataset should be uploaded into Google Drive or Jupyter folder, and the correct path needs to be updated in the notebook. Once this is done, running the cells will train and evaluate the models, displaying results such as accuracy, Dice score, and IoU, as well as visual tumour segmentation masks.

A simple web application is also included, built with Flask and deployable through ngrok on Colab. This allows users to upload an MRI scan and receive predictions from both models, including the original scan, the tumour mask, and an overlay. The design is minimal and user-friendly, making the results clear and accessible even for non-technical users.
