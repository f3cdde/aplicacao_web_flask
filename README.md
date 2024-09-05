# Aplicação Web com Flask

Este projeto cria uma aplicação web simples utilizando Flask, um micro framework para Python. A aplicação inclui uma página inicial e um formulário de contato.

## Estrutura do Projeto

aplicacao-web-flask/
│
├── src/
│   ├── app.py
│   ├── templates/
│   │   ├── index.html
│   │   └── contact.html
│   └── static/
│       └── styles.css
│
├── .gitignore
├── Dockerfile
├── README.md
└── requirements.txt

2.  Construa a imagem Docker:
    docker build -t aplicacao-web-flask .

3.  Execute o contêiner Docker:
    docker run -p 5000:5000 aplicacao-web-flask

4.  Acesse a aplicação no navegador:
    http://localhost:5000