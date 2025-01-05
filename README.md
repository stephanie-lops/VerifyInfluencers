# VerifyInfluencers
An application challenge


# Backend
## Primeiros passos

Criar o ambiente virtual venv:
```
python -m venv venv
```
Ativar o ambiente virtual (Windowns):
```
.\venv\Scripts\Activate
```

Instalar Django:
```
pip install django
```
Verificar instalação do Django:
```
python -m django --version
```

Instalação de bibliotecas:
```
pip install requests djangorestframework openai
```
Instalação de CORS:
```
pip install django-cors-headers
```
## Para executar

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
## Para executar
```
npm start
```
:
```

```


