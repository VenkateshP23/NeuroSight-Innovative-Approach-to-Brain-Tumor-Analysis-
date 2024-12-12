# 🧠 NeuroSight: Innovative Approach to Brain Tumor Analysis
**A cutting-edge deep learning framework for brain tumor classification and diagnosis**

---

## 🚀 Overview
NeuroSight leverages state-of-the-art deep learning models to classify brain tumors with high precision, providing an innovative and efficient tool for medical image analysis. This framework supports the classification of brain tumors into four categories: **Pituitary**, **Glioma**, **Meningioma**, and **No Tumor**, empowering medical professionals with a reliable diagnostic assistant.

By utilizing pretrained models such as **InceptionV3**, **VGG16**, **ResNet101**, and **InceptionResNetV2**, NeuroSight excels at extracting meaningful features from MRI images to enhance diagnostic accuracy and streamline medical workflows.

---

## 🎯 Key Features
- **State-of-the-Art Models**: Integrates InceptionV3, VGG16, ResNet101, and InceptionResNetV2 for superior performance.
- **High Accuracy**: Rigorous evaluation to identify the best model for brain tumor classification.
- **Streamlined Workflow**: Easy-to-use notebook designed for seamless integration into research or clinical practice.
- **Comprehensive Dataset**: Classified MRI images of four tumor types for robust training and testing.

---

## 🧬 Dataset Structure
The dataset is organized into training and testing folders, with subfolders for each tumor type:

BrainTumor data/ ├── training/ │ ├── Pituitary/ │ ├── Glioma/ │ ├── Meningioma/ │ └── No Tumor/ └── testing/ ├── Pituitary/ ├── Glioma/ ├── Meningioma/ └── No Tumor/


> **Note:** Due to size constraints, the dataset is not included in this repository. Please refer to the [Usage Instructions](#usage-instructions) for dataset download and setup.

---

## ⚙️ How It Works
1. **Data Preprocessing**: Handles resizing, normalization, and augmentation for optimal model performance.
2. **Feature Extraction**: Pretrained models extract robust features from MRI images.
3. **Classification**: Models predict the tumor class with high accuracy.
4. **Evaluation**: Compares model performance to identify the most effective one for this task.

---

## 📖 Usage Instructions

### 1️⃣ Clone the Repository
```bash
git clone <this-repository>
cd NeuroSight```

### 2️⃣ Install Dependencies
**Install the required Python libraries from the requirements.txt file:**
```bash
pip install -r requirements.txt```

### 3️⃣ Add the Dataset
Place the dataset in the data/ directory with the structure outlined above.

### 4️⃣ Run the Notebook
Launch the Jupyter Notebook and run the Capstone_project.ipynb:
```bash
jupyter notebook Capstone_project.ipynb```

### 🌟 Future Enhancements
- **Adding** real-time tumor classification using a web-based interface.
- **Expanding** the dataset to include additional tumor types.
- **Integrating** explainability tools (e.g., Grad-CAM) to interpret predictions.

