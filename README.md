# SpotCheckAI

## Introduction

SpotCheckAI is a full-stack progressive web application (PWA) that can identify suspicious skin lesions as benign or cancerous. Users upload an image to the website and based on the Convolutional Neural Network Model, it will give a percentage of certainty that the model thinks is cancerous or benign.

SpotCheckAI's chatbot is powered by OpenAI's GPT-3 model and can answer questions regarding the results received or the website.

## Installation Guide

### Front End

Available on the web at: [insert website link here]

To Install Locally:

1. Clone Repository
2. ```cd path/to/frontend/folder```
3. ```ionic serve```

Note: Port is to localhost 8000


### Back End

Available on the web at: [insert website link here]

Note: Interface is not interactable on web-hosted website.

To Install Locally:

1. Clone Repository

2. Create Virtual Environment

3. Install dependencies

```
pip install -r /path/to/requirements.txt
```
4. ```cd path/to/backend/folder```
5. ```python manage.py runserver 7000```

Note: Port is to localhost 7000

## Folders

1. backend: contains all the files pertaining to the backend application
2. data: data used to train the ML model
3. documents: archive of documents
4. frontend-website: contains all the files pertaining to the frontend webpage
5. got-web-crawl-qa: contains webscraper and embeddings for the chatbot
6. model development: development of ML model
7. models: contains the ML model used in the application
