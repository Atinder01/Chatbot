# Chatbot
## A python based Chatbot Project using NLTK and Keras

Live link for the project goes [here](https://share.streamlit.io/atinder01/chatbot/main/chatapp.py)

### What is Chatbot?

A chatbot or chatterbot is a software application used to conduct an on-line chat conversation via text or text-to-speech, in lieu of providing direct contact with a live human agent.In this Python project, we are going to build a chatbot using deep learning techniques. The chatbot will be trained on the dataset which contains categories (intents), pattern and responses. We use a special recurrent neural network (LSTM) to classify which category the user’s message belongs to and then we will give a random response from the list of responses.

**Tools and libraries used:** Keras, Tensorflow,NLTK,Streamlit

**The file structure and the type of files created**
* **intents.json** – File containg training dataset.
* **main.py** – Python file to build model and train chatbot.
* **words.pkl** – This is a pickle file in which we store the words Python object that contains a list of our vocabulary.
* **classes.pkl** – The classes pickle file contains the list of categories.
* **chatbot_model.h5** – This is the trained model that contains information about the model and has weights of the neurons.
* **chatapp.py** – This is the Python script in which we implemented GUI for our chatbot. Users can easily interact with the bot.

**Steps followed to create the Chatbot:**

* Import and load the data file
* Preprocess data
* Create training and testing data
* Build the model
* Predict the response
* Deploy using streamlit

![flowchart](https://user-images.githubusercontent.com/67895402/141610865-fb25a406-c611-4d7e-b142-364052629ded.png)
 
**Glimpses of webapp**

![image](https://user-images.githubusercontent.com/67895402/141611068-461d2e37-c994-44a0-9e37-5b5204c5a7ff.png)
![image](https://user-images.githubusercontent.com/67895402/141611082-752a8510-6683-40aa-9e66-e9fb4819c0a6.png)


