# CNN for Chest X-Ray Classification (COVID-19, Pneumonia, Normal)
This repository contains a case study on the application of Convolutional Neural Networks (CNNs) for classifying medical images. The model is trained to distinguish between chest X-rays of patients with COVID-19, Pneumonia, and healthy (Normal) individuals.

Note on Collaboration: This was a group project completed as part of the Machine Learning course (CS7052) at London Metropolitan University. This repository contains my specific contributions to the project, including the code for data processing, model development, and performance analysis, as detailed in the accompanying Jupyter Notebook. My analysis and commentary are attributed to "Jorge V. Perez" in the final report.

📄 [Read the Full Case Study Report (PDF)](Application_of_CNN_in_Medical_Image_Classification.pdf)


(A placeholder for a visual showing sample X-ray images from the dataset. You can generate this from the notebook.)

📜 Project Overview
The goal of this project was to build and evaluate a deep learning model capable of assisting in medical diagnosis by automatically classifying chest X-ray images. We utilized a custom-built CNN architecture to learn distinguishing features from the image data.

My key contributions, demonstrated in the CourseWork.ipynb notebook, include:

- Data Augmentation: Implemented ImageDataGenerator with various transformations (shear, zoom, rotation, flips) to expand the training dataset and improve model generalization.

- Model Architecture: Designed a sequential CNN model using TensorFlow/Keras with multiple convolutional, max-pooling, and dense layers, incorporating dropout for regularization.

- Training & Evaluation: Trained the model for 20 epochs with EarlyStopping and ModelCheckpoint callbacks.

- Performance Analysis: Evaluated the model's performance by plotting accuracy/loss curves and generating a confusion matrix to analyze its classification effectiveness.

🛠️ Technologies & Libraries
- Python 3.9

- TensorFlow & Keras: For building, training, and evaluating the CNN model.

- KaggleHub: For downloading the dataset.

- Scikit-learn: For generating and displaying the confusion matrix.

- NumPy: For numerical operations.

- Matplotlib: For data visualization.

- Jupyter Notebook: For interactive development and analysis.

⚙️ Setup and Usage
To replicate this project, follow the steps below:

1. Clone the Repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

2. Set Up a Virtual Environment:

```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install Dependencies: All required libraries are listed in the requirements.txt file.

```bash
pip install -r requirements.txt
```

4. Run the Notebook:
Launch Jupyter and open CourseWork.ipynb to see the complete workflow, from data loading to model evaluation.

jupyter notebook CourseWork.ipynb

🗂️ Repository Structure
- 23038621_Case_Study_Report_24.pdf: The complete case study report.

- CourseWork.ipynb: The Jupyter Notebook containing my code and analysis.

- requirements.txt: A list of all necessary Python dependencies.

- .gitignore: Specifies files and directories to be ignored by Git.
