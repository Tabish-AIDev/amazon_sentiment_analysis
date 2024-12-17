# **Sentiment Analysis on Amazon Fine Food Reviews**

### **Project Overview**

This project applies **Natural Language Processing (NLP)** to analyze customer sentiments in the Amazon Fine Food Reviews dataset. The reviews are classified into three sentiment categories: **positive, neutral, and negative**. The project showcases a progression of models, starting from simpler approaches like Logistic Regression and advancing to more complex techniques, including deep learning.

---

### **Dataset**

- **Source**: [Amazon Fine Food Reviews on Kaggle](https://www.kaggle.com/datasets/snap/amazon-fine-food-reviews)
- **Size**: 550,000+ reviews
- **Features**:
    - `Text`: Review content
    - `Rating`: Numeric star ratings
    - Other metadata (user info, timestamps, etc.)

---

### **Approach**

The project is structured into key stages to ensure a progressive workflow:

1. **Data Preprocessing & EDA**
    - Cleaned and tokenized review text.
    - Handled missing data and outliers.
    - Explored the dataset to understand sentiment class imbalance.
2. **Feature Engineering**
    - Applied **TF-IDF Vectorization** to transform text data into numerical features.
    
3. **Modeling**  
    Models were built progressively to showcase scalability:
    - **Logistic Regression (Baseline)**
        - Addressed class imbalance using:
            - `class_weight='balanced'`
            - **SMOTE (Synthetic Minority Over-sampling Technique)**
    - **Planned Advanced Models**:
        - Random Forests
        - LSTMs (Deep Learning)
        - Transformer-based models (e.g., BERT)

---

### **Current Results**

|Model|Accuracy|Key Notes|
|---|---|---|
|Logistic Regression (Baseline)|86%|Imbalanced data|
|Logistic Regression + Class Weights|~77.75%|Balanced classes|
|Logistic Regression + SMOTE|~78%|Balanced synthetic samples|

---

### **Skills Demonstrated**

- **Data Preprocessing**: NLP techniques (cleaning, tokenization, TF-IDF)
- **Model Development**: Logistic Regression, handling imbalance with **SMOTE**
- **Model Evaluation**: Accuracy, Confusion Matrices
- **Scalability**: Transitioning from simpler models to more advanced ones
- **Tools Used**: Scikit-learn, Pandas, NumPy, Jupyter Notebook

---

### **Next Steps**

- Build and evaluate **Random Forests** and **Gradient Boosting** models.
- Implement **LSTMs** and **Transformer-based models** for higher accuracy.
- Consider **Reinforcement Learning** for optimization.

---

### **About Me**

Aspiring AI engineer with hands-on experience in NLP projects, showcasing skills across machine learning and deep learning. I focus on building scalable solutions while demonstrating growth and ambition.

---

### Notes:

- **Updating the README**: You can replace placeholders (e.g., accuracy and results) once you finalize the models.
- Keep this **summary-focused** – no timeline or iterative process, just clean results.