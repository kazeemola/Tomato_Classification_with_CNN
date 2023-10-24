# Tomato Leaf Disease Image Classification Project


This GitHub repository contains the Tomato Leaf Disease Image Classification project, which was built using Convolutional Neural Networks (CNN) and FastAPI. The project aims to classify images of tomato leaves into different disease categories, helping farmers and researchers identify and manage tomato plant diseases effectively.

## Project Overview

Tomato is one of the most widely grown and consumed vegetables worldwide. However, it is susceptible to various diseases that can severely affect crop yield and quality. This project addresses this issue by providing an automated system for classifying images of tomato leaves into different disease categories. The primary goals of this project are:

1. **Disease Detection:** Accurately identify and classify tomato leaf diseases, including but not limited to early blight, late blight, and bacterial spot.

2. **Early Diagnosis:** Early detection of diseases is crucial for implementing timely preventive measures to protect crop health.

3. **User-Friendly Interface:** The FastAPI-based web application provides an easy-to-use interface for users to upload tomato leaf images and receive disease classification results.

4. **Educational Resource:** This project can be used as an educational tool to learn about image classification, deep learning, and FastAPI.

## Repository Structure

The project is organized into the following directories and files:

- `data/`: This directory contains the dataset used for training the CNN model. It includes subdirectories for each disease category.

- `saved_models/`: Here, you can find the trained CNN model for image classification.

- `api/`: This directory contains the FastAPI application code for serving the image classification model.

- `requirements.txt`: This file lists the Python dependencies required to run the project.

- `Tomato_notebook.ipynb` : This file contains the notebook for the EDA and training of the model

- `README.md`: This document provides an overview of the project and instructions for setting it up and running the application.

## Getting Started

To get started with the Tomato Leaf Disease Image Classification project, follow these steps:

1. Clone this repository to your local machine:

  

2. Install the required dependencies using pip:

   ```
   pip install -r requirements.txt
   ```

3. Train the CNN model on your dataset or use the provided dataset in the `data/` directory.

4. Save the trained model to the `saved_models/` directory.

5. Run the FastAPI application:

   ```
   uvicorn app.main:app --host 0.0.0.0 --port 8000
   ```

6. Access the web application by opening a web browser and navigating to `http://localhost:8000`.

7. Upload an image of a tomato leaf to get disease classification results.

## Docker Support

You can also run the FastAPI application using Docker. Build the Docker image by running the following commands:

```
docker build -t tomato-leaf-disease-app .
docker run -p 8000:8000 tomato-leaf-disease-app
```

## Acknowledgments

This project was developed by Kazeem Okunola and Naim Inusa as part of Personal Project . We would like to thank the open-source community for their contributions and the creators of FastAPI and PyTorch for their excellent tools and libraries.

## License

This project is licensed under the [MIT License](LICENSE).

## Contact

For any questions or feedback, feel free to reach out to achieverk2@gmail.com .

We hope this project proves to be a valuable resource for disease diagnosis and management in tomato crops. Enjoy using it!