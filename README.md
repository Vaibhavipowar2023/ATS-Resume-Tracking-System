

# ATS Resume Tracking System

## 📌 Introduction

The ATS Resume Tracking System is a Streamlit-based application designed to help job seekers optimize their resumes to pass through Applicant Tracking Systems (ATS). The system analyzes resumes against job descriptions and provides suggestions for improvement.

## ✨ Features

✅ Upload and analyze resume PDFs
✅ Convert PDFs to images for better processing
✅ Leverage Google Generative AI for resume enhancement
✅ Generate ATS-optimized resumes
✅ Download the optimized resume in a professional forma

## 🛠️ Installation

To get started, you'll need to install the required dependencies. You can do this by running the following commands:

```python
!pip install streamlit google-generativeai PyPDF2 pdf2image fpdf pyngrok pymupdf
```

Additionally, you need to install `poppler-utils` for PDF processing:

```bash
!apt-get install -y poppler-utils
```

## 🚀 Usage

1. **Run the Application:**
   ```bash
   streamlit run app.py
   ```
   The application will be accessible at the URL provided by `ngrok`.

2. **Upload Resume:**
   - Upload your resume in PDF format.

3. **Enter Job Description:**
   - Provide the job description you want your resume to be optimized for.

4. **Generate Optimized Resume:**
   - Click on "Generate ATS Optimized Resume" to get a resume optimized for ATS.


## 🤝 Contributing

Contributions are welcome! Please open an issue or submit a pull request.


---
