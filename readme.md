# Lung Disease Classification using Deep Learning

This project focuses on classifying different types of lung diseases from chest X-ray images using a deep convolutional neural network. The model is built using TensorFlow and Keras, leveraging transfer learning with the MobileNetV2 architecture.

## Dataset

The model is trained on the "Lungs Disease Dataset (4 types)" from Kaggle. The dataset contains images for five different classes:

- Tuberculosis
- Bacterial Pneumonia
- Corona Virus Disease
- Normal
- Viral Pneumonia

The dataset is split into training, validation, and testing sets to ensure proper evaluation of the model's performance.

## Model Architecture

The classification model is based on the **MobileNetV2** architecture, pre-trained on the ImageNet dataset. Transfer learning is employed to adapt the model to the specific task of lung disease classification. The final layers of the model are customized and trained on the lung disease dataset.

## Getting Started

To run this project, you will need to have Python and Jupyter Notebook installed. You can follow these steps to get started:

1.  **Clone the repository:**

    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2.  **Install the required dependencies:**

    ```bash
    pip install tensorflow keras pandas matplotlib
    ```

3.  **Download the dataset:**

    The notebook includes code to download the dataset from Kaggle. Make sure you have your Kaggle API credentials set up.

4.  **Run the Jupyter Notebook:**

    ```bash
    jupyter notebook Lungs.ipynb
    ```

## Results

*(You can add your model's performance metrics here, such as accuracy, precision, recall, and F1-score. You can also include a confusion matrix or other visualizations to showcase the results.)*

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to open an issue or submit a pull request.
