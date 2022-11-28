# How to Execute Ice Layer Thickness Prediction

1. Download the dataset from the link found in "data/dataset-link" (assuming that you have permission). In the second cell of the notebook, change MAT_FOLDER_PATH and BIN_FOLDER_PATH to local paths to "image/" and "layer_bin/" respectively. After doing so, you should be able to run cells 1-6, which will load the dataset into memory.
2. Download the file "data/splits.npy". In cell 7, change SPLIT_PATH to the local path to this file. After doing so, you should be able to run all cells up to and including training and testing the model.
3. Cells 14, 16, and 18 contain hard-coded paths that are used to save/load results files. These cells are not necessary to run, but if you want to save the results in order to reproduce them, you can change these hard-coded paths to local paths.
