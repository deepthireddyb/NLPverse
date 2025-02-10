# NLPverse

Project Title: Comparative Analysis of Word2Vec and TF-IDF for Document Retrieval

Project Description:
This project explores and compares two prominent techniques for document retrieval and word similarity: Word2Vec and TF-IDF.  Utilizing the Reuters corpus, the project demonstrates how each method identifies semantically similar words and retrieves relevant documents. Word2Vec, a word embedding model, captures contextual relationships between words, while TF-IDF measures word importance within a document relative to a collection. The project aims to highlight the strengths and weaknesses of each approach through practical implementation and visualization of results.  Key aspects include model training (CBOW and Skip-gram variants for Word2Vec), similarity calculations, PCA visualization of word embeddings, and document retrieval based on TF-IDF scores. The comparative analysis offers insights into the suitability of each method for various information retrieval tasks.

**Understanding the Methods:**
TF-IDF (Term Frequency-Inverse Document Frequency):
It is a statistical method that represents words based on their frequency in a document relative to a collection of documents (corpus). Whereas tt does not capture semantic meaning, only numerical weights.

Word2Vec:
A neural network-based model that represents words as dense vectors in a high-dimensional space. It captures semantic similarity, hence words with similar meanings have closer vector representations.

**Evolution of Word Vectors -**
![image](https://github.com/user-attachments/assets/3c38fd35-25d0-4bba-a089-a07a9ff45100)

**Usage of both methods -**
Use TF-IDF When:
✅ You need simple and interpretable word weighting - TF-IDF assigns weights based on frequency, making it easy to understand why certain words are considered important. 
✅ Exact keyword matching is important - Best for applications where users expect exact matches (e.g., legal documents, technical searches).
 Example Use Cases:
Search engines for structured data (e.g., documentation, academic papers).
Spam filtering (flagging specific words in emails).
Keyword-based text categorization.
Use Word2Vec When:
✅ You need semantic understanding of words - Captures word relationships (e.g., "king" and "queen" are close in vector space)
✅ Your application requires generalization beyond exact words- Helps when users input synonyms or misspellings, as it retrieves semantically similar documents.
🔹 Example Use Cases:
Chatbots and virtual assistants (understanding user queries).
Document clustering and topic modeling.
Recommendation systems (e.g., suggesting similar articles based on content).

![image](https://github.com/user-attachments/assets/4461834f-ef60-4fc2-a75c-bcc5879a15a6)
