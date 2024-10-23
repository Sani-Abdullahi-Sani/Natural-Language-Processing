# Language Adaptive Fine-Tuning (LAFT) & NaijaSenti Hausa NLP
This repository contains the code and datasets used for Language Adaptive Fine-Tuning (LAFT) and downstream sentiment analysis on the Hausa NaijaSenti dataset. The goal of this project is to adapt pre-trained models to low-resource languages like Hausa and evaluate their performance in sentiment classification tasks.

### 📁 Repository Structure
- `codes/`: Jupyter notebooks for LAFT and downstream tasks.
- `Downstream Task/`: NaijaSenti Hausa dataset for the Downstream Task (Sentiment Analysis).
- `LAFT Corpus/`: Curated datasets for the LAFT


## 🛠️ Steps to Replicate the Experiment

### 1. Clone the Repository
```bash
git clone https://github.com/Sani-Abdullahi-Sani/Natural-Language-Processing.git
cd Natural-Language-Processing
```


### 2. Install Dependencies
Ensure you have Python 3.x installed. Then install the required dependencies via `pip`:

- All the required dependencies are in the Notebooks.


### 3. Download Pre-trained Models
- Download the pre-trained transformer models for LAFT:
```bash
>>> from transformers import AutoTokenizer, AutoModelForTokenClassification
>>> model = AutoModelForTokenClassification.from_pretrained("castorini/afriberta_small")
>>> tokenizer = AutoTokenizer.from_pretrained("castorini/afriberta_small")
>>> tokenizer.model_max_length = 512
```

### 4. Run Baseline Model
[Baseline Model Final Version Notebook](https://github.com/Sani-Abdullahi-Sani/Natural-Language-Processing/blob/main/Sentiment%20Analysis%20in%20African%20Languages%20Project/Code/Baseline%20Model%20Final%20Version.ipynb)


### 5. Run LAFT + Downstream
- Execute the fine-tuning process on the low-resource language dataset (Hausa):
  
[LAFT + Downstream Task Final Version Notebook](https://github.com/Sani-Abdullahi-Sani/Natural-Language-Processing/blob/main/Sentiment%20Analysis%20in%20African%20Languages%20Project/Code/LAFT%20%2B%20Downstream%20Task%20Final%20version.ipynb)

### 6. Contact
For questions or collaborations, please contact [saniabdullahirano@gmail.com].







