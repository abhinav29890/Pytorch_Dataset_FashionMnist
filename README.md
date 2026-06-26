"# Pytorch_Dataset_FashionMnist

A small PyTorch example demonstrating how to use `torchvision.datasets.FashionMNIST` with `torch.utils.data.DataLoader`.

## Contents

- `datasets_dataloader.ipynb` - Jupyter notebook showing how to:
  - download and load the FashionMNIST dataset
  - inspect sample images and labels
  - visualize examples with matplotlib
  - create and use `DataLoader` objects for batching and shuffling

## Requirements

- Python 3.8+
- PyTorch
- torchvision
- matplotlib

## Setup

1. Install dependencies using pip:

```bash
pip install torch torchvision matplotlib
```

2. Open the notebook:

```bash
jupyter notebook datasets_dataloader.ipynb
```

## Usage

- Run the notebook cells to download FashionMNIST and explore the dataset.
- The notebook loads the training and test splits with `transform=ToTensor()`.
- It then builds `DataLoader` instances with a batch size of 64 and shuffling enabled.

## Notes

- The dataset is downloaded to the `data/` folder by default.
- This repository is meant for learning how PyTorch datasets and dataloaders work with image data.
" 
