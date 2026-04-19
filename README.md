# GRC Flask App

Week 4 project from the GRC Engineering Roadmap.

## What it does
A Flask web application deployed on AWS EC2, serving as the foundation for a GRC compliance platform.

## Routes
- `/` — Homepage
- `/health` — Health check endpoint (returns JSON)

## Tech stack
- Python 3.14
- Flask 3.1
- Gunicorn
- AWS EC2 (eu-west-2, London)

## How to run locally
```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python app.py
```

## Deployment
Deployed on AWS EC2 t3.micro instance using Gunicorn as WSGI server.