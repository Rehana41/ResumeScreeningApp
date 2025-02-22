# Resume Screening App

## 📌 Overview
The **Resume Screening App** is a machine learning-based application that automates the process of shortlisting resumes based on predefined categories. It leverages **Natural Language Processing (NLP)** and **TF-IDF Vectorization** to analyze and classify resumes into relevant job roles.

## 🚀 Features
- **Automated Resume Screening**: Extracts and categorizes resume content.
- **Text Processing with NLP**: Uses **TF-IDF Vectorization** to transform text into numerical data.
- **Machine Learning Model**: Implements **Support Vector Machine (SVM)** for classification.
- **User Interface**: Simple web-based UI for uploading and reviewing resumes.
- **Multi-Format Support**: Accepts **PDF, DOCX, and TXT** files.

## 🛠️ Technologies Used
- **Python** (Pandas, NumPy, Scikit-learn)
- **NLP** (TF-IDF Vectorization, Regex-based text cleaning)
- **Streamlit** (for Web UI)
- **Machine Learning (Support Vector Machine - SVM)**
- **File Processing** (PyPDF2, python-docx)

## 🔧 Installation Guide



### Steps to Set Up Locally:
```bash
1. [Clone the repository](https://github.com/Rehana41/ResumeScreeningApp)

2. [Download cfl.pkl file here](https://www.kaggle.com/datasets/rehanahassan/clf-pkl)

3. Install dependencies
   pip install -r requirements.txt

4. Run the application
   streamlit run app.py
```


## 🖼️ Workflow
1. **Upload Resume**: User uploads a resume in PDF, DOCX, or TXT format.
2. **Text Extraction**: Extracts raw text using PyPDF2 or python-docx.
3. **Text Cleaning**: Removes unwanted characters and formats the text.
4. **Feature Engineering**: Converts text into numerical form using **TF-IDF Vectorization**.
5. **Prediction**: SVM model classifies the resume into a job category.
6. **Results Display**: Predicted job category is displayed in the UI.

## 📊 Model Performance
- **Accuracy Achieved**: 97% using **Support Vector Machine (SVM)**.
- **Feature Extraction**: TF-IDF for text transformation.
- **Encoding**: LabelEncoder for categorical target variables.


