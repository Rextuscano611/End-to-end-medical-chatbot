# End-to-End Medical Chatbot

This project is an AI based medical chatbot that can answer basic health related questions. The chatbot uses natural language processing techniques to understand user queries and generate responses. The aim of this project is to explore how AI and machine learning can be used to build conversational systems for healthcare information.

## Features

* Chat interface for asking medical questions
* Uses NLP techniques to understand user queries
* Retrieves information from medical knowledge sources
* Simple web interface for interacting with the chatbot

## Technologies Used

Python
LangChain
Flask
Vector Database (Pinecone)
Large Language Model (Llama 2)

## Project Structure

```
End-to-end-medical-chatbot
│
├── app.py
├── requirements.txt
├── store_index.py
├── src/
├── templates/
├── static/
└── README.md
```

## Installation

Clone the repository:

```
git clone https://github.com/Rextuscano611/End-to-end-medical-chatbot.git
```

Move into the project folder:

```
cd End-to-end-medical-chatbot
```

Install the required dependencies:

```
pip install -r requirements.txt
```

## Running the Project

First run the indexing script:

```
python store_index.py
```

Then start the application:

```
python app.py
```

Open the browser and go to:

```
http://localhost:5000
```


