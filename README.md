

![Logo](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4d/OpenAI_Logo.svg/375px-OpenAI_Logo.svg.png)




# Chatbot Website with Open Source LLMs

This program will apply one of the AI intelligence models, namely LLMs, the final form of this program is a website in the form of a Chatbot which is trained to answer existing questions. The way this bot works is that we will send a message which will then be trained by the bot, at first the bot may answer a little strangely but after a few uses the bot will be trained to answer correctly because each conversation will be saved and used as an evaluation by the bot to answer next question.

This program uses a library from Huggingface, namely Transformers, which this time uses a training model from facebook/blenderbot-400M-distill and for the UI display here we use https://github.com/ibm-developer-skills-network/ LLM_application_chatbot by combining the two in here. will build a capable chat box training model.


## Installation

To using this repository, run the following commands

```bash
git clone https://github.com/firzzairvn/voiceAssistant-OpenAI-IBMWatson.git
```

Installation requirements

```bash
pip install flask
pip install flask_cors
pip install -r LLM_application_chatbot/requirements.txt
pip install transformers
```

    
## Deployment

If you use Visual Studio Code change port to 5000 and do the same thing in 
```bash 
\static\script.js
```
change const url = 'http://127.0.0.1:5000/chatbot';  to
```bash 
const url = 'http://yourLink.com/chatbox'; 
```
If you have finished changing the port to 5000 then do it
```bash 
flask run 
```



## Prerequisites

- Linux/MacOS x86_64/Windows
- Python (v3.8+)
- pip (v23.0+)
- Installed libraries packages

