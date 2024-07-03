
# Image Classification Project

This project focuses on building and training a machine learning model to classify images. The images are preprocessed, converted to grayscale, resized, and flattened before being used to train a classification model.

## Table of Contents

1. [Installation](#installation)
2. [Dataset](#dataset)
3. [Preprocessing](#preprocessing)
4. [Model Training](#model-training)
5. [Evaluation](#evaluation)
6. [Visualization](#visualization)
7. [Usage](#usage)
8. [Contributing](#contributing)
9. [License](#license)

## Installation

To get started, clone the repository and install the required dependencies.

```bash
git clone <repository-url>
cd <repository-directory>
pip install -r requirements.txt
```

## Dataset

The dataset used for this project should be organized in the following structure:

```
dataset/
├── raw-img/
│   ├── class_1/
│   │   ├── img1.jpg
│   │   ├── img2.jpg
│   │   └── ...
│   ├── class_2/
│   │   ├── img1.jpg
│   │   ├── img2.jpg
│   │   └── ...
│   └── ...
```

## Preprocessing

The preprocessing steps include:
- Converting images to grayscale
- Resizing images to 128x128 pixels
- Flattening images into 1D arrays

The preprocessing is done using the `load_images_and_labels` function.

## Model Training

The model is trained using a neural network implemented with PyTorch. The dataset is split into training and testing sets using an 80-20 split.

## Evaluation

The model is evaluated on the test set, and various metrics such as accuracy are calculated to assess its performance.

## Visualization

Random predictions from the test set are visualized using the `show_random_predictions` function, which displays 25 random images with their true and predicted labels.

## Usage

To run the notebook and train the model, simply execute the cells in the provided Jupyter notebook `main.ipynb`.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request.

## License

This project is licensed under the MIT License.
