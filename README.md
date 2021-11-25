# Construir uma página CRUD com React e uma API externa

O objetivo é criar uma página da web com React e uma API externa para executar operações <b>CRUD</b>. As operações CRUD são
as quatro operações básicas de manipulação de dados, incluindo <b>C</b>reate / <b>C</b>onstruct, <b>R</b>ead, <b>U</b>pdate e <b>D</b>elete.

# Instalação de software

<li>Node.js https://nodejs.org</li>
<br>

<p>Crie um Projeto React inicial:</p>
<p>npx create-react-app react-api-externo</p>
<p>cd react-api-externo</p>

<br>
<p><b>IU do material:</b> usaremos os componentes da IU do material.</p>
<p>react-router-dom para gerenciar a rota e o caminho em nossa página</p>
<br>

<p>npm install @material-ui/core @material-ui/icons react-router-dom</p>
<p>npm start</p>

# Desenvolvimento

<p>Edite <b>App.js</b> para incluir Router from react -router-dom no aplicativo apenas com os componentes Navbar e Users.</p>
<p>Crie <b>Navbar.js</b> como um componente da barra de navegação no topo da nossa página Material UI App bar.</p>
<p>Crie <b>Users.js</b> para ser um componente como uma página para exibir a lista de usuários.</p>

<br>

<p><b>Página de criação do usuário</b></p>
Crie <b>UserCreate.js</b> como uma página para criar um novo usuário.
Tente usar a página de criação de usuário para adicionar um novo usuário.
<br>

<p><b>Página de atualização do Usuário</b></p>
<p>Crie <b>UserUpdate.js</b> como uma página para editar dados de usuário existentes. O código será semelhante à página User Create com o uso da API de atualização do usuário.</p>

# API

<p>API para criar um usuário (<b>C</b>reate).</p>
<p>URL da API: https://www.mecallapi.com/api/users/create</p>
<p>Método: POST</p>
<br>

<p>API para obter uma lista de dados do usuário (<b>R</b>ead).</p>
<p>URL da API: https://www.mecallapi.com/api/users</p>
<p>Método: GET</p>
<br>

<p>API para editar o URL da API do usuário (<b>U</b>pdate)</p>
<p>URL da API: https://www.mecallapi.com/api/users/update</p>
<p>Método: PUT</p>
<br>

<p>API para excluir um usuário (<b>D</b>elete). Esta API exclui apenas usuários recém-adicionados.</p>
<p>URL da API: https://www.mecallapi.com/api/users/delete</p>
<p>Método: DELETE</p>
