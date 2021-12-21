# [Heroku](https://www.heroku.com/) usando python com Flask


### Instalação

#### Ambiente virtual

```cmd
python -m venv heroku-env
cd heroku-env/Scripts && activate && cd ../../
```

#### Dependencias
```
pip install -r requirements.txt
```

###### Configuração de deploy

Heroku precisa conhecer as dependências do aplicativo para que no momento do deploy crie o ambiente corretamente, para isso definimos o arquivo de requirements com as dependencias.

O arquivo Procfile, na raiz da branch, define o comando que o Heroku deve usar para executar no aplicativo. Basicamente, o mesmo comando que usaríamos para executar o aplicativo localmente. o mesmo deve permanecer na raiz do projeto.

###### Deploy

* Login no Heroku
* conectar conta Heroku com git
* Selecionar projeto para deploy 
