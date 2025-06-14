# 🤖 ArXiv Playwright Scripts

Automate your arXiv research paper hunt with Playwright + Python!  
This repo contains two scripts to help you either **download PDFs** or simply **extract PDF links** based on your search keyword.  

---

## 📂 Project Structure
```
📁 arxiv-playwright-scripts/
├── webscraper.py # 🧾 Downloads PDF files of search results
├── weblinks.py # 🔗 Extracts and prints PDF links
├── screen-capture (1).gif # 🎬 Demo of PDF link extractor
```

---

## ✨ Features

### 🔗 `weblinks.py`  
- Searches arXiv for a keyword  
- Extracts and prints all PDF links  
- 💡 Ideal if you just want to copy/paste or analyze links  

![Demo](demo.gif)

---

### 📥 `webscraper.py`  
- Searches arXiv for a keyword  
- Automatically downloads all PDF files to the `data/` folder  
- Perfect for bulk downloading papers 🧠📄

---

## 🚀 Getting Started

Install the dependencies:

```bash
pip install playwright
playwright install
```
Run either script:
```
python weblinks.py     # to print PDF links
python webscraper.py   # to download PDFs
```

---

## 📌 Notes
Make sure the `data/` folder exists before running `webscraper.py`.

You can edit the search keyword inside the script (`neural network` by default).

---

## 📚 Built With
🧪 Playwright for Python

🌐 ArXiv.org
