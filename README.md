## Checklist do projeto back-end Django da Semana Multi Stack TreinaWeb

💻 [Repositório - GitHub](https://github.com/treinaweb/treinaweb-workshop-multistack-python)

## Checklist do Ambiente

- [ ]  Instalar Python
    - 📥 [Download](https://www.python.org/downloads/)
- [ ]  Instalar PyCharm
    - 📥 [Download](https://www.jetbrains.com/pt-br/pycharm/download/)
- [ ]  Instalar Insomnia
    - 📥 [Download](https://insomnia.rest/download)
- [ ]  Instalar DBeaver
    - 📥 [Download](https://dbeaver.io/download/)

🔗 [Instruções de configuração - Windows](https://www.treinaweb.com.br/blog/configurando-ambiente-de-desenvolvimento-django-no-windows/)

🔗 [Instruções de configuração - Linux](https://www.treinaweb.com.br/blog/configurando-ambiente-de-desenvolvimento-django-no-linux/)

🔗 [Instruções de configuração - macOS](https://www.treinaweb.com.br/blog/configurando-ambiente-de-desenvolvimento-django-no-macos/)

## Checklist da Criação do Projeto

- [X]  Criar o projeto

    `django-admin startproject ediaristas_workshop`

- [X]  Criar aplicação

    `python [manage.py](http://manage.py) startapp web`

- [X]  Iniciar o servidor

    `python [manage.py](http://manage.py) runserver`

## Checklist do Desenvolvimento da App Web

- [X]  Criar migrações do model

    `python [manage.py](http://manage.py) makemigrations`

- [X]  Executar migrações no banco de dados

    `python [manage.py](http://manage.py) migrate`

- [X]  Criar pasta `forms` dentro da app `web`
- [X]  Criar pasta `templates` dentro da app `web`
- [X]  Criar arquivo `[urls.py](http://urls.py)` dentro da app `web`

## Checklist do Desenvolvimento da App Api

- [ ]  Criar aplicação

    `python [manage.py](http://manage.py) startapp api`

- [ ]  Criar pasta `pagination`  dentro da app `api`
- [ ]  Criar pasta `serializer` dentro da app `api`
- [ ]  Criar pasta `services` dentro da app `web`
- [ ]  Criar pasta `service` dentro da app `api`

## Problemas frequentes

- Caso a virtualenv não esteja ativada no Windows, digite os seguintes comandos no terminal do PyCharm:
    - cd venv\Scripts
    - activate
    - Ao final, o virtualenv será ativada, como mostra a imagem abaixo:

        
		
## Linguagens e Tools:
<p align="left">  
	<a href="https://www.python.org" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> 
	<a href="https://www.djangoproject.com/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/django/django-original.svg" alt="django" width="40" height="40"/> </a> 
	<a href="https://www.w3.org/html/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> 
	<a href="https://www.w3schools.com/css/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="css3" width="40" height="40"/> </a>
	<a href="https://www.typescriptlang.org/" target="_blank"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="typescript" width="40" height="40"/> </a> 
	<a href="https://www.microsoft.com/en-us/sql-server" target="_blank"> <img src="https://www.svgrepo.com/show/303229/microsoft-sql-server-logo.svg" alt="mssql" width="40" height="40"/> </a> 
	<a href="https://dbeaver.io//" target="_blank"> <img src="https://dbeaver.io/wp-content/uploads/2015/09/beaver-head.png" alt="dbeaver" width="40" height="40"/> </a> 
</p>