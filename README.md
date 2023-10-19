# South_African_Language_Identification

## Project Description

Welcome to our project! Language is a powerful tool that can be used to strengthen democracy and promote social, cultural, intellectual, economic, and political development in South Africa.

This project aims to develop a language identification system that can accurately identify the language of any given text input, using natural language processing (NLP) techniques to analyze text features and determine the most likely language.

South Africa is a multilingual country with 11 official languages, each with equal status. Most South Africans are multilingual, speaking at least two or more official languages.

Given the multilingual population, it is important for our systems and devices to also communicate in multiple languages. This project will develop a system that can identify the language of any text input in any of South Africa's 11 official languages.

I am developing a system that can tell you which language a piece of text is written in, even if the text is in a language that you do not understand. For example, if you have a piece of text in isiZulu and you do not speak isiZulu, you can use this system to identify the language of the text.

*This system could be used in a variety of ways, such as:*

* To help people learn new languages
* To develop multilingual translation tools
* To create more inclusive and accessible systems and devices

I am excited to be working on this project and I believe that it has the potential to make a positive impact on South Africa.

## Features
* The system uses natural language processing (NLP) techniques to analyze text features and determine the most likely language.
* The system can identify the language of any text input, even if it is in a language that the user does not understand.
* The system supports all 11 official languages of South Africa.
* The system has a user-friendly interface that makes it easy to use, even for people who are not familiar with NLP or language identification.

## Tools Utilized:
* Python
* scikit-learn
* nltk
* Streamlit
* GitHub
* Comet

## Installation
1. Clone the repository: git clone https://github.com/OnyekaEkesi/South-Africa-language-identification.git

2. pip install the required libraries

## Usage
A demonstration of the identification app was made using streamlit.
1. Run the main script: python main.py

2 .Enter the text you want to identify the language

3. The system will display the identified language

## Data
The system needs a large and diverse dataset of text and language labels in order to learn how to identify the language of a given text input. The dataset should include a variety of text genres, such as news articles, social media posts, and academic papers. It should also represent the linguistic diversity of South Africa, including all 11 official languages and the many dialects and regional variations.

Using a dataset with an equal number of samples from each language helps to ensure that the model is not biased towards any one language. This is important because the system is designed to be used by people who speak all 11 official languages of South Africa.
![language distribution](https://github.com/obinnameso/South-Africa-language-identification/blob/main/images/lang_dist.jpg?raw=true)

## Best Model
The Naive Bayes classifier was chosen for the language identification system because it outperformed other models when tested on a labeled dataset of South African text samples. The classifier uses NLP techniques, such as n-gram analysis and character frequency distribution, to extract features from the text and make language predictions.

## Model Evaluation
The system's performance was measured using accuracy, precision, recall, and F1-score. These metrics assess how well the system can identify the language of text samples.
1. Accuracy: The percentage of text samples that the system classified correctly.
2. Precision: The percentage of text samples that the system classified as a particular language, which were actually of that language.
3. Recall: The percentage of text samples of a particular language that the system classified correctly.
4. F1-score: A measure of the system's overall performance, which takes into account both precision and recall.

## Future Work
* Improve the model's ability to identify language accurately by using more advanced NLP techniques.
* Create a more user-friendly web-based interface for the model, so that it can be easily accessed and used with other applications.

<br>
<br>

### Note: The code for this project is proprietary and cannot be shared with the public without permission.
