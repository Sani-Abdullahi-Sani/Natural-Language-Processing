# Hausa Corpus #
This repository contains the Hausa Corpus, a collection of text data sourced from various platforms, blogs, and scanned literature to facilitate language research and machine learning applications. The data covers a wide range of topics, including business, psychology, healthcare, religion, and more. Below is a detailed explanation of how the data was collected and processed.

## Data Sources
### 1. Hausa Global Media
We collaborated with the Hausa Global Media company, a blogging platform, to obtain a rich dataset that includes both short and long blogs, as well as books authored by them. The topics covered in this dataset span across:

- Business
- Psychology
- Healthcare
- Education
- Religion
- Self-Awareness
- Technology
- Politics
 As a token of appreciation for their cooperation, we provided an incentive to the company for sharing this data.

### 2. Hausa Novel Store
Content was scraped from the website HausaNovel.ng, an online store dedicated to Hausa novels. The dataset focuses primarily on topics such as:

- Romance
- Entertainment
- Healthcare

### 3. Scanned Literature
We included scanned copies of classic Hausa literature such as:

- Magana Jari Ce
- Ruwan Bagaja
- PDF versions of other Hausa texts

To extract the text from the scanned books, we utilized Tesseract OCR with Python. 

## Data Preprocessing
We undertook several preprocessing steps to ensure the quality and consistency of the dataset:

- Whitespace Removal: Removed extra whitespaces from the text.
- Text Cleaning: Trimmed leading and trailing whitespace.
- Sentence Splitting: Split the text into sentences using sentence-ending punctuation (e.g., periods, exclamation marks, and question marks).
- Additionally, we removed timestamps and other metadata such as date and time, for example, '10/12/2022', from the scraped data to maintain data uniformity.

## Acknowledgments
We would like to thank Hausa Global Media and HausaNovel.ng for providing invaluable data for this project. This corpus will play a significant role in improving natural language processing (NLP) models for the Hausa language.

Feel free to explore the notebooks for details on data collection, cleaning, and extraction:

- Web Scraping: [NLP_Project__Data_Web_Scraping.ipynb](./NLP_Project__Data_Web_Scraping.ipynb)
- Data Preprocessing: [NLP_Project_2024_Data_Collection,_Preprocessing,_and_Cleaning.ipynb](./NLP_Project_2024_Data_Collection,_Preprocessing,_and_Cleaning.ipynb)
- Text Extraction from Scanned Books: [NLP_Project__Data_Extraction.ipynb](./NLP_Project__Data_Extraction.ipynb)

