# Chest X-Ray Images Pneumonia Classification

This repository collects a set of experiments for classifying chest X-ray images as pneumonia or normal using classical machine learning, CNNs, transfer learning, and transformer-based models.

The project is organized as a notebook-driven exploration of multiple architectures and feature extraction approaches. It also includes a dataset reference and supporting materials for the report and presentation.

## Dataset

The dataset used by this project is the Kaggle Chest X-Ray Pneumonia dataset:

https://www.kaggle.com/datasets/paultimothymooney/chest-xray-pneumonia

If you are running the notebooks locally, download the dataset and place it in the expected local `data/` directory structure used by the notebooks.

## Project Contents

The repository contains these main notebooks:

- `Autoencoder.ipynb`
- `Convolutional_Neural_Network(CNN).ipynb`
- `Random_Forest_Hog_Extraction.ipynb`
- `Transefer_Learning(TL).ipynb`
- `vgg19-finetune-chest-xray.ipynb`
- `efficientnet.ipynb`
- `chest-xray-images-resnet50.ipynb`
- `deit-without-aug-with-aug-and-aug-with-se.ipynb`
- `swin-vit.ipynb`
- `swin-se-block-with-aug-without-aug.ipynb`
- `Ensambled Approach.ipynb`
- `hyperparameter-tuning.ipynb`
- `data_processing.ipynb`

## Suggested Workflow

1. Install the dependencies.
2. Download the Kaggle dataset.
3. Make sure the notebook paths match your local dataset location.
4. Run the preprocessing notebook first if you want to inspect or regenerate intermediate data.
5. Open and execute the model notebooks you want to compare.

## Supporting Files

- `data/dataset_link.md` contains the dataset URL.
- `others/` contains the project report and presentation materials.

## Notes

This repository is notebook-based, so there is no single training entry point. Each notebook represents a separate experiment or model pipeline.
