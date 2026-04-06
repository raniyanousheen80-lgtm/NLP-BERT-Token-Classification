# NLP BERT Token Classification (POS Tagging & Chunking)

## 🚀 Project Overview
This project demonstrates how to fine-tune a transformer model (BERT/DistilBERT) for token classification tasks such as Part-of-Speech (POS) Tagging and Chunking (Named Entity Recognition).

The model is trained on a labeled dataset to identify and classify tokens into meaningful categories like person names, locations, and organizations.

---

## 🎯 Objectives
- Understand token classification using transformer models  
- Perform POS tagging and chunking  
- Handle tokenization and label alignment  
- Evaluate model using sequence-based metrics  

---

## 🧠 Model Used
- DistilBERT (distilbert-base-cased)
- Fine-tuned using Hugging Face Transformers  

---

## 📊 Dataset
- WikiANN Dataset (English)
- Contains labeled tokens for Named Entity Recognition (NER)

---

## ⚙️ Tech Stack
- Python  
- Hugging Face Transformers  
- Datasets Library  
- SeqEval (for evaluation)  

---

## 🔄 Workflow
Raw Data → Tokenization → Label Alignment → Model Training → Evaluation → Inference  

---

## 🧩 Tasks Performed

### ✅ Data Preprocessing
- Tokenized input text using BERT tokenizer  
- Handled subword tokens  
- Aligned labels using -100 for ignored tokens  

### ✅ Model Training
- Fine-tuned DistilBERT for token classification  
- Used Trainer API for training  

### ✅ Evaluation
- Metrics used:
  - Precision  
  - Recall  
  - F1 Score  

### ✅ Inference
- Tested model on custom sentences  
- Successfully identified entities like Person, Organization, Location  

---

## 📈 Results
- The model achieved good performance with balanced precision and recall  
- Demonstrates effective learning for token classification tasks  

---

## 🔍 Example

**Input:**
