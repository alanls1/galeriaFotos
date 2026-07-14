# Sistema de Galeria de fotos

![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black)
![License: MIT](https://img.shields.io/badge/License-MIT-informational)

O Sistema de Galeria de fotos é uma aplicação web desenvolvida com React, TypeScript e Styled Components que permite aos usuários fazer upload de imagens, que são então armazenadas no Firebase para visualização posterior.

## Funcionalidades

- **Upload de Imagens:** Os usuários podem fazer upload de imagens para a galeria.
  
- **Armazenamento no Firebase:** As imagens são armazenadas no Firebase para acesso e visualização posterior.

## Como Usar

1. Clone este repositório em sua máquina local.
   ```bash
   git clone https://github.com/alanls1/galeriaFotos.git
   ```

2. Instale as dependências do projeto.
   ```bash
   cd galeriaFotos
   npm install
   ```

3. Configure o Firebase.
   - Crie um projeto no Firebase (https://console.firebase.google.com/).
   - No console do Firebase, vá para "Authentication" e ative o método de autenticação que deseja usar (por exemplo, e-mail/senha).
   - No console do Firebase, vá para "Storage" e habilite o armazenamento do Firebase.
   - No console do Firebase, vá para "Configurações do projeto" e copie as configurações do SDK do Firebase (apiKey, authDomain, projectId, etc.).
   - Copie `.env.example` para `.env` **na raiz do projeto** (o Create React App só lê variáveis de um `.env` na raiz, não dentro de `src/`) e preencha com as configurações do Firebase:

     ```dotenv
     REACT_APP_FIREBASE_APIKEY=apiKey
     REACT_APP_FIREBASE_AUTHDOMAIN=authDomain
     REACT_APP_FIREBASE_PROJECTID=projectId
     REACT_APP_FIREBASE_STORAGEBUCKET=storageBucket
     REACT_APP_MESSAGINGSENDERID=messagingSenderId
     REACT_APP_FIREBASE_APPID=appId
     ```

4. Execute a aplicação em modo de desenvolvimento.
   ```bash
   npm start
   ```

5. Acesse a aplicação em seu navegador.
   ```
   http://localhost:3000
   ```

6. Comece a usar o Sistema de Galeria de fotos, fazendo upload de imagens.

## Contribuição

Se você deseja contribuir com melhorias para o Sistema de Galeria de Fotos, fique à vontade para abrir uma issue ou enviar um pull request.
