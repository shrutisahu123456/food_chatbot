# food_chatbot
this is the chatbot for a food website that can assist customer queries.
visit website: https://shrutisahu123456.github.io/food_chatbot/

here is the demo video link:
https://github.com/shrutisahu123456/food_chatbot/assets/120123564/7da630df-40b8-47c8-94b6-ef5c722ac278

About files
===================
main.py: Contains Python FastAPI backend code
dp_helper.py, gen_helper.py : contains the dump of the database. you need to import this into your MySQL db by using MySQL workbench tool
training_phrases: this has training phrases etc. for our intents
frontend: website code

Install these modules
======================

pip install mysql-connector
pip install "fastapi[all]"

OR just run pip install -r backend/requirements.txt to install both in one shot

To start fastapi backend server
================================
1. Go to backend directory in your command prompt
2. Run this command: uvicorn main:app --reload

ngrok for https tunneling
================================
1. To install ngrok, go to https://ngrok.com/download and install ngrok version that is suitable for your OS
2. Extract the zip file and place ngrok.exe in a folder.
3. Open windows command prompt, go to that folder and run this command: ngrok http 80000

NOTE: ngrok can timeout. you need to restart the session if you see session expired message.
