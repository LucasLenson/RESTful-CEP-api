### Explorando Padrões de Projetos na Prática com Java

Java RESTful API criada para para explorar as implementações dos padrões de projeto usando o Spring Framework, são eles:
- Singleton
- Strategy/Repository
- Facade

 Esta API é projetada para simplificar o gerenciamento de clientes e seus endereços, integrando-se com o serviço externo [ViaCEP](https://viacep.com.br) para garantir que os dados de endereço sejam precisos e atualizados. Ela demonstra boas práticas de separação de responsabilidades e uso de padrões de projeto como injeção de dependência e reaproveitamento de código através de interfaces e implementações.

### Principais Tecnologias
 - **Java 22**: Utilizaremos a versão 22 do Java
 - **Spring Boot 3.2.5**: Para maximizar a produtividade por meio de sua  premissa de autoconfiguração
 - **Spring Data JPA**: Para simplificar nossa camada de acesso aos dados, facilitando a integração com bancos de dados SQL
 - **OpenAPI (Swagger)**: Para criar uma documentação de API eficaz e fácil de entender usando a OpenAPI (Swagger)
 - **H2 Database**: Para persistir os dados em um banco de testes e facilitar a produção
  
