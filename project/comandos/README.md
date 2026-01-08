

## Iniciar projeto django
```
python -m venv venv
.\venv\Scripts\activate
pip install django
django-admin startproject project .
python manage.py startapp contact
```

## Testar runserver
python manage.py runserver

```
# Configurar o Git:
git config --global user.name 'Rafael Santana'
git config --global user.email 'rafa93melo@gmail.com'
git config --global init.defaultBranch main
# Configurar o .gitignore
git init
git add .
git commit -m 'Mensagem'
#Verifica o log do comit com autor e data
git log
# Add projeto ao repositório criado no github
git remote add origin URL_DO_GITREPOSITORIO


# Demais commits:
git add .
git status                           (Esse é opicional, serve para ver o que está adicionando)
git commit -m 'alteração feita'
git push
```