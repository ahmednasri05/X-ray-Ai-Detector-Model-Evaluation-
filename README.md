# Research still in progress...!

# 🏥 AI-Assisted Fracture Detection in X-Rays

Welcome to the **AI-Assisted Fracture Detection** project repository! This project explores the effectiveness of AI in helping surgeons detect fractures in X-ray images. Our goal is to analyze how AI predictions align with medical professionals' diagnoses and identify areas for improvement using data science techniques. 

## 📝 Project Overview

### Research Question: 
How effective is the use of AI systems to assist surgeons in detecting fractures in X-rays?

### Team Objective:
To evaluate the AI system's performance compared to the **Gold Standard** (ground truth) and analyze the behavioral patterns of surgeons before and after using AI assistance. The project consists of two main parts:

## 🌟 Part 1: Doctor Behavioral Analysis

### Objectives:
- Evaluate how doctors' diagnoses improve or change with AI assistance.
- Analyze the impact of AI suggestions on medical procedures.

---

### ⚙️ Model Evaluation:

1. **Accuracy in Binary Classification** 🟢:
   - Measures the proportion of correct predictions (fracture/no fracture).
  
2. **Jaccard Index in Binary Classifier** 🔄:
   - Evaluates the similarity between predicted and actual fracture labels.

3. **Confusion Matrix in Binary Classification** 🔍:
   - Visualizes the number of true positives, false positives, true negatives, and false negatives
     
---

### 🔎 Exploratory Data Analysis:

#### **Comparison: Doctor Diagnoses Before and After AI** 📊
   - Compare the accuracy of diagnoses before and after AI assistance using bar plots or line graphs.

#### **Error Analysis**:
   1. **Disagreements Between Doctor and AI** ❓:
      - Investigate cases where the doctor and AI disagree. Identify which diagnosis aligns with the Gold Standard.
      
   2. **Changes in Doctor Diagnosis After AI** 🏥:
      - Study cases where the doctor changes their initial diagnosis after seeing AI recommendations.
      - **Sub-analysis**:
         1. **Impact on Procedures**: Did the AI influence changes in medical procedures? Were the changes beneficial?
         2. **Correctness of Changes**: Evaluate whether the changes in diagnosis were accurate according to the Gold Standard.

---

## 🌟 Part 2: AI Model Performance Evaluation

### Objectives:
- Evaluate the performance of the AI model using a variety of metrics.
- Investigate if there are any subgroup-specific trends.

---

### ⚙️ AI Model Evaluation:

1. **Accuracy Score** 📈: Measures overall prediction correctness.
2. **Jaccard Index** 🟣: Measures set similarity between the predicted and actual diagnoses.
3. **Confusion Matrix** 🔄: Breakdown of prediction results.
4. **Recall (Sensitivity)** 📡: Focuses on the ability to detect actual fractures (reducing false negatives).
5. **Precision** 🎯: Focuses on the correctness of fracture predictions (reducing false positives).
6. **F1 Score** 🏆: Balances recall and precision for imbalanced datasets.

---

### 🧩 Subgroup Analysis:
- Perform a detailed analysis to evaluate AI's performance on different demographic or medical subgroup Fractures.
- Investigate if certain Fractures are more prone to misdiagnosis.

## 🛠️ Technologies Used

- Python 🐍
  - Libraries: `pandas`, `numpy`, `matplotlib`, `seaborn`, `sklearn`
- Jupyter Notebooks 📓
- Git & GitHub 🌐
