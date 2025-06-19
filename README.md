# 🏥 Project: Medical Data Extraction

This project focuses on extracting and organizing medical-related data from unstructured sources using Python. The aim is to demonstrate the power of Natural Language Processing (NLP) and data parsing in transforming raw text data into structured, analyzable formats.

---

## 📌 Objective

To automate the extraction of relevant medical information such as:
- Patient name
- Age
- Gender
- Diagnosis
- Medications
- Dosage instructions

from prescription-style or clinical text documents using regular expressions and NLP techniques.

---

## 🛠️ Tools & Technologies

- **Python**
- **Regular Expressions (re)**
- **Text Parsing**
- **Jupyter Notebook**
- **Pandas**


## 📁 Project Structure
Project-Medical-Data-Extraction/
│
├── medical_data_extraction.ipynb     # Main notebook containing the logic
├── sample_data.txt                   # Sample input text file (prescriptions)
├── output.csv                        # Extracted structured data
└── README.md                         # Project documentation

## 🔍 Features

- 📄 Reads and parses unstructured clinical text
- 🧠 Extracts key-value data using regular expressions (regex)
- 📊 Stores structured output in a CSV file
- 🔧 Easily extendable for various medical data fields

## 🚀 How to Run

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Utkrisht2026/Project-Medical-Data-Extraction.git
   cd Project-Medical-Data-Extraction

A tool for extracting structured medical data from unstructured clinical notes and prescriptions.

## Features

- 📥 Import unstructured medical text data
- 🧹 Extract key patient information (Name, Age, Gender)
- 💊 Identify medications and dosages
- 📅 Capture visit dates
- 💾 Export to structured CSV format

pip install -r requirements.txt

jupyter notebook medical_data_extraction.ipynb

# Medical Data Extraction Notebook

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)
![Pandas](https://img.shields.io/badge/Pandas-1.3%2B-brightgreen)

A Jupyter notebook for extracting structured medical data from unstructured clinical text.

## Usage

1. Open `prescription_parser.ipynb` `pd_parser.ipynb`  in Jupyter Notebook
2. Run all cells sequentially
3. Input your medical text when prompted
4. Check `cv_concepts.ipynb` for structured results

## Sample Output

| Patient Name | Age | Gender | Diagnosis     | Medications       | Dosage      |
|--------------|-----|--------|---------------|-------------------|-------------|
| John Doe     | 45  | Male   | Hypertension  | Atenolol 50mg     | Once daily  |
| Jane Smith   | 32  | Female | Diabetes      | Metformin 500mg   | Twice daily |

## Future Enhancements

| Feature | Description |
|---------|-------------|
| 🖨️ OCR Integration | Support for scanned prescriptions using Tesseract or other OCR tools |
| 🤖 NLP Models | Advanced extraction using spaCy, BERT, or clinical NLP models |
| 🌐 Web Application | Flask/Django interface for clinical staff usage |
| 🔍 Multi-language | Support for non-English medical documents |
| 🧠 ML Improvements | Better handling of varied prescription formats |

## Installation

# Navigate to project directory
cd medical-data-extraction

# Create virtual environment (recommended)
python -m venv venv
source venv/bin/activate  # On Windows use `venv\Scripts\activate`

# Install dependencies
pip install -r requirements.txt

# Launch Jupyter Notebook
jupyter notebook

#Requirements
Python 3.8+
Jupyter Notebook
pandas
regex
python-dateutil

   
## 👨‍💻 Author

**Utkrisht Jalan**  
Aspiring Data Analyst skilled in SQL, Python, Power BI, and Excel.  
[GitHub Profile](https://github.com/Utkrisht2026)

---

## ⭐ If you found this useful, don't forget to star this repo!

