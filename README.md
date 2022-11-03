# Image-Classification
 Create and train an image classifying model using opencv, SVM and opengridsearch on Jupyter
Manual data cleaning for 7 faces 
	1. Rihanna
	2. Amitabh Bachchan 
	3. Dwayne Johnson
	4. harry Styles
	5. Kylie Jenner
	6. Leonardo DiCaprio 
 7. Steve Harvey
Technologies used in this project, Jupyter notebook, Sklearn for model building, Matplotlib & Seaborn for data visualization, Python, Numpy and OpenCV for data cleaning

Explanation about folder structure files is given as comment

To train your own model with different images you can use the dataset folder and add your images there
Steps
1. Data Collection
collect images and separte each person image ini separate folders
2. Data Cleaning
use the code to crop the face and create them in cropped folder in dataset. Manually check cropped photos to ensure no inconsistent images. These cropped images will be used to train the model. 
3. Training Model
Trained model- using raw images and wavelet transformed images to perform vertical stacking of them and train model and then hyper tune it!
Wavelet transformed imaged- to extract features from a cropped image!
GridSearch used to try different models with different parameters and come up with best model and parameters









