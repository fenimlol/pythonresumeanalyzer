# 🚀 AI-Powered Resume Analyzer

## 📜 Overview
The **AI-Powered Resume Analyzer** is a cutting-edge Python tool designed to help job seekers optimize their resumes for **readability**, **ATS (Applicant Tracking System) compatibility**, and **job relevance**. By analyzing text extracted from PDF and DOCX files, this tool provides valuable insights to improve your resume’s effectiveness.

## ✨ Features
- 📄 **Resume Parsing** – Extracts text from **PDF** and **DOCX** files.
- 🔍 **Keyword Analysis** – Matches resume content with **job-related keywords**.
- 📊 **Readability Score** – Evaluates clarity using the **Flesch Reading Ease metric**.
- 📌 **Actionable Insights** – Identifies missing keywords and suggests improvements.
- 📝 **User-Friendly CLI** – Simple and interactive command-line interface.

## ⚡ Installation
### Prerequisites
Ensure you have **Python 3.7+** installed, then install the required dependencies:
```bash
pip install PyPDF2 python-docx nltk textstat
```

## 🎯 Usage
Run the script and follow the prompts:
```bash
python resume_analyzer.py
```
Provide the resume file path and enter job-related keywords when prompted.

### 📌 Example Output
```
Enter the resume file path (PDF or DOCX): resume.pdf
Enter job-related keywords (comma-separated): Python, Machine Learning, Data Science

📊 === Resume Analysis Results ===
✅ Readability Score: 62.5
✅ Found Keywords: Python, Data Science
❌ Missing Keywords: Machine Learning

💡 Suggestion: Consider simplifying your sentences for better readability.
```

## 🛠️ Future Enhancements
- 🌍 **Web-based version using Flask/Streamlit**
- 📈 **Machine Learning model for resume scoring**
- 📄 **Support for JSON/CSV reports**

## 🤝 Contributing
Want to improve this project? Follow these steps:
1. **Fork** the repository.
2. **Create** a new branch.
3. **Commit** your changes.
4. **Submit** a pull request.

## 👤 Author
**Joshua Daniel**  
📌 GitHub: [fenimlol](https://github.com/fenimlol)

## 📜 License
This project is released under the **MIT License**. Feel free to modify and distribute it.

