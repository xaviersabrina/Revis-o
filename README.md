## Como executar o projeto:

Os comandos abaixo devem ser executados no terminal ou git bash.
Clonar o repositório:

``` git clone https://github.com/tdd-mastertech/crud.git ```

Entrar na pasta:

``` cd crud ```


Acesse a pasta e já delete a pasta .git para que depois você possa subir para seu próprio github.


Dentro da pasta, criar virtualenv

``` python -m venv env ```

ou

``` py -m venv env ```


Ativar virtualenv

```source env/bin/activate (Mac e Linux) ```

``` source env/Scripts/activate (Windows)```

Instalar requisitos

```pip install -r requirements.txt```

Em alguns casos é necessário atualizar o pacote PIP, para isso digitar o comando.

```python -m pip install --upgrade pip```


Executar servidor do Django

``` python manage.py runserver ```

Neste caso, aparecerá a mensagem de que é necessário aplicar migrações, basta digitar:

``` python manage.py migrate ```

Caso haja alteração das models.py, é necessário antes criar os arquivos de migração e depois aplicar com o migrate.
Para criar:

``` python manage.py makemigrations ```

Para acessar o admin, digite localhost:8000/admin. Para criar seu usuário, no terminal digite:

```python manage.py createsuperuser```

Preencha os campos para criar usuário, email e senha e seu super usuário estará criado.

Para parar o servidor, usar o comando Ctrl-C

