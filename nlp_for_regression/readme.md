# [Application the Bert-like NLP model for a regression task](https://github.com/ivan-aleshin/pet_projects/blob/main/nlp_for_regression/ebay_lenses_proj.ipynb)

[Dataset-compressed](https://github.com/ivan-aleshin/pet_projects/blob/main/nlp_for_regression/data_lens_final.rar)  
[Study Project](https://github.com/ivan-aleshin/pet_projects/blob/main/nlp_for_regression/ebay_lenses_proj.ipynb)

The goal of this study is explore the approach using the NLP model for the regression problem. 
The task is to try to predict the price of a product by its name. In this case, we take one category of goods - photographic lenses. The fact is that the name of a photo lens usually contains characteristics that affect the cost. Using a text classification model, we will extract embeddings and then apply classic ML models to these embeddings for final price predictions.  
For this study, a dataset was collected from the Ebay. Dataset consists more than 400,000 rows with two columns - the text name of the product and its cost in US dollars. The dataset includes products with a fixed price only.
The dataset has been pre-processed. Duplicate lines have been removed, as well as lines with an incorrect price value. For example, when a price range was specified. Some of the products do not match the lenses category. For example, there are some items from the accessories or cameras categories. Additional data cleaning is not provided in this work.  
  
---
  
What can be improved  

Apply gpu-based ML models evaluation. In this step we use only Ridge Regression model. SVM and KNN models takes too much time to evaluate on CPU.

To clean the dataset. For example, using semi-supervised learning methods. It also possible to make a classifier to determine whether a given product a lens or a camera or something else. To do this the additional datasets should be collected.  

There are mnay ovepriced items which can be listed for years without being sold. So for the real selling price the auction data and final prices should be used. But it'll take much more time to collect such data of an equivalent size.

**Tools & Skiils**  
[![Pandas](https://img.shields.io/static/v1?label=tool&message=Pandas&color=40407a)](#)
[![Huggingface](https://img.shields.io/static/v1?label=tool&message=huggingface&color=FFFF00)](#)
[![Python](https://img.shields.io/static/v1?label=tool&message=Python&color=33d9b2)](#)
[![SKLearn](https://img.shields.io/static/v1?label=tool&message=sklearn&color=cd6133)](#)
[![Transformers](https://img.shields.io/static/v1?label=tool&message=Transformers&color=FFBF00)](#)
[![Bert](https://img.shields.io/static/v1?label=tool&message=Bert&color=ebe834)](#)  
[![ML](https://img.shields.io/static/v1?label=skill&message=Machine%20Learning&color=1B9CFC)](#)
[![NLP](https://img.shields.io/static/v1?label=skill&message=Natural%20Language%20Processing&color=2ECC71)](#)
[![Feature Engineering](https://img.shields.io/static/v1?label=skill&message=Feature%20Engineering&color=B33771)](#)  

