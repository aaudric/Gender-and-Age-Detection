# Gender and Age Detection Project 👴🏼 👵🏼

![Predictions](/model1/prediction%20vs%20reaal.png)

## Table of Contents

- [Gender and Age Detection Project 👴🏼 👵🏼](#gender-and-age-detection-project--)
  - [Table of Contents](#table-of-contents)
  - [Description](#description)
  - [Dataset](#dataset)
  - [Installation](#installation)
  - [Notebook Structure](#notebook-structure)
  - [Usage](#usage)


## Description
This project uses deep learning to predict gender and age from facial images. It leverages the UTKFace dataset to train a convolutional model that predicts the gender (man or woman) and age (as a continuous value) of individuals in images. This notebook includes loading the data, preparing the images, building and training the model, and visualizing the results.

## Dataset
The dataset used in this project is the UTKFace dataset, which is publicly available for academic research purposes. It contains over 20,000 face images with annotations of age, gender, and ethnicity. The images cover a wide range of ages, from 0 to 116 years old. More details and the dataset itself can be found at the [UTKFace website](https://susanqq.github.io/UTKFace/).

## Installation

To run this notebook, you must have Python installed, along with the following libraries :

- NumPy
- Matplotlib
- Pandas
- TensorFlow/Keras
- Seaborn
  

You can install all the necessary dependencies using pip:

```bash
pip install numpy matplotlib pandas tensorflow seaborn
```

## Notebook Structure

The notebook is structured as follows :

1. **Importing Necessary Libraries** : All required libraries are imported at the beginning of the notebook.

2. **Loading and Preparing Data** : Paths of images and corresponding labels are extracted and stored in a DataFrame.

3. **Data Visualization** : Distributions of ages and genders are visualized to provide insights into the data's composition.

4. **Image Preprocessing** : Images are converted to grayscale, resized, and normalized.

5. **Model Building** : A convolutional neural network (CNN) model is built to process the images.

6. **Model Training** : The model is trained on the data.

7. **Evaluation and Prediction** : The model is used to predict gender and age on new images, and results are visualized.

8. **Saving the Trained Model** : The trained model is saved for future use.

## Usage

To use this notebook :

1. Launch Jupyter Notebook or JupyterLab :

```bash
jupyter notebook
```

2. Open the `gad.ipynb` file in Jupyter.

3. Run the cells in the notebook in order.

