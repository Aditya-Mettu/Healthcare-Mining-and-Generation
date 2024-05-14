# Healthcare-Mining-and-Generation

---

# Mining Healthcare Websites

## Project Overview
Our project focuses on leveraging advanced Natural Language Processing (NLP) and machine learning technologies to enhance the accessibility and precision of healthcare information from vast online databases. The system uses BioBERT for identifying key medical terms and employs the SympGraph to enrich user queries, utilizing Retrieval-Augmented Generation (RAG) method for effective document extraction.

## Key Technologies
- **BioBERT**: A domain-specific language model pre-trained on biomedical corpora.
- **SympGraph**: A graph-based method for linking medical terms based on their associations.
- **Retrieval-Augmented Generation (RAG)**: Integrates cosine similarity, BERT, and TF-IDF for extracting relevant documents.

## System Architecture
1. **Data Scraping**: Data is collected from various healthcare websites using Scrapy.
2. **Data Processing**: Utilizing BioBERT to process and extract relevant medical terms.
3. **Query Expansion**: Uses SympGraph to expand user queries with relevant terms.
4. **Document Retrieval and Response Generation**: Implements RAG and uses advanced models like GPT-2 and BART for generating responses.


## Usage
```python
# Example of using the system to query healthcare information
response = system.query("symptoms of diabetes")
print(response)
```

## Contributing
Interested in contributing? We welcome pull requests and issues from all developers.

## Contact
- Aditya Mettu - amettu3@asu.edu
