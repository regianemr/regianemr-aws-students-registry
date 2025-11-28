# 🎓 Cadastro de Alunos — Projeto Full Stack (Flask + MySQL + AWS)

Este projeto implementa um sistema de cadastro e listagem de alunos, com backend em Flask, banco MySQL no RDS, frontend simples e um deploy estático no S3.

O objetivo foi reforçar conceitos de APIs REST, banco relacional, integração com cloud e deploy na AWS.

## 📸 Demonstração
🌟 Tela Inicial

<div  align="center">  <img  src="https://i.imgur.com/tDOOd54.png"  width="650">  </div>

📝 Cadastro em Ação

<div  align="center">  <img  src="https://i.imgur.com/VlFBW5P.gif"  width="650">  </div>


## 🚀 Funcionalidades
- 📌 API – Endpoints

- Método Rota Descrição

- POST /cadastro Insere um novo aluno no banco

- GET /alunos Lista todos os alunos cadastrados

### 📌 Outras Funcionalidades

- Criação da tabela tb_alunos no MySQL RDS

- Integração entre Flask (EC2) e MySQL (RDS)

- Frontend simples usando Fetch API

- Deploy do frontend como site estático no S3


## 🛠️ Tecnologias utilizadas

### 🐍 Backend

 
- Flask

- Flask-RESTful

- Flask-CORS

- MySQL Connector

- AWS EC2 (execução da API)
  
- AWS RDS (banco MySQL)

### 🎨 Frontend

  

- HTML5

- CSS3

- JavaScript (Fetch API)

- AWS S3 (deploy estático)

## 📦 Como rodar o projeto


1️⃣ Backend (Flask)  

- Configure o app.py com suas credenciais do RDS e execute:

- python app.py

2️⃣ Frontend

- No arquivo script.js, atualize o IP público da instância EC2:

const API_URL = "http://SEU-IP-EC2:5000";

3️⃣ Deploy no AWS S3

- Envie os arquivos HTML, CSS e JS para o bucket

- Ative Static Website Hosting

- Defina index.html como documento principal

4️⃣ Acesso


- Abra a URL pública do bucket para acessar o sistema.





## 👩‍💻 Autora


Feito por
Regiane Melo

