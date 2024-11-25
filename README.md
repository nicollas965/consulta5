https://acadcruzeirodosul-my.sharepoint.com/my

dotnet add package Swashbuckle.AspNetCore --version 6.5.0

dotnet new sln -n API

dotnet sln API.sln add API.csproj

1. Implementação do Frontend com React
Primeiro, crie o frontend em React para interagir com os controllers no backend.

Passos para configurar o React:
Instale o create-react-app se necessário (se ainda não tiver o create-react-app instalado):

npm install -g create-react-app

Crie um novo projeto React:

npx create-react-app frontend
cd frontend

Instale as dependências para fazer requisições HTTP:

npm install axios

Estrutura de pastas do frontend
A estrutura básica do projeto React será:

frontend/
├── src/
│   ├── components/
│   │   ├── CategoriaList.js
│   │   ├── TarefaList.js
│   ├── App.js
│   ├── axios.js
└── public/

npm install react-router-dom
