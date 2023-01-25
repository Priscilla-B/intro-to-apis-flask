# Example Application - Complimentr

This application is meant to be used with the [Introduction to APIs course](https://github.com/craigsdennis/intro-to-apis-course).

## Use this on Glitch

[Remix on Glitch](https://glitch.com/edit/#!/import/git?url=https://github.com/Priscilla-B/intro-to-apis-flask)


## Local Installation

Create a `.env` file and update it with your [Twilio](https://twilio.com) credentials.

### Running the application

* `python -m venv .venv`
* `source ./.venv/bin/activate`
* `pip install -r requirements.txt`
* `FLASK_ENV=development flask run`

#### In Development mode

* Run [ngrok](https://ngrok.com/) on port 5000
* Visit your ngrok url!
