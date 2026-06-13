# BasicSearchEngine
A simple academic project developed for the Modern Information Retrieval (MIR) course, featuring a basic search engine built to explore core information retrieval techniques.


### 1. The Dataset
The core data is provided in the repository. You do not need to crawl external sites, but the raw data requires significant preprocessing.
* **Path:** `release/top_3000_rated_books.rar`
* **Note:** Extract this file to your data directory before running the preprocessing scripts.

### 2. Installation
Ensure you have Python installed, then run:
```bash
pip install -r requirements.txt
```

### 3. Running the UI
We use **Streamlit** to provide an interactive search experience.
```bash
streamlit run UI/main.py
```
Once running, navigate to `http://localhost:8501/` in your browser.

