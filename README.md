# Recommender-System-and-ConvAI-using-LLMs-on-e-commerce-Data

# **Project Summary:**
We'll use amazon's data for our project. You can either download data directly from [Kaggle](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset), or  you can donwload using Kaggle's API.

![ConvAI using LLMs ](https://github.com/Praveen76/Recommender-System-and-ConvAI-using-LLMs-on-e-commerce-Data/blob/main/Conversational%20AI.webp)

The idea of the project is to build a Recommender System, and implement a Conversation AI for different tasks ( explained below).

# Recommender System using cosine and jaccard similarity:
  * Product Clustering: We'll use product_id, Discounted_Price, Subcategory, rating to find products similarity.
  * User clustering: Calculate users similarity using jaccard similarity with input features such as user_id, product_id, Subcategory, rating.

# Conversational AI using LLMs:

  * Sentiment Analysis: We'll do sentiment analysis using BERT Model.
  * Generate Questions: We'll generate 4 questions per record that users could potentially ask to Virtual Assistant.
  * Answers users' questions: We'll use OpenAI's davinci engine to answer each question that users could potentially ask.
  * Summarize Product Description: We'll use t5-small model from Google to summarize product using product description  to users.


# Instructions for Installation

**Dependencies:**
You'll need to install below dependencies to run this project.
* numpy: 1.18.1
* pandas: 1.0.1
* matplotlib: 3.5.3
* seaborn: 0.10.0
* re: 2.2.1
* sklearn: 0.22.1
* xlsxwriter: 1.2.7
* scipy: 1.4.1
* transformers: 4.30.2
* openai: 0.28.1
* torch: 1.13.1+cpu


# License:
This project is open-source and distributed under the MIT License. Feel free to use and modify the code as needed.

# Issues:
If you encounter any issues or have suggestions for improvement, please open an issue in the Issues section of this repository.

# Contact:
The code has been tested on Windows system. It should work well on other distributions but has not yet been tested. In case of any issue with installation or otherwise, please contact me on [Linkedin](https://www.linkedin.com/in/praveen-kumar-anwla-49169266/)

# **About Me:**
I’ve been working as a Data Scientist for a very long time now. I've worked on various NLP, Machine learning & cutting edge deep learning frameworks to solve business problems. Please feel free to check out my personal wesbsite [TowardsMachineLearning.Org](https://towardsmachinelearning.org/) , where I cover an array of topics from Machine learning, NLP, Deep Learning, etc.
