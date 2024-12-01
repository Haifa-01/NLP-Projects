
# README: Lab 3 - Regex and Arabic NLP Embedding

## Lab Overview

This project, **"Lab 3: Regex and Arabic NLP Embedding,"** explores key techniques in natural language processing (NLP), focusing on extracting structured information from text using Regex and implementing various word embedding techniques for semantic analysis. 

---

## Learning Objectives

By completing this lab, you will:
1. Extract structured information (e.g., products, quantities, and prices) from text using Regex.
2. Represent text data numerically using advanced word embedding techniques.
3. Visualize word embeddings using t-SNE to analyze their semantic relationships.

---

## Steps in the Lab

### 1. **Rule-Based NLP and Regex**
   - Use Regex to process text data.
   - Extract information such as product names, quantities, and unit prices.
   - Generate a structured output table summarizing the extracted details.

   **Example Input**:  
   `"I bought three Samsung smartphones at $150 each, four kilos of fresh bananas for $1.2 a kilogram, and one Hamburger for $4.5."`

   **Example Output**:  
   A table displaying:  
   - Product  
   - Quantity  
   - Unit Price  
   - Total Price  

### 2. **Word Embedding Techniques**
   - Explore the following methods:
     1. One-Hot Encoding
     2. Bag of Words (BoW)
     3. TF-IDF
     4. Word2Vec (Skip-Gram, CBOW)
     5. FastText
   - Compare the performance of these methods on the provided dataset.

### 3. **Visualization**
   - Use t-SNE to visualize high-dimensional embeddings and understand their clustering behavior.

---

## Tools and Technologies

- **Programming Language:** Python
- **Libraries Used:** 
  - numpy, pandas
  - gensim, sklearn, matplotlib
  - nltk
- **Development Environment:** Google Colab

---

## Results

- **Part 1:** A working pipeline to extract structured data from text using Regex.
- **Part 2:** Word embedding models that capture semantic relationships, visualized through t-SNE.

---
