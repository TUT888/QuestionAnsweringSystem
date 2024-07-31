# Information Retrieval-Based Question Answering System
[![en](https://img.shields.io/badge/lang-en-blue.svg)](https://github.com/TUT888/QuestionAnsweringSystem/blob/main/README.md)
[![vi](https://img.shields.io/badge/lang-vi-red.svg)](https://github.com/TUT888/QuestionAnsweringSystem/blob/main/README.vi.md)

Project: Information Retrieval-Based Question Answering System <br>
The project was done while studying "Introduction to Natural Language Processing" unit <br>

## Project Description

The project includes following sections:
1. Read question-answer data: The question-answer pairs data were collected from classmates. These data were categorized by topics.
2. Extract text data features: The TF-IDF technique was used to extract features.
3. Train model to predict the topic of the input question.
4. Find answers for input questions:
    - The input question was fed into the model to predict its topic.
    - Cosine Similarity was used to search for similar questions with the same topic in the available question-answer dataset.
    - Diplay the answer from the question with the highest similarity from the dataset.

## Library version

| Library | Version |
| --- | --- | 
| numpy | 1.19.5 |
| scipy | 1.5.4 |
| keras_preprocessing | 1.1.2 |
| sklearn | 0.19.0 |

## Files in repository
- retrieval_based_qa.ipynb file: the main Jupyter Notebook file of the project.
- chatbot folder: The text files contained the data of question-answer pairs categorized by topic.
  
## Reference 
Refer to the section 'Information Retrieval based chatbots (IR-based)' at: [Tìm hiểu và xây dựng hệ thống chatbot trong thực tế](https://viblo.asia/p/tim-hieu-va-xay-dung-cac-he-thong-chatbot-trong-thuc-the-XL6lA8D4Zek)

## Authors
The project was done by a group of 3 members:
- Uyen Tam Tat [Github](https://github.com/TUT888)
- Thuy Tien Duong [Github](https://github.com/tienduong-21)
- Hieu San Truong [Github](https://github.com/hs0512)
