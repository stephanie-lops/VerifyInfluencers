## ---- UNDER DEVELOPMENT ----
# VerifyInfluencers
An application challenge

# Backend
## Getting Started

Create the venv virtual environment:
```
python -m venv venv
```
Activate the virtual environment (Windowns):
```
.\venv\Scripts\Activate
```

Install Django:
```
pip install django
```
Verify Django installation:
```
python -m django --version
```

Install libraries:
```
pip install requests djangorestframework openai
```
Install CORS:
```
pip install django-cors-headers
```
Install dotenv:
```
pip install python-dotenv
```
Install Openai:
```
pip install openai
```
## To to execute

```
python manage.py runserver
```
## Django REST Framework

Fetch Tweets:
```
http://127.0.0.1:8000/api/influencer/some_handle/tweets/
```
Analyze Claims:
```
http://127.0.0.1:8000/api/influencer/some_handle/claims/
```
Verify Claim:
```
http://127.0.0.1:8000/api/verify-claim/
```
Leaderboard:
```
http://127.0.0.1:8000/api/leaderboard/
```
Influencer Claims:
```
http://127.0.0.1:8000/api/influencer/<influencer_id>/claims/
```

# Frontend

Start:
```
cd verify-influencers-frontend
```
peerDependencies:
```
npm install --legacy-peer-deps
```
Install Axios: To fetch data from your Django API, install Axios:
```
npm install axios
```
Install React Router:
```
npm install react-router-dom
```
Install Bootstrap (optional):
```
npm install bootstrap
```
Install web-vitals module:
```
npm install web-vitals
```
Openai Installation:
```
npm install openai
```
## To run
```
npm start
```

