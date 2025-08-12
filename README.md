Sistema de Login Simples em Python
Este é um exemplo básico de sistema de login usando Python, onde o usuário precisa digitar seu nome e senha para ter acesso.

Como funciona
O programa solicita que o usuário digite seu nome.

Depois, pede a senha.

Se o usuário for "Olegario" e a senha for "234", o acesso é liberado com uma mensagem de boas-vindas.

Caso contrário, uma mensagem de erro é exibida.

Código
python
Copiar
Editar
usuario = input("Digite seu nome: ")
senha = input("Digite a senha: ")

if usuario == "Olegario" and senha == "234":
    print("Bem-vindo, Olegario!")
    print("👌👌👌")
else:
    print("Usuário ou senha incorretos. Tente novamente ")
    print("🤐🤐🤐")
Como executar
Certifique-se de ter o Python instalado na sua máquina.

Salve o código em um arquivo, por exemplo login.py.

Execute no terminal ou prompt de comando com:

bash
Copiar
Editar
python login.py
