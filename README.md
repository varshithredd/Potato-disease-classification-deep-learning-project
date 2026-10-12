# Potato Disease Classification

A notebook-based deep learning project focused on potato disease image classification, with separate experiments for TensorFlow Lite conversion and model quantization.

## Repository guide

| Notebook | Focus |
| --- | --- |
| [Image data generator workflow](potato-disease-classification-model-using-image-data-generator.ipynb) | Image-classification experiment using an image data generator |
| [Classification model](potato-disease-classification-model.ipynb) | Main classification notebook |
| [Post-training conversion](tf-lite-conversion-post-training.ipynb) | Post-training TensorFlow Lite conversion experiment |
| [Quantization-aware training](tf-lite-conversion-quantized-aware-training.ipynb) | Quantization-aware training experiment |
| [TensorFlow Lite converter](tf-lite-converter.ipynb) | Additional conversion workflow |

## Getting started

1. Clone or download this repository.
2. Open a notebook in Jupyter or another compatible notebook environment.
3. Review its imports, dataset paths, and model file paths before running cells.
4. Install the dependencies referenced by that notebook and provide the required image dataset or model files.
5. Run cells in order.

## Reproducibility

The repository contains notebooks rather than a packaged application. Dataset locations and dependency versions must be checked in the individual notebooks. Results depend on the dataset, split, environment, and training configuration; no independently verified benchmark is claimed here.
