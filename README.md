# deploy-docker-compose-flask

Exemplo de estudo sobre deploy de um projeto flask com docker-compose.


## Rodando o projeto

```
git clone https://github.com/rg3915/deploy-docker-compose-flask.git
mv deploy-docker-compose-flask app
cd app
python -m venv .venv
source .venv/bin/activate
pip install -U pip; pip install -r requirements.txt


gunicorn -b 0.0.0.0:5000 app:app
```

