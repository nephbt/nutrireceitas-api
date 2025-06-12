🍲 NutriReceitas — API REST

POO com Banco de Dados - PUC Goiás

👨‍💻 Trabalho realizado por:
- 👤 Bruno Teles
- 👤 Rodrigo Gomes


⚙️ **ESPECIFICAÇÕES**
- ☕ Java: 21.0.3
- 🛢️ Banco de dados local: PostgreSQL

🛠 **TECNOLOGIAS**

Este projeto foi construído com as seguintes tecnologias e bibliotecas:

- Java 21 – Linguagem principal do projeto
- Spring Boot 3.5.0 – Framework para aplicações web e back-end modernas
  - spring-boot-starter-web – Criação de APIs RESTful
  - spring-boot-starter-data-jpa – Integração com JPA/Hibernate
  - spring-boot-starter-validation – Validação de dados com Bean Validation
  - spring-boot-starter-test – Frameworks de testes (JUnit, Mockito, etc.)
  - spring-boot-devtools – Ferramentas para desenvolvimento e hot reload
- Lombok – Redução de código repetitivo com anotações como @Getter, @Setter, etc.
- MapStruct 1.6.3 – Mapeamento automático entre DTOs e entidades
- PostgreSQL JDBC 42.7.3 – Driver para integração com banco de dados PostgreSQL
- H2 Database – Banco de dados em memória para testes e desenvolvimento
- Maven – Gerenciador de dependências e build
- Spring Boot Maven Plugin – Empacotamento e execução da aplicação
- Maven Compiler Plugin – Configurado com suporte a processadores de anotação (Lombok e MapStruct)


📲 **CONSUMO DA API**
Você pode utilizar um dos dois métodos abaixo:
- 🔁 Via Postman ou outra API Client (Thunder Client, Insomnia, etc)
- 💻 Via aplicação JavaFX:
[nutrireceitas-consumo (GitHub)](https://github.com/nephbt/nutrireceitas-consumo)

📌 Optando pela segunda opção, siga o passo a passo descrito no [README](https://github.com/nephbt/nutrireceitas-consumo)

🛠️ **CONFIGURANDO O BANCO DE DADOS**
- 🔧 Crie um banco de dados chamado nutrireceitas no PostgreSQL
- 📁 Vá até o arquivo:
  src/main/resources/application.properties
- ✍️ Substitua as seguintes linhas com seu usuário e senha do PostgreSQL:
  - spring.datasource.username=postgres
  - spring.datasource.password=4541

📡 **REQUISIÇÕES HTTP**
- Caso opte por consumir a API via Postman, Thunder Client, ou outro, siga o passo a passo completo em:
  - 📁 src/main/java/com/nutrireceitas/demo/REQUISICOES HTTP
