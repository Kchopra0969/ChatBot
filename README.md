# <a href="https://github.com/rhildred/es6-twilio-chatbot" target="_blank">es6-twilio-chatbot</a>

I got the user interface for the web from a student of mine, Pat Wilken.

A chatbot written in es6 and vs6 for twilio and testing on the web. The important files are index.js and game.js.

A popular theme for the upcoming Halloween holiday is to make haunted house simulations. You will make a choose your own adventure for a haunted house presented as a Twilio chatbot. 

Marking
-----

|Element|Out Of|
|---|---|
|get a game or choose your own adventure in es6| 60|
|count case and if statements|2/3 each up to 20 points|
|spelling and grammar|10|
|on time|10|

This is a chatbot that uses deep learning and intent recognition. The user may ask a question whose answer already exists in the database. But there are many ways to frame the same question and it's impossible to hard-code each exact phrasing of the question into the code. To overcome this problem, we associate each answer in our database with an intention. The 'Intention' is the meaning of the question. If the user phrases the same question in multiple ways, they will all be mapped to the same intention because they all have the same general meaning. Then the corresponding answer is returned.

eg. 'Hello' , 'Hi' , 'Nice to meet you' and 'Good morning' can all be mapped to the intention 'Greeting'. Then the answer for this intention is return, such as 'Nice to meet you too'.

The model is currently trained on a small number of intents. It recognizes the intent of the user's query and gives the appropriate response.

The chat bot is in python. Text is entered by the user as a command line argument. The python script uses a model which has been trained on many intents. Using this model, it predicts the intent of the user entered text. For each intent there is a single fixed response, which the chat bot gives.


