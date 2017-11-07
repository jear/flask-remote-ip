# flask-remote-ip

Flask Web App To Return your Public IP

## Setup

```
$ git clone https://github.com/ruanbekker/flask-remote-ip
$ cd flask-remote-ip
$ virtualenv .venv
$ source .venv/bin/activate
$ pip install -r requirements.txt
```

## Run the Server:

```
$ python app.py
 * Running on http://0.0.0.0:5000/ (Press CTRL+C to quit)
```

## Getting your Public IP from a Remote Client:

```
$ curl http://ip-flask-app:5000/
10.20.30.40
```
