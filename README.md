# 1. Criar novo ambiente venv

```
python3 -m venv venv
```
# 2. Ativar ambiente venv

```
source venv/bin/activate
```

# 3. Criar novo projeto Django

```
django-admin startproject app .
```

# 4. Executar aplicação do projeto Django

```
python3 manage.py runserver
```


# 5. Criar uma nova app Django

```
python3 manage.py startapp <nome da app>
```

# 6. Cria migrations baseados nos models (Observa alterações e gera script atualizações da estrutura do Banco de Dados)

```
python3 manage.py makemigrations
```

# 7. Executa migrations baseados nos models (Executa script de atualizações da estrutura do Banco de Dados)

```
python3 manage.py migrate
```

# 7. Criar superuser do django admin

```
python manage.py createsuper
```