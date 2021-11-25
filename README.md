# Construir uma página CRUD com React e uma API externa

O objetivo é criar uma página da web com React e uma API externa para executar operações CRUD . As operações CRUD são
as quatro operações básicas de manipulação de dados, incluindo C reate / C onstruct, R ead, U pdate e D elete.

#Instalação de software

<li>Node.js https://nodejs.org</li>

<p>Crie um Projeto React inicial:</p>
<p>npx create-react-app react-api-externo</p>
<p>cd react-api-externo</p>

<p>IU do material: usaremos os componentes da IU do material.</p>
<p>react-router-dom para gerenciar a rota e o caminho em nossa página</p>

<p>npm install @material-ui/core @material-ui/icons react-router-dom</p>
<p>npm start</p>

#Desenvolvimento

<p>Edite App.js para incluir Router from react -router-dom no aplicativo apenas com os componentes Navbar e Users . (Vamos criar esses 2 componentes).</p>
<p>Crie Navbar.js como um componente da barra de navegação no topo da nossa página Material UI App bar .</p>
<p>Crie Users.js para ser um componente como uma página para exibir a lista de usuários.

<p>Página de criação do usuário</p>
Crie UserCreate.js como uma página para criar um novo usuário.
Tente usar a página de criação de usuário para adicionar um novo usuário.

<p>Página de atualização do Usuário</p>
<p>Crie UserUpdate.js como uma página para editar dados de usuário existentes. O código será semelhante à página User Create com o uso da API de atualização do usuário.</p>

#API

<p>API para criar um usuário (C reate).
URL da API: https://www.mecallapi.com/api/users/create
Método: POST</p>

<p>API para obter uma lista de dados do usuário ( R ead).
URL da API:https://www.mecallapi.com/api/users
Método: GET</p>

<p>API para editar o URL da API do usuário ( U pdate)
:https://www.mecallapi.com/api/users/update
Método: PUT</p>

<p>API para excluir um usuário ( D elete). Esta API exclui apenas usuários recém-adicionados.
URL da API:https://www.mecallapi.com/api/users/delete
Método: DELETE</p>
