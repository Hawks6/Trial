# RFP Document Processing 

This project automates the extraction and structuring of key information based on the provided fields in the assignment from RFP (Request for Proposal) documents using the Gemini GenAI large language model. The script supports both **PDF** and **HTML** file formats.

## Features:
- **Automated Text Extraction**: Extracts text content from uploaded PDF or HTML files.
- **Structured Output**: Processes extracted text using Gemini GenAI and outputs the data in a well-defined JSON structure.
- **Pre-Configured API Key**: Includes a pre-configured API key for seamless execution.

---

## Instructions for Use

### 1. Setup in Google Colab
1. Open the provided `.ipynb` file in **Google Colab**.
2. Ensure an internet connection is available.

### 2. Install Dependencies
- The first cell in the notebook contains all the required pip installation commands.
- Run the first cell to install dependencies, including:
  - `pdfplumber` for PDF text extraction.
  - `beautifulsoup4` for parsing HTML files.
  - Other necessary libraries for interaction with Gemini GenAI.

### 3. Upload Your RFP File
- Use the file upload option in Google Colab to upload your **PDF** or **HTML** file.
- Copy the path of the uploaded file for use in later steps.

### 4. Execute the Notebook
- After uploading the file:
  - Paste the file path when prompted after running the last cell.
  - The script will process the file and return the structured output in JSON format.

---

## Key Notes
- **Gemini GenAI Integration**: The notebook uses the Gemini GenAI LLM to analyze and structure the RFP document data.
- **API Key Included**: A personal API key is already included in the notebook for testing and evaluation. No additional configuration is needed.
- **JSON Output**: The final output will be displayed in JSON format, with all required fields structured as specified.

---

## Requirements
- A Google Colab account.
- A valid RFP file in either **PDF** or **HTML** format.

---
