# Testes_Django
##Testes realizados com demo Django

https://docs.djangoproject.com/en/1.8/intro/tutorial01/

--Passos:

1 - Instalar o Django
```
  #MAC
    sudo easy_install pip
    pip install Django
```    
2 - Testar se o módulo foi instalado:
```
 $ python -c "import django; print(django.get_version())"
``` 
3 - Criar o projeto:
```
 $ django-admin startproject mysite
``` 
4 - Estrutura do site:
```
mysite/
    manage.py
    mysite/
        __init__.py
        settings.py
        urls.py
        wsgi.py
```
5 - Escolha o banco de dados, editando o arquivo abaixo:
```
   mysite/settings.py
```
6 - Para criar a estrutura do db, rode o comando abaixo:
```
  $ python manage.py migrate
```  
7 - Rodando o servidor:
```
  $ python manage.py runserver  
  $ python manage.py runserver 8080 #Para rodar numa porta específica;
```  
8 - Crie seus modelos (exemplo: polls):
```
  $ python manage.py startapp polls
```  
9 - Crie os formulários do Admin baseados nos modelos;

10 - Crie o site usando templates e consumindo os dados populados pelo Admin via Modelos.
