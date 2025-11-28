# 🧙‍♀️ Cadastro de Alunos - Projeto Full Stack com AWS


![Magic Badge](https://img.shields.io/badge/✨%20Projeto%20com%20AWS-%F0%9F%8E%AD-darkred)
![Status Badge](https://img.shields.io/badge/Status-Deploy%20desativado%20%7C%20Prática%20acadêmica-8B0000?style=flat-square)

> 🪶 **Observação:** Este projeto teve seu **deploy realizado apenas para fins de prática** durante a trilha **Santander Imersão Digital**.  
> Os serviços na AWS estão **desativados temporariamente** devido aos custos de hospedagem.  
> 🔮 Todo o código e a estrutura do sistema permanecem disponíveis neste repositório para estudo e consulta.

--- 
## ✨ Sobre o Projeto
Este projeto foi desenvolvido como parte da **Trilha DevOps** do programa **Santander Imersão Digital** em parceria com **Alura** e **FIAP**.
A aplicação tem como objetivo realizar o **cadastro e visualização de alunos** por meio de um **backend em Python (Flask)** integrado a um **banco de dados MySQL hospedado na AWS RDS**, e um **frontend hospedado no S3**.

Para personalizar a experiência, o frontend foi completamente **estilizado com um tema inspirado na Escola de Magia de Hogwarts**, utilizando **CSS puro** com efeitos dourados, sombreamento e atmosfera mística.

---

## 🪄 Demonstração

📸 **Tela inicial:**
Exibe o formulário de cadastro de alunos com o tema de Hogwarts, incluindo elementos visuais inspirados no universo de Harry Potter.
<img src="https://i.imgur.com/kAwkWtI.png" alt="Prévia do Cadastro de Alunos" width="600">

🧾 **Envio do formulário:**
Demonstra a interação do usuário ao preencher e submeter o cadastro, exibindo o processo concluído com sucesso.

<img src="https://i.imgur.com/hkir1J2.gif" alt="Cadastro efetuado com sucesso" width="600">

--- 

## ⚙️ Tecnologias Utilizadas

 ☁️ **Backend**
- **AWS EC2** — Hospedagem da API Flask
- **AWS RDS (MySQL)** — Banco de dados relacional
- **Flask e Flask-RESTful** — Criação da API REST
- **Flask-CORS** — Liberação de comunicação com o frontend
- **MySQL Connector** — Conexão entre a aplicação e o banco

🪄 **Frontend**
- **HTML5**
- **CSS3 (customizado com tema mágico)**
- **JavaScript (Fetch API)**
- **AWS S3** — Hospedagem estática

 🧰 **Ferramentas auxiliares**
- **Git / GitHub** — Versionamento do código
- **MySQL Workbench** — Criação e manipulação do banco
- **Amazon Console** — Gerenciamento dos serviços em nuvem

---

## ✨ O que foi feito
1. **Criação do banco de dados MySQL** no Amazon RDS, com tabela `tb_alunos` para armazenar as informações de alunos.

2. **Configuração do backend** em uma instância EC2 executando um servidor Flask para as rotas `/cadastro` (POST) e `/alunos (GET)`.

3. **Integração entre backend e banco** para permitir inserção e consulta dos cadastros via API.

4. **Customização completa do frontend**, com:

- Layout temático da Escola de Magia de Hogwarts 🪄
- Fundo com imagem e gradiente dourado escuro
- Inputs e botões estilizados com bordas e brilhos mágicos
- Uso de `box-shadow`, `text-shadow` e `linear-gradient` para criar efeitos luminosos

5. **Deploy do frontend no AWS S3**, configurado como site estático e vinculado ao backend via IP público da instância EC2.

---

## 🚀 Como Executar
1. Configure o banco de dados MySQL no RDS conforme o tutorial.
2. Suba a instância EC2 e edite o arquivo app.py com as credenciais do seu banco.
3. Execute o backend:

```bash
python app.py
```
4. Edite o `script.js` do frontend e substitua o IP pelo IP público da sua EC2.
5. Faça upload dos arquivos para o **AWS S3** e habilite a hospedagem de site estático.
6. Acesse a URL pública do bucket e teste o cadastro de alunos.

---
##  Autora
Feito com ❤️ por [Jezebel Guedes](https://www.linkedin.com/in/jezebel-guedes/) 👋Vamos nos conectar!
