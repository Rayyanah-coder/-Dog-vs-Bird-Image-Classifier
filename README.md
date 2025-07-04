# Dog vs Bird Image Classifier
 simple AI-powered image classification tool that distinguishes between dogs and birds trained by Teachable Machine.
---

## 📌 What It Does

- Classifies an uploaded image as either a **Dog** or a **Bird**
- Uses a `.h5` model trained on Teachable Machine
- Runs fully in Google Colab (no installation required)
- Outputs the predicted class and confidence score

---

## 🧠 Model Info

- Model type: Image classification
- Trained on: Custom dataset via [Teachable Machine](https://teachablemachine.withgoogle.com/)
- Classes: `Dog`, `Bird`

---

## 🚀 How to Use

1. Open the notebook: [`classificationAIModel.ipynb`](main.ipynb) in **Google Colab**
2. Upload the following files when prompted:
   - `keras_model.h5`
   - `labels.txt`
   - An image (e.g. `dog.jpg`)
3. Run the cells in order
4. You'll get output like:
![Image](https://github.com/user-attachments/assets/4ac5f434-cf63-44b5-a343-147bc8773927)

---

## 🛠 Requirements

You don’t need to install anything! Just open the notebook in **Google Colab** and you're good to go.

Colab installs dependencies automatically:
- TensorFlow 2.12.1
- NumPy
- Pillow
