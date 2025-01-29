# PDF-Uploader-and-Summarizer
📄 Overview
This project is a Streamlit-based web application that allows users to upload multiple PDF files and extract structured text summaries from them. The extracted information includes diagnosis, symptoms, medical history, and treatment details, which can be downloaded as a CSV file.


🚀 Features

✅ Upload multiple PDF medical records.

✅ Extract key information using OCR (Tesseract) and regular expressions.

✅ Summarize extracted text into structured medical insights.

✅ Display results in a table format.

✅ Download the extracted data as a CSV file.

🛠 Technologies Used

Programming Language: Python

Libraries: Streamlit, pandas, OpenCV, NumPy, Pytesseract, pdf2image, re

Tools: Jupyter Notebook, Visual Studio Code

📂 Project Structure

pdf-uploader-summarizer/

│


├── main.py                  # Streamlit frontend for file upload & display  

├── backend.py               # PDF processing and text extraction logic  

├── requirements.txt         # Required Python libraries  

├── README.md                # Documentation  

├── sample_data/             # Folder for test PDFs  

│   ├── sample1.pdf  

│   ├── sample2.pdf  

└── output/                  # Extracted results (CSV files)  

🛠 Setup Instructions

1️⃣ Install Dependencies

Ensure you have Python 3.8+ installed. Then, run:

pip install -r requirements.txt

2️⃣ Run the Application

streamlit run pdf_to_excel.py

3️⃣ Upload PDFs & Extract Information

Upload medical PDF reports via the web UI.

Extracted details will be shown in a table.

Download the summarized data as a CSV file.
