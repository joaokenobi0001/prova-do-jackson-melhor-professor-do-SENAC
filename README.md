# prova-do-jackson-melhor-professor-do-SENAC


Este projeto é um sistema de gerenciamento de projetos e tarefas em Node.js. Usuários podem criar, visualizar, editar e excluir projetos e tarefas, com cada projeto tendo várias tarefas associadas. O sistema usa JWT para autenticação, Sequelize para ORM, e bcrypt para hash de senhas. O projeto segue uma arquitetura MVC e inclui validações de campos, segurança com middleware de autenticação, e documentação das rotas da API.

UserApi: Define operações de usuário (criação, atualização, exclusão, listagem, login e validação de token) chamando métodos no UserCtrl.

verifyToken: Verifica a presença e validade de um token de autorização na requisição HTTP, permitindo a requisição prosseguir se o token for válido.

Project: Modelo de dados para projetos com campos como id, name, description e createdAt.

Task: Modelo de dados para tarefas com campos como id, title, description, status, createdAt e completionDate.

UserModel: Modelo de dados para usuários com campos como id, nome, email e senha.

Esses componentes gerenciam usuários, projetos e tarefas, mapeando os dados para um banco de dados usando Sequelize.

