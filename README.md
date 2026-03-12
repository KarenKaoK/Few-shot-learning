# Few-Shot Learning with the CUB Dataset

This repository is a sample notebook for training and evaluating a few-shot learning workflow on the CUB dataset. The implementation is based on the `easy-few-shot-learning` project and focuses on a practical prototype using classical training with episodic validation/testing.


### Overview

The main file in this repository is [Few_shot_sample_code.ipynb](/Users/ren/Desktop/karen/git_karen/Few-shot-learning/Few_shot_sample_code.ipynb), which demonstrates how to:

- prepare the CUB dataset
- train a backbone model with classical supervised training
- evaluate the model with Prototypical Networks
- run a simple `3-way 5-shot` few-shot classification setting
- visualize support and query samples from test episodes

### Project Content

- [Few_shot_sample_code.ipynb](/Users/ren/Desktop/karen/git_karen/Few-shot-learning/Few_shot_sample_code.ipynb): end-to-end notebook example for CUB few-shot learning

### Environment and Dependencies

This notebook is adapted from the `easy-few-shot-learning` ecosystem and uses:

- Python 3
- PyTorch
- `easyfsl`
- `gdown`
- Google Colab or a local GPU environment

Reference project:

- `easy-few-shot-learning`: https://github.com/sicara/easy-few-shot-learning

### Dataset Notes

The notebook uses the CUB dataset and includes a note that downloading large files directly in Colab may be blocked. In that case, the archive may need to be uploaded manually before extraction.

### How to Use

1. Open [Few_shot_sample_code.ipynb](/Users/ren/Desktop/karen/git_karen/Few-shot-learning/Few_shot_sample_code.ipynb) in Google Colab or a local Jupyter environment.
2. Install the required packages, including `easyfsl` and `gdown`.
3. Prepare the CUB dataset.
4. Run the training, validation, and test cells in order.
5. Review the visualization cells for support/query examples and predictions.

### Related Articles

This repository is part of a few-shot learning study series:

- [Few-Shot Learning (2): Implementing Few-Shot Learning on the CUB Dataset](https://karenkaods.medium.com/%E6%B7%BA%E8%AB%87few-shot-learning-2-%E5%AF%A6%E4%BD%9Ccub-%E8%B3%87%E6%96%99%E9%9B%86-few-shot-learning-902070fcfda3)
- [Few-Shot Learning (1): Getting Started](https://karenkaods.medium.com/%E6%B7%BA%E8%AB%87few-shot-learning-1-%E5%88%9D%E6%AD%A5%E8%AA%8D%E8%AD%98-3cb541a866e5)

