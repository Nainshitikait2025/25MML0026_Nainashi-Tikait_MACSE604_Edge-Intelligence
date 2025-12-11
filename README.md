README.md
# Text Data Project – NLP with Project Gutenberg (Romeo & Juliet)

## Dataset
For this project, I used a free public-domain dataset from **Project Gutenberg**.  
I downloaded the HTML version of the book **“Romeo and Juliet”** and renamed it to:

**romeo_and_juliet.html**

This file serves as the raw text corpus for scraping and NLP tasks.

---

##  Project Workflow

### 1️ Load HTML Dataset
- Opened the HTML file in Python  
- Parsed it using **BeautifulSoup**  
- Extracted raw text and stored it in the variable `text`

### 2️ Text Extraction (Scraping)
- Removed HTML tags  
- Cleaned the content  
- Printed the first 500–1000 characters to verify extraction  
- Saved a sample as `text_sample.txt`

### 3️ NLP Pipeline (Using NLTK)
I performed basic Natural Language Processing tasks:
- **Sentence Tokenization**  
- **Word Tokenization**  
- **POS (Part-of-Speech) Tagging**

These show how raw text can be processed and analyzed.

---

## Files Included in This Repository

| File Name | Description |
|----------|-------------|
| **text_project.ipynb** | Jupyter Notebook containing scraping + NLP pipeline |
| **romeo_and_juliet.html** | Original HTML dataset downloaded from Project Gutenberg |
| **text_sample.txt** | First 1000 characters extracted from the HTML (dataset sample) |
| **error_explanation.docx** | Error explanation (Unicode path error + fix) |
| **README.md** | Project description file |

---

## 📌 Tools & Libraries Used
- Python  
- BeautifulSoup (for scraping)  
- NLTK (for tokenization & POS tagging)  
- Jupyter Notebook  

---

##  How to Run This Project

1. Download all repository files  
2. Install dependencies:
3. Open `text_project.ipynb`  
4. Run each cell in order  
5. Ensure the HTML file (`romeo_and_juliet.html`) is in the same directory  

---

##  Notes
- The dataset is **public domain** (legal to use).  
- The text was extracted using HTML scraping, not a pre-cleaned dataset.  
- The project demonstrates understanding of corpus creation + NLP preprocessing.

---

##  Project By
**Nainshi Tikait**  
M.Tech AIML Student  


