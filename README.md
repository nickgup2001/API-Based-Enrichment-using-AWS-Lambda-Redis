# API-Based Data Enrichment Microservice

## 🌐 Overview
This project enriches user contact data by integrating with third-party APIs (Melissa, StrikeIron) using AWS Lambda. A Flask-based microservice exposes REST endpoints, and Redis is used to cache repeated API responses for efficiency.

## 🛠️ Technologies
- AWS Lambda
- Python, Flask
- Redis
- Postman
- GitHub

## 🎯 Key Features
- REST API built with Flask
- On-demand data enrichment via Lambda
- Response caching with Redis
- Postman tested endpoints

## 🧪 How to Test
Use Postman with the provided `postman_collection.json`. Redis will return cached responses for duplicate API calls.

## 📂 Structure
- `flask_app/`: Flask service files
- `lambda/`: AWS Lambda script for API calls
- `redis_cache.py`: Redis client for caching

## ⚙️ Setup
Install dependencies with `pip install -r requirements.txt`. Run Flask locally using `python app.py`.

