# SMS Client Api

###### This is an sms service that provides endpoints for sending sms via either Nexmo or AfricasTalking

Here's the basic directory structure;
```
├── app
│   ├── config.py
│   ├── __init__.py
│   ├── models
│   │   └── __init__.py
│   ├── resources
│   │   └── __init__.py
│   ├── templates
│   │   └── index.html
│   ├── utils
│   │   └── __init__.py
│   └── views
│       └── __init__.py
├── README.md
├── requirements.txt
├── test
│   └── __init__.py
└── wsgi.py

```

### Project Set up
- clone this repository
- cd into project folder
- create a virtual environment i.e virtualenv venv
- activate virtual environment i.e source venv/bin/activate
- run pip install -r requirements.txt
- start the project : python wsgi.py
