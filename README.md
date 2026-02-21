# Urban Semantic Segmentation

This repository contains a Jupyter Notebook (`segmentation_urban.ipynb`) for performing Semantic Segmentation on urban driving scenes. It focuses on predicting pixel-level classes for street-view images.

## Setup and Installation

To run this notebook, you will need a Python environment with the following main libraries installed:
- `torch` & `torchvision`
- `numpy` & `pandas`
- `matplotlib`
- `transformers` (HuggingFace)
- `evaluate`

You can install them via pip:
```bash
pip install torch torchvision numpy pandas matplotlib transformers evaluate tqdm
```

## Dataset Requirements
This code expects the **Cityscapes** dataset (specifically the 5000 image subset). 
You must set an environment variable named `UNI_PATH` on your machine that points to the root directory where your `/Datasets/CityScapes5000` folder is located.

- **Images:** Expected at `leftImg8bit/`
- **Labels:** Expected at `gtFine/`

## How to Run
1. Ensure your `UNI_PATH` environment variable is set correctly.
2. Open `segmentation_urban.ipynb` in Jupyter Notebook, JupyterLab, or VS Code.
3. Run the cells sequentially from top to bottom.
