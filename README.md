# VerifyInfluencers
An application challenge


## Primeiros passos

Para executar o projeto, criar e instalar o ambiente virtual (Windowns):
```
python -m venv venv
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
## Para executar

```
python manage.py runserver
```

Para buscar tweets de um influenciador:
```
http://127.0.0.1:8000/api/influencer/some_handle/tweets/
```
Para verificar as claims de um influenciador:
```
http://127.0.0.1:8000/api/influencer/some_handle/claims/

```
You can test the APIs using tools like Postman or cURL:
```
Fetch Tweets: /api/influencer/<twitter_handle>/tweets/
Analyze Claims: /api/influencer/<twitter_handle>/claims/
Verify Claim: /api/verify-claim/
Leaderboard: /api/leaderboard/
Influencer Claims: /api/influencer/<influencer_id>/claims/
```



