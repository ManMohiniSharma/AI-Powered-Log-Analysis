# AI-Powered Log Analysis

An AI-powered system for analyzing large-scale system logs using Natural Language Processing (NLP) and transformer-based language models.

## Project Overview

This project focuses on preprocessing and analyzing system log data to extract meaningful security-related information. It uses NLP techniques and CyberBERT/SecBERT embeddings to represent log messages in a form suitable for intelligent log analysis and downstream security applications.

## Key Features

- Preprocessing of large-scale system log data
- Extraction of actions and security-relevant information from logs
- Mapping log information to Unified Cybersecurity Ontology (UCO) concepts
- Semantic sentence generation from log entries
- Cybersecurity-focused BERT (SecBERT) embeddings
- Hybrid vector representation of log information
- Storage of processed and enriched log data for further analysis

## Technologies Used

- Python
- Pandas
- NumPy
- PyTorch
- Hugging Face Transformers
- BERT / SecBERT
- Natural Language Processing (NLP)
- Google Colab
- Google Drive

## Dataset

The project uses the **BGL (Blue Gene/L) system log dataset**.

The raw dataset is not included in this repository. The notebook expects the dataset to be available in Google Drive.

Expected path:

```text
/content/drive/MyDrive/BGL/BGL.log
```

## How to Run

1. Open the notebook in Google Colab.
2. Make sure the BGL dataset is available in your Google Drive.
3. Mount Google Drive when prompted.
4. Install the required Python libraries if necessary.
5. Run the notebook cells sequentially.

## Project Workflow

```text
Raw System Logs
       ↓
Log Preprocessing
       ↓
Action / UCO Mapping
       ↓
Semantic Sentence Generation
       ↓
SecBERT Embeddings
       ↓
Hybrid Vector Representation
       ↓
Enriched Log Dataset
```

## Future Scope

- Automated anomaly detection
- Real-time log monitoring
- Intelligent security event classification
- Visualization dashboards
- Integration with security monitoring systems
- Advanced AI-based threat detection

## Author

**Man Mohini Sharma**
