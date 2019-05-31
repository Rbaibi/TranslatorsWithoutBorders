# Translators Without Borders Challenge
2nd edition of the Hackathon for Peace, Justice and Security

## HELP BRIDGE THE LANGUAGE GAP IN HUMANITARIAN WORK.
Improving humanitarian assistance by prioritising translation needs through automatic impact assessment.

**Background:** When humanitarians respond to disasters, they need to communicate with affected people, community leaders, and NGOs. Often however, they do not speak the same language. Translators without Borders (TWB) helps to bridge this gap by translating large amounts of key documents for humanitarian organizations. 

**Problem:** Due to the high volume of requests, we need to be able to prioritize the translations that are the most urgent. However, we have little information about the impact of the translations we have done so far. Knowing how effective previous translations were can help us prioritize future translations.

 We define impact as a mix of factors including but not limited to document type, audience, beneficiaries, relevance for concurrent crises, and sectors (Health, Logistics, Nutrition, Protection, Shelter, Water/Sanitation/Hygiene, Camp Coordination and Camp Management, Early Recovery, Education, Emergency Telecommunications, Food Security).      

**Solution:** Help TWB translate the most critical information first: build a tool to assess the impact of previous translations and to prioritize future ones.

A solution that can:

a)    Automatically assess the impact of translations produced by TWB in the past (maybe exploring the data, using Machine Learning, to find out meaningful patterns,)

and

b)    Predict the impact of a new requested translation.

For:

a) A static solution for a (repeatable) one-time analysis would suffice;

b) However, it would ideally be available via an API for integration with TWB’s translation management system. 

**Datasets:**

TWB corpus of ~5000 documents with the following metadata for each document:

original file format (.docx, .pdf, .pptx etc.)

time of translation request

NGO making the request

target language (source language is English for majority of the documents)

target country (probably of limited reliability)

The documents will be provided as text files.

Data from the United Nations Office for the Coordination of Humanitarian Affairs (OCHA)



## Deep Learning Resources
If you are developing a deep neural network based solution, you can use the free GPUs provided by either Google Colab or Kaggle. Here are the instructions for both:

### Google Colab:
Go to Google Colab and start a new notebook. You can use the instructions in this notebook to upload your datasets and work on them in Colab. When you need to use GPUs to train your models, switch GPU on under Edit --> Notebook settings. This notebook shows you an example of training a model built in TensorFlow using a GPU.

### Kaggle:
Go to Kaggle and create a user profile. Then, go to Kernels --> New Kernel. A blank notebook opens up, and you can write your code in here. You will see on the right side of the notebook an option to turn on the GPU. On the top right side of your notebook, you will see a symbol that looks like a cloud with an arrow on it. You can click on this to upload your data to Kaggle.

### Other options:
If you have a Google Cloud, or Amazon Web Services, or Paperspace account, etc, you can use one of these to train your models.
