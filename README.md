# HAM10000
The order of executing programs should be-
1. Image_loader-1.ipynb. This file generates an array of RGB pixels of the 10015 images in the size 32x32
2. Project_pre_processing.ipynb. This file cleans the pixel data and handles the imbalance nature using SMOTE and saves the X and y data as X_sm and y_sm
3. project_model.ipynb. This file has the train test split and 2 models. First without any regularization and second with dropout layers.
