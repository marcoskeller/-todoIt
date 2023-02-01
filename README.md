# -todoIt

Este é um produto chamado TodoIt que permite os usuários controlarem as suas tarefas diárias. 

-->Para registrar, o usuário fornece o e-mail e a senha. 
--->Para cada tarefa, o título, a descrição, a categoria e a data de vencimento.

## Nome(s) do(s) programador(es)

```bash
Marcos Keller da Fonseca
```

## Framework(s) Utilizado(s)

```python
DJango
```

## Modo de Execução

```python

1º - Realize o Clone do Projeto

-->git clone https://github.com/marcoskeller/todoIt.git

2º - Crie e Ative o ambiente virtual com os comandos abaixo

-->python3 -m venv venv
--->venv/Scripts/activate

3º -  Realize a instalação das dependências necessárias do projeto com o comando abaixo

-->pip install -r requirements.txt

4º - Realize a criação e execução do ambiente de Migração usando os comandos abaixo

-->python mananage.py makemigrations
O comando acima irá obter a estrutura das classes definidas no arquivo models.py e criará os arquivos de migração de cada classe.

--->python manage.py migrate
Após criar os arquivos que definem a estrutura de cada entidade no banco de dados, precisamos executar estas migrações. Para isso, utilizamos o comando acima

---->

5º - Executar Servidor de Desenvolvimento

-->python manage.py runserver


=>Agora antes de prosseguir é um passo muito importante

6º - Para fazer login, você precisa criar um superusuário (superuser) - uma conta de usuário que pode controlar tudo no site. Volte à linha de comando, digite o comando abaixo: 

-->python manage.py createsuperuser 

e aperte Enter.

Quando for solicitado, insira seu nome de usuário (letras minúsculas, sem espaços), e-mail e senha. Não se preocupe por não conseguir ver a senha que está digitando - é assim mesmo. 
Digite a senha e aperte a tecla enter para continuar. 

7º - Volte ao seu navegador. Faça login com as credenciais de superusuário que você escolheu; você deverá ver o painel de controle de administração do Django.

8º - Abra seu navegador e cole o endereço abaixo

-->http://localhost:8000/login

```