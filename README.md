# Temp email creator bot

Python scripted telegram bot. <br>
Link: https://t.me/project_temp_email_bot

## Tools

`Python 3` using the `pyTelegramBotAPI`. 

## How to install and prepare for running?

Clone this git repository: 
```
http: git clone https://github.com/aakashirkina/temp_email_bot.git
ssh: git clone git@github.com:aakashirkina/temp_email_bot.git
```
Then create, activate virtual environment, update pip and install all requirements: <br>
```
python3 -m venv venv
source venv/bin/activate
pip install -U pip
pip install -r requirements.txt
```
For Windows:
```
python -m venv venv
venv/Scripts/activate
pip install -U pip
pip install -r requirements.txt
```

## How to run?

add src file to path `export PYTHONPATH=$PYTHONPATH:$(pwd)/src` <br>
run `python ./src/app.py`
