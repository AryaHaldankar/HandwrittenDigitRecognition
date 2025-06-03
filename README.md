# 📝 Handwritten Digit Recognition Model

Welcome to my **Handwritten Digit Recognition** project! This is a machine learning model I built **from scratch** — without using high-level libraries like TensorFlow or PyTorch. It reads and understands handwritten digits (like those from the MNIST dataset), just like a person would!

## 💡 What This Project Does

This model takes an image of a handwritten digit (from 0 to 9) and predicts which digit it is. Imagine writing a number on paper, taking a picture of it, and the computer tells you exactly what number you wrote — that’s what this does!

## 🧠 How It Works

At its core, this project is a **neural network** — a simplified version of how the human brain works. It learns from thousands of examples of handwritten digits and gets better over time.

By default, the model has:
- **2 layers**
- First layer with **40 neurons**
- Second layer with **20 neurons**

But here’s the cool part — you can change the structure of the model to whatever you want! Just call the `gradient_descent()` function and pass in your own custom list of layer sizes. It’s that flexible.

## ⚙️ Features

- 🧱 Custom-built from scratch (no ML libraries!)
- 🔁 Trains using gradient descent
- 🔧 Adjustable number of layers and neurons
- 🖼️ Works with handwritten digit images (like MNIST)
---

## 🚀 Getting Started

Follow these steps to set up and run this project on your local machine.

### 📁 Prerequisites

- Python 3.x installed
- `pip` (Python package manager)

---

### ⚙️ Step-by-Step Setup

1. **Clone the Repository**
   ```bash
   git clone https://github.com/AryaHaldankar/HandwrittenDigitRecognition.git
   cd HandwrittenDigitRecognition

2. **Create a virtual environment**
   ```bash
   python -m venv venv

3. **Activate the Virtual Environment**  
   ***- On Wndows***
   ```bash
   venv\Scripts\activate
   ```  
  ***- On Mac/Linux***
  ```bash
  source venv/bin/activate
  ```
4. **Install Project Dependencies**
   ```bash
   pip install -r requirements.txt
   
5. **Add the `data/` Folder**

   Download the `data` folder from the provided link [Drive Link](https://drive.google.com/drive/folders/1O_xsb7ZFBCjrQVCkKu9fYOze12fGPXMB?usp=sharing).

   Place the entire `data/` folder inside the root of the project directory — the same directory where your scripts and `requirements.txt` are located.
6. **Run Script**
   ```bash
   python3 DigitRecognition.py
