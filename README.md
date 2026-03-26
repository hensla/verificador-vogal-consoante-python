🔤 verificador-vogal-consoante-python
Script simples em Python que verifica se uma letra maiúscula informada pelo usuário é uma vogal ou uma consoante.

📋 Descrição
O programa solicita que o usuário digite uma letra maiúscula e, com base em uma verificação condicional, identifica se a letra pertence ao grupo das vogais (A, E, I, O, U) ou das consoantes, exibindo o resultado no terminal.

💻 Código
pythonL = input("coloque uma letra aleatoria MAIUSCULA: ")

if L == "A" or L == "E" or L == "I" or L == "O" or L == "U":
    print(f"{L} é uma vogal.")
else:
    print(f"{L} é uma consoante.")

▶️ Como executar
Pré-requisitos

Python 3.x instalado na sua máquina
Download Python

Passos

Clone o repositório:

bash   git clone https://github.com/hensla/verificador-vogal-consoante-python.git

Acesse a pasta do projeto:

bash   cd verificador-vogal-consoante-python

Execute o script:

bash   python verificador.py

🖥️ Exemplo de uso
coloque uma letra aleatoria MAIUSCULA: A
A é uma vogal.
coloque uma letra aleatoria MAIUSCULA: B
B é uma consoante.
coloque uma letra aleatoria MAIUSCULA: I
I é uma vogal.

🧠 Conceitos utilizados

input() — leitura de dados do usuário
Estrutura condicional if / else
Operador lógico or
F-strings para formatação de saída


📁 Estrutura do projeto
verificador-vogal-consoante-python/
│
└── verificador.py

👤 Autor
Feito por hensla.

📄 Licença
Este projeto está sob a licença MIT.
