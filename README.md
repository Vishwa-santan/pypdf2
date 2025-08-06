# PDF Text Extraction and NLP with spaCy

This project extracts text from a PDF file, performs **Named Entity Recognition (NER)** and **Dependency Parsing** using spaCy, and exports the extracted entities into a structured **JSON file**.

# 📂 Features

Feature	Description

📄 PDF Text Extraction	Reads and extracts text from all pages of a PDF using PyPDF2.

🧠 Named Entity Recognition (NER)	Detects and classifies real-world entities (like names, locations, orgs).

🧩 Dependency Parsing & POS Tagging	Analyzes the grammatical structure and part-of-speech of each token.

💾 JSON Export	Saves named entities as structured JSON data.

✅ Page Count Detection	Displays total number of pages in the input PDF.

🔠 Full Document Parsing	Processes the entire document text for more complete NLP results.

📊 Console Output	Outputs sample named entities and POS tags directly to the terminal.

🛠️ Customizable File Paths	Easy to update input/output paths based on user environment.

📦 Modular Code	Separated into logical steps: read, process, export.

🧪 spaCy Medium Model (en_core_web_md)	Uses a more powerful NLP model for better accuracy in NER/POS tagging.



 
 # Project Structure

├── extract_nlp_pdf.py 

├── output.json 

├── NIST-Cybersecurity-Framework.pdf 

├── README.md 


# What It Does

Loads a PDF file using PyPDF2

Extracts text from all pages

Processes the text using spaCy for:

Named Entity Recognition (NER)

Part-of-Speech (POS) tagging

Saves named entities to output.json

Prints a sample named entity to the console.


# 🚀 How to Run
Place your PDF (e.g., NIST-Cybersecurity-Framework-Policy-Template-Guide.pdf) in your working directory.

Update the file_path in the script if needed.

Run the Python script:


python extract_nlp_pdf.py


# 🧪 Sample Output (Console)

Total no.of pages in pdf file: 12
Elon Musk PERSON
SpaceX ORG
California GPE
...

Sample Named Entity: {'text': 'California', 'label': 'GPE'}
Sample POS Tag: {'text': 'California', 'label': 'GPE'}

# 📜 License

This project is for educational and research purposes.
Policy content from the NIST framework should follow their usage guidelines.



