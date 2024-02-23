# Sistema de Galeria de fotos

O Sistema de Galeria de fotos é uma aplicação web desenvolvida com React, TypeScript e Styled Components que permite aos usuários fazer upload de imagens, que são então armazenadas no Firebase para visualização posterior.

## Funcionalidades

- **Upload de Imagens:** Os usuários podem fazer upload de imagens para a galeria.
  
- **Armazenamento no Firebase:** As imagens são armazenadas no Firebase para acesso e visualização posterior.

## Como Usar

1. Clone este repositório em sua máquina local.
   ```bash
   git clone https://github.com/seu-usuario/sistema-de-galeria-de-Fotos.git
   ```

2. Instale as dependências do projeto.
   ```bash
   cd sistema-de-galeria-de-Fotos
   npm install
   ```

3. Configure o Firebase.
   - Crie um projeto no Firebase (https://console.firebase.google.com/).
   - No console do Firebase, vá para "Authentication" e ative o método de autenticação que deseja usar (por exemplo, e-mail/senha).
   - No console do Firebase, vá para "Storage" e habilite o armazenamento do Firebase.
   - No console do Firebase, vá para "Configurações do projeto" e copie as configurações do SDK do Firebase (apiKey, authDomain, projectId, etc.).
   - Crie um arquivo `.env` na raiz do seu projeto e adicione as configurações do Firebase:

     ```dotenv
     REACT_APP_FIREBASE_API_KEY=apiKey
     REACT_APP_FIREBASE_AUTH_DOMAIN=authDomain
     REACT_APP_FIREBASE_PROJECT_ID=projectId
     REACT_APP_FIREBASE_STORAGE_BUCKET=storageBucket
     REACT_APP_FIREBASE_MESSAGING_SENDER_ID=messagingSenderId
     REACT_APP_FIREBASE_APP_ID=appId
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
