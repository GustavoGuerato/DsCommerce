# DsCommerce

DsCommerce é uma aplicação de e-commerce desenvolvida em Java utilizando o framework Spring Boot. Este projeto serve como base para a criação de uma loja virtual completa, com funcionalidades essenciais como gerenciamento de produtos, carrinho de compras, autenticação de usuários, e muito mais.

## 🚀 Funcionalidades

- Gerenciamento de produtos (CRUD)
- Sistema de autenticação de usuários
- Carrinho de compras
- Finalização de pedidos
- Integração com banco de dados H2 para testes

## 🛠️ Tecnologias Utilizadas

- **Java 17**
- **Spring Boot 3.0**
- **Spring Data JPA**
- **Spring Security**
- **H2 Database**
- **Maven**

## 📦 Estrutura do Projeto

O projeto segue uma estrutura de camadas comum em aplicações Spring Boot:

- **src/main/java**: Código fonte da aplicação.
  - **controller**: Controladores REST que gerenciam as requisições HTTP.
  - **service**: Lógica de negócios da aplicação.
  - **repository**: Interfaces de repositório para acesso ao banco de dados.
  - **model**: Entidades que representam os dados.
- **src/main/resources**: Arquivos de configuração e recursos estáticos.

## ⚙️ Configuração

1. Clone este repositório:
   ```bash
   git clone https://github.com/GustavoGuerato/DsCommerce.git
