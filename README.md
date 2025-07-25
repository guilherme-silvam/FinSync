# 💼 FinSync – Gerenciador de Reembolsos e Comissões

O **FinSync** é um sistema fullstack moderno e responsivo que permite:
- Cálculo de comissão por vendas
- Controle de reembolsos com upload de comprovantes
- Justificativa para gastos no cartão corporativo
- Cadastro e login de usuários com autenticação JWT
- Interface com tema claro e escuro

---

## 🛠 Tecnologias Utilizadas

- **Frontend:** React + TailwindCSS + Vite
- **Backend:** Node.js + Express + MongoDB
- **Upload de Arquivos:** Cloudinary
- **Autenticação:** JWT (com refresh token)
- **Armazenamento:** MongoDB
- **Design Responsivo:** Sim
- **Tema Dark/Light:** Sim

---

## 🚀 Como Rodar o Projeto

Você pode rodar de **duas formas**:

---

### ✅ Opção 1: Usando Visual Studio Code (sem terminal)

1. Instale o **Visual Studio Code**  
   👉 [https://code.visualstudio.com](https://code.visualstudio.com)

2. Descompacte o arquivo `finsync_project.zip`

3. Abra o VSCode > File > **Open Folder** > selecione a pasta `finsync_project`

---

#### 📦 Rodar o Backend

1. Vá até a pasta `backend`
2. Clique com o botão direito no arquivo `package.json` > `Run NPM install`
3. Após instalar, clique com o botão direito > `Run NPM Script` > `start`

---

#### 💻 Rodar o Frontend

1. Vá até a pasta `frontend`
2. Clique com o botão direito em `package.json` > `Run NPM install`
3. Depois clique com o botão direito > `Run NPM Script` > `dev`

---

#### 🌐 Acesse no navegador

- Frontend: `http://localhost:5173`
- Backend: `http://localhost:5000`

---

### 🌐 Opção 2: Rodar direto no navegador (sem instalar nada)

Você pode usar:
- GitHub para subir o projeto
- Codesandbox para abrir e rodar o código
- MongoDB Atlas para usar um banco de dados na nuvem

Se quiser seguir por esse caminho, me chame que te oriento passo a passo. É possível rodar 100% no navegador.

---

## 👤 Usuário de Teste

Você pode criar uma conta ou usar:

Email: teste@finsync.com
Senha: 123456


---

## 📁 Estrutura de Pastas

finsync_project/
│
├── backend/
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── index.js
│
├── frontend/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── services/
│ │ └── App.jsx
│
└── README.md


---

## ✨ Funcionalidades

- [x] Autenticação segura com JWT e refresh token
- [x] Cadastro de reembolsos com comprovante (imagem no Cloudinary)
- [x] Visualização de lançamentos (comissões, reembolsos, cartões)
- [x] Tema escuro/claro com botão de alternância
- [x] Design responsivo para celular, tablet e desktop

---

## 🧠 Autor

Desenvolvido por **Guilherme Machado**   
[LinkedIn](https://www.linkedin.com/in/guilherme-machado-b26327248/) | [GitHub](https://github.com/guilherme-silvam)

---



