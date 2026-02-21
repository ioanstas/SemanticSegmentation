# Urban Semantic Segmentation

This repository contains a Jupyter Notebook (`Urban_cities_segment.ipynb`) for performing Semantic Segmentation on urban driving scenes using models like UNet and SegFormer. It focuses on predicting pixel-level classes for street-view images.

## Dataset Requirements
This code requires two datasets for training and zero-shot evaluation:

### 1. Cityscapes (Training & Validation)
The primary dataset used is the 5000-image subset of Cityscapes. Your local workspace should be structured as follows:
- **Images:** Place them at `../Datasets/CityScapes5000/leftImg8bit/`
- **Labels:** Place them at `../Datasets/CityScapes5000/gtFine/`

### 2. BDD100k (Zero-Shot Evaluation)
To evaluate the models' zero-shot generalization out of the box, we use the BDD100k driving dataset.
- Place the BDD100k data at `../Datasets/BDD100k/`


## How to Run
1. Ensure your datasets are placed in the directory structure detailed above.
2. Open `Urban_cities_segment.ipynb` in Jupyter Notebook, JupyterLab, or VS Code.
3. Run the cells sequentially from top to bottom.
