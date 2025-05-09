# BERT Representational Distance of Homonyms by Word Class

An analysis of representational distance between noun-noun homonyms, noun-verb homonyms, and unambiguous words using BERT embeddings. 
This project replicates and extends the methodology from **Mirman et al. (2010)** to assess semantic similarity based on contextual embeddings. 

## Setup Instructions:

## 1. Clone and Navigate to the Repository

git clone https://github.com/419tom/homonyms.git 

cd homonyms 

## 2. Create Virtual Environment
conda env create -f homonyms.yml 

conda activate homonyms 

## OR

## 2. Run Requirements
pip install -r requirements.txt


## 3. Install SpaCy Model (if still required)
python -m spacy download en_core_web_sm

## 4. Run script for Cosine Similarities
python cosine_similarities.py

## 5. Run Script for Visual Analysis (Barplot)
python similarity_analysis.py







