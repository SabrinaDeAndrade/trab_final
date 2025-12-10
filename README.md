# Projeto final

## Integrantes
- **SABRINA DE ANDRADE DOS SANTOS**
- **YAGHO CERUTTI**

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

