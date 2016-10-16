# Facebook Messenger Bot
We are building a chat bot for the KOSS Fb page to automate messages. Work in progress.

## Run this bot for your page

Follow this link : https://blog.hartleybrody.com/fb-messenger-bot/

### Environment Variables for heroku

APIAI_CLIENT_ACCESS_TOKEN = client access token from api.ai <br>
FB_ACCESS_TOKEN = Facebook app access token <br>
PAGE_ACCESS_TOKEN = The page access token of your facebook page <br>
VERIFY_TOKEN = The verification token made while making a webhook

## What it can do
1. If the message contains `gsoc` or `google summer of code` it replies with metakgp wiki link of gsoc.<br>
2. If the message contains `dc` and `hub` and `add` it replies with the current Hit Hi Fit Hai dc hub address. <br>
3. From the menu you can choose `Facing development issues` and then enter your query and bot will reply with search results from stackoverflow.

## Installing it
Make sure you have python2 in your system. If the default python you use is python3 ie. when you type `python --version` in the terminal and it shows "python 3.x.x" then install python2 specifically by `sudo apt-get install python2`. After that use `virtualenv` to make sure that everytime you are in a terminal session, `python` refers to `python2` for all its dependencies rather than `python3`.
