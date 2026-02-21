# Urban Semantic Segmentation

This repository contains a Jupyter Notebook (`segmentation_urban.ipynb`) for performing Semantic Segmentation on urban driving scenes. It focuses on predicting pixel-level classes for street-view images.

## Dataset Requirements
This code expects the **Cityscapes** dataset (specifically the 5000 image subset). 
You must change the environment variable named `UNI_PATH` to the root directory where your `/Datasets/CityScapes5000` folder is located.

- **Images:** Expected at `leftImg8bit/`
- **Labels:** Expected at `gtFine/`

## How to Run
1. Change `UNI_PATH` environment variable to the root directory of your dataset from cityscapes. 
2. Open `segmentation_urban.ipynb` in Jupyter Notebook, JupyterLab, or VS Code.
3. Run the cells sequentially from top to bottom.
