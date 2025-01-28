# Resume Classification (Rule-based Approach)

### Description:
This project focuses on classifying resumes into specific job designations using a rule-based approach. The system extracts key information, such as skills and experience, from resumes, and applies predefined rules for classification. We used **Logistic Regression** and **Naive Bayes** models for categorizing the resumes into various job roles. The project uses **SpaCy** for Named Entity Recognition (NER) and utilizes **predefined skill sets** to enhance classification accuracy. The text extraction from resumes is done using **PyPDF** and **python-docx**.

### Current Status:
- Developed an initial version using a rule-based classification system.
- **SpaCy** was used for **Named Entity Recognition (NER)** to extract skills, experience, and other relevant details from resumes.
- **Logistic Regression** and **Naive Bayes** models were used for classifying resumes into predefined job categories.
- The text from resumes was extracted using **PyPDF** (for PDF files) and **python-docx** (for DOCX files).
  
### Future Work:
- Automating the classification process with **Large Language Models (LLMs)** like **BERT** or **GPT**, which will enhance the flexibility and accuracy of the classification system.

### Technologies Used:
- **Python**
- **SpaCy (NER)**
- **scikit-learn (Logistic Regression, Naive Bayes)**
- **PyPDF (Text extraction from PDFs)**
- **python-docx (Text extraction from DOCX files)**
- **Shutil (To Move or Copy Files)**
- **Predefined Skill Set for Classification**
