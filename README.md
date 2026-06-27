# chatbot_using_Llama2_LangChain_RAG
Create a chatbot for your own pdf file using Flask, a popular web framework, and the Langchain, another popular framework for working wtih Large Language Models (LLMs).
The chatbot will not just interact with users via text but also comprehend and answer questions related to the content of a specific document with the help of Retrieval Augmented Generation (RAG).

**LangChain**
LangChain is a versatile tool for building AI-driven language applications. It provides various functionalities such as text retrieval, summarization, translation, and many more, by leveraging pretrained language models. In this project, you will be integrating LangChain into your chatbot, empowering it to understand and respond to diverse user inputs effectively.

**Flask**
Flask is a lightweight and flexible web framework for Python, known for its simplicity and speed. A web framework is a software framework designed to support the development of web applications, including the creation of web servers, and management of HTTP requests and responses.

You will use Flask to create the server side or backend of your chatbot. This involves handling incoming messages from users, processing these messages, and sending appropriate responses back to the user.

**Routes in Flask**
Routes are an essential part of web development. When your application receives a request from a client (typically a web browser), it needs to know how to handle that request. This is where routing comes in.

In Flask, routes are created using the @app.route decorator to bind a function to a URL route. When a user visits that URL, the associated function is executed. In your chatbot project, you will use routes to handle the POST requests carrying user messages and to process document data.

Steps:

- Set up a development environment for building an assistant using Python Flask
- Implement PDF upload functionality to allow the assistant to comprehend file input from users
- Integrate the assistant with open source models to give it a high level of intelligence and the ability to understand and respond to user requests
- Deploy the PDF assistant to a web server for use by a wider audience.

For reference, take a look at : https://github.com/ibm-developer-skills-network/wbphl-build_own_chatbot_without_open_ai

set up the environment by executing the following code
```
pip3 install virtualenv 
virtualenv my_env # create a virtual environment my_env
source my_env/bin/activate # activate my_env
```
and then:
```
pip install -r requirements.txt
```
install:
```
pip install "langchain==0.3.27" "langchain-core==0.3.80" "langchain-community==0.3.31" "langchain-huggingface==0.3.1" "langchain-text-splitters==0.3.11" "huggingface-hub==0.36.0" "tokenizers==0.19.1" "transformers==4.43.3" "sentence-transformers==2.7.0" "requests==2.32.5"
```