

```markdown
# FullStackSportify 🎶

Uma **replica do Spotify** desenvolvida como projeto full-stack, utilizando **React** no front-end, **Node.js (Express)** no back-end e **MongoDB** para armazenar os dados. Um projeto moderno e funcional, que simula uma plataforma de streaming de música.

## 🛠 Tecnologias Usadas

- **Front-end:**
  - **React**: Biblioteca JavaScript para construção de interfaces de usuário.
  - **Vite**: Ferramenta de build extremamente rápida para desenvolvimento com React.
  
- **Back-end:**
  - **Node.js**: Ambiente de execução para JavaScript no servidor.
  - **Express**: Framework minimalista para Node.js, facilitando a construção da API.
  - **MongoDB**: Banco de dados NoSQL utilizado para armazenar dados dos usuários e músicas.

- **Autenticação e Armazenamento:**
  - **JWT (JSON Web Tokens)** para autenticação segura de usuários.
  - **Mongoose** para interagir com o MongoDB de maneira simples e eficiente.

## 💻 Funcionalidades

- **Player de Música**: Ouça suas músicas favoritas diretamente no seu navegador.
- **Pesquisa de Músicas e Artistas**: Encontre suas músicas ou artistas preferidos através de uma busca.
- **Criação de Playlists**: Organize suas músicas em playlists personalizadas.
- **Autenticação de Usuário**: Cadastre-se, faça login e gerencie sua conta.
- **Interface Moderninha e Responsiva**: Design clean e atraente, feito com amor para uma experiência de usuário incrível.

## 🚀 Como Rodar o Projeto

### 1. Clonar o Repositório

Clone o repositório para sua máquina local:

```bash
git clone https://github.com/Romeropedro1/fullstacksportify.git
cd fullstacksportify
```

### 2. Instalar as Dependências

Para o **front-end**:

```bash
cd front-end
npm install
```

Para o **back-end**:

```bash
cd back-end
npm install
```

### 3. Configurar o MongoDB

Certifique-se de que você tenha uma instância do **MongoDB** rodando na sua máquina ou use um serviço de MongoDB na nuvem (como o MongoDB Atlas). Atualize as credenciais de conexão no arquivo de configuração do back-end (`back-end/config/database.js`).

Exemplo de configuração:

```js
const mongoose = require('mongoose');

mongoose.connect('mongodb://localhost:27017/sportify', { useNewUrlParser: true, useUnifiedTopology: true })
  .then(() => console.log('Conectado ao MongoDB!'))
  .catch(err => console.log('Erro ao conectar ao MongoDB:', err));
```

### 4. Rodar o Back-end

No diretório do **back-end**, execute:

```bash
npm start
```

Isso iniciará a API na sua máquina local. O servidor vai rodar na porta `5000` por padrão.

### 5. Rodar o Front-end

No diretório do **front-end**, execute:

```bash
npm run dev
```

Isso iniciará o servidor de desenvolvimento do Vite e você poderá acessar a aplicação na URL `http://localhost:3000`.

## 🎨 Design

A interface foi criada com uma estética moderna, com **cores vibrantes**, **tipografia limpa** e **botões animados** para uma navegação intuitiva e divertida. A experiência do usuário foi cuidadosamente planejada para garantir que você se sinta em um serviço de streaming de música de alta qualidade.

## 🔐 Autenticação

Este projeto utiliza **JWT (JSON Web Tokens)** para autenticação de usuários, garantindo a segurança nas requisições feitas ao servidor, como no processo de login e na criação de playlists.

## 🏗 Como Contribuir

Se você quiser contribuir para o projeto, siga as etapas:

1. Fork o repositório.
2. Crie uma nova branch (`git checkout -b feature/nova-funcionalidade`).
3. Faça suas alterações e commit (`git commit -am 'Adicionando nova funcionalidade'`).
4. Envie para o repositório remoto (`git push origin feature/nova-funcionalidade`).
5. Abra um pull request.

## 📑 Licença

Este projeto está sob a licença **MIT**. Veja o arquivo [LICENSE](LICENSE) para mais informações.

---

Feito com ❤️ por Romero Pedro (https://github.com/romeropedro1).

```

