 # MercadoDAO
## Projeto DAO com Java

Este projeto é uma implementação de um padrão de design DAO (Data Access Object) utilizando Java. O objetivo principal foi demonstrar a separação das responsabilidades no acesso a dados e o uso de boas práticas de desenvolvimento, incluindo a proteção contra SQL Injection e a implementação de uma Factory de Conexão.

---
## Descrição:
---
Este projeto é uma aplicação Java que simula a interação com um banco de dados, utilizando o padrão DAO para separar a lógica de negócio da lógica de acesso aos dados. Além disso, implementamos um mecanismo para prevenir SQL Injection, que é uma das vulnerabilidades mais comuns em sistemas que interagem com bancos de dados.

---
Funcionalidades Implementadas:

DAO: O padrão de design DAO foi utilizado para criar uma camada de abstração entre a lógica de negócios e o banco de dados, permitindo maior flexibilidade e manutenção.

Factory de Conexão: Foi implementada uma Factory de Conexão para centralizar a criação das conexões com o banco de dados, garantindo que as conexões sejam gerenciadas de forma eficiente.

Prevenção de SQL Injection: O código foi escrito de forma a evitar SQL Injection, utilizando consultas preparadas (Prepared Statements) ao invés de concatenar strings diretamente nas consultas SQL.

Estrutura do Projeto
---

<img width="295" height="124" alt="image" src="https://github.com/user-attachments/assets/4df8476f-6783-421a-bc5f-303f3fdd62ac" />



---
O projeto é composto pelas seguintes partes principais:

- Model: Classe que representa as entidades do banco de dados.

- DAO: Interface e classes de implementação responsáveis pela comunicação com o banco de dados.

- Factory de Conexão: Classe responsável pela criação e gerenciamento de conexões com o banco de dados.

- SQL Injection Protection: Utilização de Prepared Statements para garantir a proteção contra ataques de SQL Injection.

Tecnologias Utilizadas

- Java: Linguagem de programação principal para a implementação da lógica.

- JDBC (Java Database Connectivity): Biblioteca usada para conectar o Java ao banco de dados.

- MySQL: Banco de dados utilizado na aplicação.

- Prepared Statements: Técnica para prevenir SQL Injection ao construir consultas SQL de forma segura.

