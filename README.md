# Projeto de Finanças em Java Spring Boot

Este projeto é uma aplicação de gerenciamento financeiro desenvolvida em Java utilizando o framework Spring Boot. O objetivo é permitir que os usuários gerenciem suas receitas, despesas, contas e cartões de forma eficiente.

# Estrutura do Projeto

Este projeto é organizado da seguinte forma:

## Diretório `src/main/java/io.github.emefsilva.finance`

- **api/**: Contém a interface da API.
  - **controller/**: Implementa os controladores que gerenciam as operações.
    - `UserController.java`: Controlador para operações relacionadas a usuários.
    - `IncomeController.java`: Controlador para operações relacionadas a receitas.
    - `ExpenseController.java`: Controlador para operações relacionadas a despesas.
  - **dto/**: Contém os objetos de transferência de dados (DTO).
    - `UserDTO.java`: DTO para transferir dados de usuários.
    - `IncomeDTO.java`: DTO para transferir dados de receitas.
    - `ExpenseDTO.java`: DTO para transferir dados de despesas.

- **service/**: Contém a lógica de negócios.
  - `UserService.java`: Lógica de negócios para usuários.
  - `IncomeService.java`: Lógica de negócios para receitas.
  - `ExpenseService.java`: Lógica de negócios para despesas.

- **model/**: Contém as entidades do domínio.
  - `User.java`: Entidade que representa um usuário.
  - `Income.java`: Entidade que representa uma receita.
  - `Expense.java`: Entidade que representa uma despesa.
  - `Category.java`: Entidade que representa uma categoria.
  - `Account.java`: Entidade que representa uma conta.
  - `Card.java`: Entidade que representa um cartão.

- **repository/**: Contém as interfaces para acesso a dados.
  - `UserRepository.java`: Interface para operações de acesso a usuários.
  - `IncomeRepository.java`: Interface para operações de acesso a receitas.
  - `ExpenseRepository.java`: Interface para operações de acesso a despesas.

- **configuration/**: Contém as configurações da aplicação.
  - `SecurityConfig.java`: Configuração de segurança da aplicação.

## Tecnologias Utilizadas

- **Java**: Linguagem de programação principal.
- **Spring Boot**: Framework para construção de aplicações Java.
- **JPA/Hibernate**: Para interação com o banco de dados.
- **Maven**: Gerenciador de dependências.

## Funcionalidades

- Gerenciamento de usuários.
- Registro de receitas e despesas.
- Classificação de receitas e despesas por categorias.
- Relatórios financeiros.


   

