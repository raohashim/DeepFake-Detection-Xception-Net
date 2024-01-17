# DeepFake-Detection-Xception-Net
A method for detecting deepfakes using the Xception Network architecture was suggested by FaceForensic++ (https://arxiv.org/pdf/1901.08971.pdf). Our implementation follows the parameters and technique outlined in the FaceForensic++ paper. This technique is commonly used as a benchmark to assess the effectiveness of new detection methods.

## Dataset
The processed dataset could be downloaded from this link: https://seafile.idmt.fraunhofer.de/u/d/b639276d15b9423bb11f/

## Here are the steps to follow to train a model for deepfake detection:

1. Extract frames from videos using the "Rename and Frame Extraction.ipynb" file. Simply add the path to the directory where the videos are stored.
 
2. Next, use the "Data_Analysis.ipynb" file to create test, train, and cv directories that contain only cropped faces from the previously extracted frames. Follow the instructions carefully to label and store the data for further processing.
 
3. To train the model, follow the instructions in the "Model Training.ipynb" file.
 
4. Finally, use the "Test_Xception.ipynb" file to evaluate the model's performance on unseen video data. Just follow the instructions provided.
