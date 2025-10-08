# Image Classification App with PyTorch & Gradio

This project is a simple image classification web app built using Gradio and PyTorch. It uses a custom CNN model to classify uploaded images into one of three categories: Cat, Dog, or Person. The app displays both the predicted label and the labeled image.

## 🚀 Features

- Upload and classify images as Cat, Dog, or Person
- Custom CNN model built with PyTorch
- Real-time prediction and image labeling
- Gradio-based interactive web interface

## 🧠 Technologies Used

- Python
- PyTorch
- OpenCV
- PIL (Pillow)
- Gradio
- torchvision

## 📁 File Structure

- `app.py`: Gradio interface for image classification
- `predict.py`: CNN model definition and prediction logic
- `model/cnn_128_model-100.pth`: Pretrained model weights
- `uploaded_image.jpg`: Temporary file for uploaded image
- `labeled_image.jpg`: Output image with prediction label

## 🔐 Environment Variables

No environment variables are required.

## 🛠️ How to Run

1. **Clone the repository:**

```
git clone https://github.com/yourusername/image-classification-app.git
cd image-classification-app
```
2. **Install dependencies:**   
```
pip install -r requirements.txt
```

3. **Ensure the model file is placed at:**
```
model/cnn_128_model-100.pth
```

4. **Run the app:**
```
python app.py
```
