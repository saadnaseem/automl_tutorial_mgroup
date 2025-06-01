# automl_tutorial_mgroup


Part A: California housing dataset and Autogluon      
1- open the google colab file   
2- go to 'File' -> 'Save a copy in drive'  
3- click 'connect' upper right corner  
Script: [https://colab.research.google.com/drive/1cFR4n7N0WxUI2vtQiEzjbEzbgULWXmfI?usp=sharing](https://colab.research.google.com/drive/1VnQN9RvokqOZ1Ncu5g4448Ifdl3hVRRl?usp=sharing)   
autogluon: https://auto.gluon.ai/    

Part B: California housing dataset and TabPFN  
Script: https://colab.research.google.com/drive/1Mbkvk2egLQkVN6qCimvhIDCSyrX1OWxj?usp=sharing     

TabPFN: https://www.nature.com/articles/s41586-024-08328-6      

List of models
https://s3.amazonaws.com/assets.datacamp.com/email/other/ML+Cheat+Sheet_2.pdf

"Although TabPFN provides a powerful drop-in replacement for traditional tabular data models such as CatBoost, similar to these models, it is intended to be only one component in the toolkit of a data scientist. Achieving top performance on real-world problems often requires domain expertise and the ingenuity of data scientists. As for other modelling approaches, data scientists should continue to apply their skills and insights in feature engineering, data cleaning and problem framing to get the most out of TabPFN. We hope that the training speed of TabPFN will facilitate faster iterations in the data science workflow."



# 🧠 AutoML Tutorial with AutoGluon and TabPFN  
**Predict California Housing Prices Using Two AutoML Tools**

This repository contains two tutorials that show how to use state-of-the-art AutoML methods—**AutoGluon** and **TabPFN**—on the California Housing dataset.

---

## 📌 What is AutoML?  
**AutoML (Automated Machine Learning)** automates the process of training machine learning models: model selection, hyperparameter tuning, ensembling, and evaluation—making it faster and easier to build high-performing models without manual coding.

---

## 🔹 Dataset
We’ll use the California Housing dataset (a regression problem) 
[Dataset](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset)

## 🔹 Part A: AutoGluon + California Housing

A hands-on guide using [AutoGluon](https://auto.gluon.ai/), an open-source AutoML toolkit by Amazon.

### 📄 Instructions:
1. Open this Google Colab notebook:  
   [Tutorial Link](https://colab.research.google.com/drive/1cFR4n7N0WxUI2vtQiEzjbEzbgULWXmfI?usp=sharing)
2. Go to `File` → `Save a copy in Drive`
3. Click `Connect` (upper right corner) and start running cells

---

## 🔹 Part B: TabPFN + California Housing

Try out [TabPFN](https://www.nature.com/articles/s41586-024-08328-6), a fast transformer-based model trained to approximate Bayesian posteriors.

### 📄 Instructions:
1. Open this Google Colab notebook:  
   [Tutorial Link](https://colab.research.google.com/drive/1Mbkvk2egLQkVN6qCimvhIDCSyrX1OWxj?usp=sharing)
2. Go to `File` → `Save a copy in Drive`
3. Click `Connect` to run

---

## 🧠 Notes on TabPFN

> “Although TabPFN provides a powerful drop-in replacement for traditional tabular data models such as CatBoost, similar to these models, it is intended to be only one component in the toolkit of a data scientist. Achieving top performance on real-world problems often requires domain expertise and the ingenuity of data scientists. As with other modeling approaches, data scientists should continue to apply their skills and insights in feature engineering, data cleaning and problem framing to get the most out of TabPFN. We hope that the training speed of TabPFN will facilitate faster iterations in the data science workflow.”

---

## 📚 Additional Resources

- 🔗 [AutoGluon Docs](https://auto.gluon.ai/)
- 🔗 [TabPFN Research Paper](https://www.nature.com/articles/s41586-024-08328-6)
- 📄 [ML Models Cheat Sheet (PDF)](https://s3.amazonaws.com/assets.datacamp.com/email/other/ML+Cheat+Sheet_2.pdf)

---

## 🛠 Requirements

Both tutorials run in **Google Colab**, no installation needed.  
To run locally:

```bash
pip install autogluon
pip install tabpfn
```

---

## ✅ Summary

| Tool      | Task         | Highlights                         |
|-----------|--------------|------------------------------------|
| AutoGluon | Regression   | Fast, interpretable, ensemble-based|
| TabPFN    | Regression   | Fast transformer, few-shot learning|

