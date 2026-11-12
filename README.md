# Handwritten Digit Recognition using SVM

## 📌 Project Overview

This project demonstrates handwritten digit recognition using Machine Learning. A Support Vector Machine (SVM) classifier is trained to identify handwritten digits from 0 to 9 using 8×8 pixel images.

## 🎯 Project Objectives

- Understand how image data is represented as numerical pixel values.
- Explore and analyze handwritten digit data.
- Visualize digit images using Matplotlib.
- Train a Support Vector Machine classifier.
- Evaluate model performance using accuracy.
- Compare different SVM configurations.
- Predict handwritten digits using the trained model.

## 📊 Dataset Information

The project uses a handwritten digits dataset containing 1,797 images.

- Image dimensions: 8 × 8 pixels
- Number of features: 64 pixel values
- Pixel values: 0–16
- Target variable: Digit label (0–9)

**Dataset file:** `data/digits.csv`

**Note:** The original dataset file is not included in this repository. It is required to run the notebook.

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## 🤖 Machine Learning Algorithm

**Support Vector Machine (SVM)**

SVM is a supervised Machine Learning algorithm used for classification. It identifies decision boundaries to classify handwritten digit images into ten categories (0–9).

## ⚙️ Project Workflow

1. Import the required Python libraries.
2. Load the handwritten digit dataset.
3. Visualize individual digit images.
4. Separate features and target variables.
5. Split the dataset into training and testing sets (70:30).
6. Train an SVM classifier using a linear kernel.
7. Evaluate the model using accuracy score.
8. Predict an individual handwritten digit.
9. Compare different SVM configurations using different kernels and parameter settings.

## 📁 Project Structure

```text
Handwritten-Digit-Recognition-SVM/
│
├── data/
│   └── digits.csv
│
├── 02_handwritten_digit_recognition_svm.ipynb
│
├── README.md
│
└── requirements.txt
```

## 🚀 How to Run the Project

**Step 1: Clone the repository**

```bash
git clone https://github.com/thrishnalakshmi201-lab/Handwritten-Digit-Recognition-SVM.git
```

**Step 2: Navigate to the project folder**

```bash
cd Handwritten-Digit-Recognition-SVM
```

**Step 3: Install the required libraries**

```bash
pip install -r requirements.txt
```

**Step 4: Add the dataset**

Place the original `digits.csv` file inside the `data` folder.

**Step 5: Run the Jupyter Notebook**

```bash
jupyter notebook
```

Open `02_handwritten_digit_recognition_svm.ipynb` and run the cells.

## 📈 Model Evaluation

The model performance is evaluated using the accuracy score on the test dataset.

The project also compares different SVM configurations, including linear and RBF kernels, to understand how model settings affect classification accuracy.

## 📚 Learning Outcomes

- Understanding image data as numerical pixel values.
- Learning multi-class classification.
- Implementing an SVM classifier.
- Visualizing handwritten digit images.
- Evaluating Machine Learning models.
- Comparing different model configurations.

## 👩‍💻 Author

**Thrishnalakshmi MV**

Machine Learning Project | Python | Scikit-learn

---

⭐ If you find this project useful, feel free to star this repository!
