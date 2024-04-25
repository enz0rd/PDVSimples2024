<div style='display: flex; justify-content: end; position: absolute; left: 52rem; top: 3.5rem; width: 2rem'><img src='./src/assets/favicon.ico' /></div>


Bem vindo ao

# Repositório do Projeto PDV

Leia a [Documentação](Documentação.md) para mais informações acerca das tecnologias e funcionamento


Para começarmos, tenha o [XAMPP](https://www.apachefriends.org/pt_br/download.html) e o [Node](https://nodejs.org/en/download) instalado. Abra o XAMPP e inicie os serviços de MySQL e Apache. Depois:

- `npm run iniciar`

  <small>Para instalar as dependências, criar a base de dados, rodar as migrações, povoar o banco de dados e iniciar a aplicação</small>

Depois desse comando ser rodado, basta utilizar o comando abaixo para rodar a aplicação novamente:

- `npm start`

Espero que goste!

Changelogs:

- [X] Tela de login e autenticação
- [X] CRUD de Usuários
- [X] CRUD de Produtos
- [X] Envio de vendas
- [X] Listagem de Vendas
- [X] Cancelamento de Vendas (Com dedução de estoque)

Planos futuros

- [ ] Implementação de um módulo de relatórios
