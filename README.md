# 💵 Fake Currency Detection Using Deep Learning

A deep learning project that detects counterfeit currency notes using Convolutional Neural Networks (CNNs). This model classifies currency note images into two categories — **Real** or **Fake** — based on visual features.

---

## 🚀 Project Overview

Currency counterfeiting is a serious global issue, causing significant financial losses. This project leverages the power of deep learning to provide an **automated image classification system** for identifying fake currency notes with high accuracy.



## 🧠 Key Features

- CNN-based binary image classifier
- Trained on real-world images of currency
- High accuracy on test data
- Easily extendable to other denominations and countries
- Ready for integration into real-time systems or mobile apps


## 🗂️ Project Structure

    Fake_Curreny_Detection/
    ├── Datasets/
    │ └── currency_dataset/
    │ ├── fake/
    │ └── real/
    ├── FakeCurrencyDetection.ipynb
    └── README.md


## 🖼️ Dataset

The dataset consists of two categories of Indian currency note images:

- `real/` – Genuine currency notes
- `fake/` – Counterfeit currency notes

Images are preprocessed using:
- Resizing to uniform dimensions
- Normalization
- Data augmentation for model generalization


## 🔧 Technologies Used

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| TensorFlow / Keras | Deep learning framework |
| OpenCV | Image preprocessing |
| NumPy, Pandas | Data handling |
| Matplotlib, Seaborn | Data visualization |
| Jupyter Notebook | Experimentation and visualization |



## 🏗️ Model Architecture

The CNN model includes:

- Multiple `Conv2D` and `MaxPooling2D` layers
- `Dropout` layers to prevent overfitting
- Flatten and fully connected `Dense` layers
- `Sigmoid` output for binary classification

The model is trained using:

- **Loss Function:** Binary Crossentropy  
- **Optimizer:** Adam  
- **Metrics:** Accuracy, Precision, Recall, F1 Score


## ▶️ How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Murugavl/Fake_Curreny_Detection.git
   cd Fake_Curreny_Detection
2. **Install Dependencies**

    ```bash
    pip install -r requirements.txt
3. **Launch the Notebook**

    ````bash
    jupyter notebook FakeCurrencyDetection.ipynb
4. **Train and Test the Model**

    * Follow the notebook steps

    * Evaluate results using plots and predictions


## 📄 License

This project is open source and available under the MIT License.