# Decision Boundary Exploration

In this project, we explore **how different decision boundaries affect classification results**.

---

## 🔎 What is a Decision Boundary?
A **decision boundary** is a threshold or rule that separates different classes in a classification problem.  
It defines which side of the boundary a data point falls on and thus determines its predicted class.  

---

## ⚙️ Method
1. Initially, we defined two one-dimensional normal distributions.  
2. Using a **decision boundary of 0.5**, we separated the two distributions.  
3. Then, we changed the decision boundary to **0.9** and observed how the classification changed.  

---

## 🎯 Conclusion
- The **choice of decision boundary** depends on the relative importance of **Type I and Type II errors**.  
- For example, in medical applications, it may be preferable to **misclassify a healthy person as sick** rather than **misclassify a sick person as healthy**, because failing to detect a disease can have more serious consequences.  

This project demonstrates how adjusting decision boundaries allows us to **balance different types of classification errors** according to the problem's requirements.
