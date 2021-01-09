[building-a-flask-app-with-docker-compose](https://pythonise.com/series/learning-flask/building-a-flask-app-with-docker-compose)
#############

Directory:
```
app
├── docker-compose.yml
├── flask
│   ├── Dockerfile
│   ├── .dockerignore
│   ├── app
│   │   ├── __init__.py
│   │   └── views.py
│   ├── app.ini
│   ├── requirements.txt
│   └── run.py
├── nginx
│   ├── Dockerfile
│   └── nginx.conf
├── .gitignore
└── readme.md
```

To Run:  
`docker-compose up --build`

To stop the service, hit `Ctrl + c`.