# <h1 align="center">**Summarization**</h1>

<p align="center">
<img src="images/image_readme.jpeg"> 
</p>

In this repository, text summarization models are implemented, a task within Natural Language Processing (NLP) that involves creating a shorter version of a document or article while capturing all essential information. Specifically, abstractive summarization models are developed to generate new text that synthesizes the most relevant information. These models are built using TensorFlow and Hugging Face.

The most important use cases include improving efficiency in reviewing large volumes of text, such as in academic research and legal document auditing. Additionally, these models are useful in customer service applications where long interactions need to be summarized for quick reference. They can also be used in journalism to create concise summaries of extensive news articles and in business information management to produce executive summaries that facilitate decision-making.


## **Implemented Models:**
- **Text Summarization with a Transformer Model:** This [sequence-to-sequence Transformer model](https://huggingface.co/learn/nlp-course/en/chapter1/7) is implemented from scratch, including its architecture, custom loss function, and optimizer. It is trained on the [Extreme Summarization (XSum) Dataset](https://huggingface.co/datasets/EdinburghNLP/xsum), which contains BBC news articles along with their corresponding concise summaries in a single sentence. The results on the validation dataset are: **`rouge1`: 27.66**, **`rouge2`: 8.51**, **`rougeL`: 22.27**, **`rougeLsum`: 22.28**.

- **Text Summarization with the [Text-To-Text Transfer Transformer (T5) model](https://huggingface.co/docs/transformers/model_doc/t5):** The [T5 Base](https://huggingface.co/google/t5-base) model is fine-tuned with the same XSum dataset to achieve better results and consequently higher text summarization quality. The results on the validation dataset are: **`rouge1`: 40.11**, **`rouge2`: 17.03**, **`rougeL`: 32.21**, **`rougeLsum`: 32.2**.

## **Some Results**

<p align="left">
<img src="images/images_models/summary_1.png" style="width: 888px;"> 
</p>

---
<p align="left">
<img src="images/images_models/summary_4.png" style="width: 746px;"> 
</p>

---
<p align="left">
<img src="images/images_models/summary_2.png" style="width: 1144px;"> 
</p>

---
<p align="left">
<img src="images/images_models/summary_6.png" style="width: 1366px;"> 
</p>

---
<p align="left">
<img src="images/images_models/summary_3.png" style="width: 1358px;"> 
</p>

---
<p align="left">
<img src="images/images_models/summary_5.png" style="width: 903px;"> 
</p>

#### *More results can be found in the respective notebooks.*

## **Technological Stack**
[![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white&labelColor=101010)](https://docs.python.org/3/) 
[![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white&labelColor=101010)](https://www.tensorflow.org/api_docs)
[![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=white&labelColor=101010)](https://huggingface.co/)
[![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white&labelColor=101010)](https://plotly.com/)

## **Contact**
[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white&labelColor=101010)](mailto:jerson.gimenesbeltran@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=101010)](https://www.linkedin.com/in/jerson-gimenes-beltran/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white&labelColor=101010)](https://github.com/JersonGB22/)