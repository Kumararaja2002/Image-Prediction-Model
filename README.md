## 🌐 Try It Online

You can try the image classification app directly on Hugging Face Spaces:

👉 [Image Classification App on Hugging Face](https://huggingface.co/spaces/Kumararaja/Image-Classification-App)

No need to download or run anything locally — just upload an image and get predictions instantly!

## ⚠️ Model File Notice

Due to GitHub's 25MB file size limit, the trained model file (`cnn_128_model-100.pth`, ~30MB) is **not included** in this repository.

To run the app locally, you can:
1. **Train the model yourself** using the architecture in `predict.py`.
2. Or, **use the Hugging Face Space** linked above to run the app online and get the modelfile from the Huggingface files option.

Once you have the model, place it in the following path:

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
where I coul
```
model/cnn_128_model-100.pth
```

4. **Run the app:**
```
python app.py
```
