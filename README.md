# Simple-Python-Chatbot

Creating a simple Python chatbot using natural language processing and deep learning.

<h2> TOOLS USED <h2>
  - nltk libarary <br>
  - keras <br>
  - flask <br>
  
<h2> MAIN STEPS <h2> 
  - getting the right data - we are storing the questions answers in an JSON format in a file - intents.json <br>
  - cleaning, lematizing and everthing that is necesaary for the initial setup and saving 2 pickle files as - words.pkl and classes.pkl <br>
  - and creating Bag of Words <br>
  - Create model - 3 layers. First layer 128 neurons, second layer 64 neurons and 3rd output layer contains number of neurons <br>
  - and in the app.py we are creating a flask backend - restful api to connect with my android app <br>
  - it gives a json object as a response <br>
  
  - ANDROID - a simple android app ui with the networking - volley libarary to send a get request and gets a string response <br>
  - It displays the result in a ui <br>

CONTRIBUTOR -  <br>
Ankit - ETE - AEC - contribution - "Helped in fixing a bug while I was trying to deploy it on Heroku" <br>

