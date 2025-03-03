# 🛒 Support Vector Machines for Purchase Prediction  

## 📄 Project Overview  
This project focuses on **classifying purchase behavior** (**FN vs. MM**) using **Support Vector Machine (SVM) models** and optimizing the **hyperparameters** to improve model performance.  

## 📂 File: `SVM Model_Analysis.pdf`  

## 🎯 Objective  
- Build an **SVM model** to predict purchase behavior.  
- Tune hyperparameters to **optimize model performance**.  
- Compare **different SVM kernels** to determine the best-performing model.  

## 🛠 Data Preprocessing  
- Loaded the dataset: `juice2022.csv`.  
- Split data into **training (90%)** and **testing (10%)** using `createDataPartition()`.  

## ⚙ Model Implementation  
- Implemented an **initial SVM model** with a **linear kernel** using `svm()` (`cost = 0.01`).  
- Evaluated model performance using:  
  - **Accuracy**  
  - **Training error rate**  
  - **Test error rate**  

## 🔧 Hyperparameter Tuning  
- Used `tune()` function to find the **optimal cost parameter** in the range **0.01 to 10**.  
- Identified the **best cost parameter** that minimized **test error**.  

## 📊 Comparison of SVM Kernels  
- Tested different **SVM kernels**:  
  - **Linear Kernel**  
  - **Radial Kernel**  
  - **Polynomial Kernel**  
- The **radial kernel** performed best with the **lowest test error rate (0.434)** after tuning.  

## 🏆 Final Recommendation  
- Use **Radial Kernel SVM** with **cost = 0.5** for the best results.  

---

## 📌 Key Takeaways  
✅ **Preprocessing** helps in cleaning and splitting data effectively.  
✅ **Hyperparameter tuning** plays a crucial role in model performance.  
✅ **The radial kernel SVM** significantly outperformed other kernels in this case.  

