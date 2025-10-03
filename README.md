# AI-Powered Sentiment Analysis 
*A case study using AI/ML to unlock customer insights from unstructured feedback/reviews*  

## 🔍 Project Overview  
This project applies **Aspect-Based Sentiment Analysis (ABSA)** using **Machine Learning**(BERT Model) to analyze and classify student reviews about their **food experience** on university campus.  

**Example:**  
- Review: *“The food tasted great, but it was too expensive.”*  
- Aspect-Based sentiment:  
  - **Taste** → Positive  
  - **Price** → Negative  

This approach is valuable because it provides **granular insights** into what exactly students like or dislike, helping decision-makers improve specific areas (e.g., pricing, quality, service) instead of relying on general sentiment alone.  

The goal is to demonstrate how **AI can transform qualitative feedback** into measurable insights, helping institutions improve **cafeteria services** and enhance student satisfaction.  

---

## 🎯 Business Value  
Institutions often gather feedback from students, but the comments are usually **free-text and unstructured**, making them hard to interpret at scale.  

**Why it’s valuable:**  
- Analyzes thousands of customer feedback faster and more accurately  
- Converts feedback into actionable insights  
- Tracks satisfaction and identifies issues early  
- Supports data-driven improvements  

**Other applications:**  
- Businesses: understand customer sentiment and improve products  
- Healthcare: monitor patient experience and service quality  
- Hospitality: enhance guest satisfaction and service offerings  
- Applicable to any sector collecting unstructured feedback


---

## 🛠️ Technical Approach

### 1. Data Collection
- Collected student food reviews via Google Forms.  
- Used a restaurant review dataset and nigerian meals dataset for model fine-tuning.  

### 2. Model Training
- Fine-tuned **BERT (RoBERTa)** for **Aspect-Based Sentiment Analysis**.  
- Trained to classify sentiment as **Positive, Negative, or Neutral** for 5 aspect-categories: Food, Service, Portion size, Ambience & Price 

### 3. Evaluation
- Tested the model to assess **accuracy and performance**.  

### 4. Application
- Used the fine-tuned model to **analyze and classify student feedback**.  

### 5. Tools
- **Python**, **PyTorch**, **Transformers (HuggingFace)**, **Jupyter Notebook**  
- **Pandas**, **NumPy**, **Matplotlib** for data handling and visualization

---

## 📈 Results & Insights  
- The BERT model achieved an accuracy of 93% showing strong performance in classifying **positive, negative, and neutral** sentiments along with their aspect categories.

