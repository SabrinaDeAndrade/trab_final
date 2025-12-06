# Projeto da Equipe TAG2

## Integrantes
- **SABRINA DE ANDRADE DOS SANTOS**
- **YAGHO CERUTTI**

---

## 📌 Sobre o Projeto
Este projeto consiste em uma aplicação web que implementa uma loja virtual simples, seguindo os requisitos solicitados na disciplina.  
A aplicação foi desenvolvida utilizando **HTML, CSS, JavaScript puro**, com **Node.js opcional** para servir os dados via API (sem banco de dados, utilizando arquivos JSON).

---

## 🧩 Funcionalidades
- Exibição dinâmica de 30 produtos.
- Cada produto possui:
  - id  
  - nome  
  - quantidade  
  - categoria  
  - preço  
  - imagem  
- Filtro por categoria
- Barra de pesquisa
- Carrinho com:
  - verificação de estoque  
  - impedir adicionar sem estoque  
  - manter o estoque real (não resetar)
- Layout simples e funcional.

---

## 📁 Estrutura do Projeto

/projeto
|-- /frontend
| |-- index.html
| |-- css.css
| |-- script.js
|
|-- /backend
| |-- server.js (caso use Node.js)
| |-- produtos.json
|
|-- README.md
|-- requirements.txt (se usar Python)
|-- package.json (se usar Node.js)

yaml
Copiar código

---

# ▶️ **Como Executar o Projeto**

## 🔹 **Opção 1 — Usando apenas Frontend (sem backend)**  
Basta abrir o arquivo:

frontend/index.html

yaml
Copiar código

em qualquer navegador.

---

## 🔹 **Opção 2 — Usando Node.js (Recomendado)**

### 1. Instalar dependências
No terminal, dentro da pasta do projeto:

npm install

shell
Copiar código

### 2. Executar a API
node backend/server.js

css
Copiar código

A API ficará disponível em:

http://localhost:3000/produtos

shell
Copiar código

### 3. Abrir o site
Abra o arquivo:

frontend/index.html

yaml
Copiar código

---

## 🧪 Testes
- Teste os filtros
- Adicione itens ao carrinho
- Verifique estoque diminuindo corretamente
- Finalize a compra
- Tente adicionar um produto sem estoque (deve bloquear)

---

## 📌 Observações
- Nenhum framework JS foi utilizado.
- Node.js foi usado apenas para servir a API, conforme permitido.
- Não há banco de dados — os dados vêm de `produtos.json`.

---

# 📄 **requirements.txt (caso use Python)**  
*(Se você não usou Python, pode ignorar este arquivo.)*

flask

yaml
Copiar código

---

# 📦 **package.json (caso use Node.js)**

{
"name": "loja-ursinhos",
"version": "1.0.0",
"description": "Loja virtual simples desenvolvida pela equipe TAG2",
"main": "backend/server.js",
"scripts": {
"start": "node backend/server.js"
},
"dependencies": {
"express": "^4.18.2",
"cors": "^2.8.5"
}
}

yaml
Copiar código

---

# 🚀 **Pronto!**
