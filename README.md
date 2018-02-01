# Site-Django
Aplicação básica de um site de votos desenvolvido em Django e Python3.

Recursos utilizados:

    - Python
    - Django
    - Twig
    - sqlte3
    
Instalar Django com no Python 3:

    $ sudo python3 -m pip install Django
    
Verificar a versão do Django instalada:

    $ python3 -m django --version

Executar o *server*:

    $ python3 manage.py runserver
    
Criar *migrate*:

    $ python3 manage.py sqlmigrate polls 0001
    
Executar *migrate* no banco de dados:

    $ python3 manage.py migrate