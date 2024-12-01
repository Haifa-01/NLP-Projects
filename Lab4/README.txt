
# README: Data-Centric vs Model-Centric Approaches

## Lab Overview

This project, **"Lab: Data-Centric vs Model-Centric Approaches,"** introduces the concepts of data-centric and model-centric strategies in machine learning. Through hands-on experiments, it demonstrates how improving data quality and preprocessing can often outperform purely enhancing models through hyperparameter tuning or complex architectures.

---

## Learning Objectives

By completing this lab, you will:
1. Build a text classifier for product reviews (focused on the magazine category).
2. Explore the limitations of model-centric approaches (e.g., model selection and hyperparameter tuning).
3. Implement data-centric techniques to improve the dataset quality, leading to better model performance.

---

## Steps in the Lab

### 1. **Understanding the Problem**
   - Build a classifier for product reviews, using examples such as:
     - **Positive Review:**  
       *"Excellent! I look forward to every issue. I had no idea just how much I didn't know. The letters from the subscribers are educational, too."*  
       **Label:** ⭐️⭐️⭐️⭐️⭐️ (good)

     - **Negative Review:**  
       *"My son waited and waited, it took the 6 weeks to get delivered that they said it would but when it got here he was so disappointed, it only took him a few minutes to read it."*  
       **Label:** ⭐️ (bad)

### 2. **Model-Centric Approach**
   - Train various models and fine-tune hyperparameters to maximize performance.
   - Explore the limits of accuracy improvements achievable through model tweaking.

### 3. **Data-Centric Approach**
   - Evaluate the quality of the dataset and identify issues such as noisy labels, missing data, or imbalanced classes.
   - Implement techniques to improve data quality:
     - Data cleaning
     - Re-labeling
     - Balancing the dataset
   - Measure the performance improvements achieved by better data preprocessing.

---

## Tools and Technologies

- **Programming Language:** Python
- **Libraries Used:** 
  - pandas, numpy
  - sklearn
  - matplotlib, seaborn
  - nltk (for text processing)
- **Development Environment:** Google Colab

---

## Results

- **Model-Centric Approach:** Demonstrates the limitations of focusing solely on model architecture and hyperparameter optimization.
- **Data-Centric Approach:** Highlights how cleaning and improving the dataset can significantly enhance performance.

---
