# 🌿 Plant Disease Detection

A deep learning project for detecting plant diseases from leaf images using **MobileNet** with transfer learning and fine-tuning.

## 📌 Project Overview

This project uses a pretrained MobileNet model to classify plant leaf images into different disease categories.

The model is trained using:

* Transfer Learning
* Fine-Tuning
* Data Augmentation
* Early Stopping
* Adam Optimizer

A **Gradio GUI** is included at the end of the notebook, allowing the user to upload a leaf image and get the predicted disease.

## 🧠 Model

The project uses **MobileNet** as the base model.

### Training Steps

1. Load and prepare the image dataset.
2. Resize images to the required input size.
3. Apply preprocessing and augmentation.
4. Use MobileNet with pretrained weights.
5. Train the classification layers.
6. Unfreeze the last layers of MobileNet.
7. Fine-tune the model using a small learning rate.
8. Evaluate the final model on the test dataset.
9. Use Gradio to create an interactive interface.

## 🖥️ Gradio GUI

The final notebook cell contains a Gradio interface.

The user can:

1. Upload a plant leaf image.
2. Send the image to the trained model.
3. Get the predicted disease.
4. View the prediction confidence.

## 📂 Project Structure

```text
Plant-Disease-Detection/
│
├── plant_disease.ipynb
├── README.md
└── requirements.txt
```

## ⚙️ Requirements

Install the required libraries:

```bash
pip install tensorflow gradio numpy pandas matplotlib scikit-learn pillow
```

Or:

```bash
pip install -r requirements.txt
```

## ▶️ How to Run

Open the notebook:

```text
plant_disease.ipynb
```

Run the cells in order.

At the end of the notebook, launch the Gradio interface.

## 📊 Evaluation

The model is evaluated using:

* Accuracy
* Loss
* Validation performance
* Test performance

## 🚀 Technologies

* Python
* TensorFlow / Keras
* MobileNet
* Transfer Learning
* Fine-Tuning
* Gradio
* NumPy
* Pandas
* Matplotlib
* Scikit-learn

## 👩‍💻 Author

Menna 

Computer Science & Artificial Intelligence Student
