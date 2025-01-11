# Web Scraping and Headline Similarity Analysis

## Project Overview
This project involves web scraping live news data from the BBC News website and analyzing headlines using machine learning techniques. The goal is to extract structured data, clean it, and implement a TF-IDF-based model to identify similar headlines. The project demonstrates the integration of web scraping, data cleaning, and machine learning to deliver actionable insights.

---

## Key Features
- **Web** Scraping**: Extracts news titles, categories, timestamps, descriptions, and links using BeautifulSoup and Requests.
- **Data Cleaning**: Handles missing values, removes duplicates, and standardizes the dataset for consistency.
- **Text Similarity**:
  - TF-IDF Vectorization for transforming text data.
  - Cosine similarity to identify similar headlines based on keywords.
- **Data Export**: Cleaned datasets are saved as CSV files for further analysis.
- **Model Saving**: Saves the trained vectorizer, TF-IDF matrix, and dataset to a pickle file for reuse.

---

## Project Workflow
1. **Web Scraping**:
   - Data is extracted from the BBC News website, focusing on articles with categories, descriptions, and timestamps.
2. **Data Cleaning**:
   - Missing values are addressed.
   - Duplicate entries are removed.
   - Data is standardized for easier processing.
3. **Machine Learning**:
   - Headlines are vectorized using TF-IDF.
   - Cosine similarity is computed to find similar headlines based on user input.
4. **Model Saving**:
   - The TF-IDF vectorizer, matrix, and cleaned dataset are saved in a pickle file for easy reuse.
5. **Output**:
   - Similar headlines are displayed with their titles and links.

---

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone <repository-url>
Install the required libraries:
pip install -r requirements.txt

Run the main script:
python ml_news.py
