#🎮 dslist 🎮 

O dslist é um projeto que organiza títulos de jogos em listas para os usuários.  
Este projeto foi desenvolvido para treinar o conhecimento e as boas práticas no uso de Spring Boot com JPA e Hibernate.

---

## Modelo de Domínio
O modelo de domínio define a estrutura dos dados, como os jogos e suas listas de categorias.  
![image](https://github.com/user-attachments/assets/feaddbcf-2cff-4798-bade-b11be773d32c)


---

## Padrão em Camadas  
A arquitetura do dslist segue o padrão de camadas, facilitando a manutenção e escalabilidade do sistema.  
- **Controller** 🎛️: Interface entre o usuário e o sistema.
- **Service** ⚙️: Contém a lógica do projeto.  
- **Repository** 🗄️: Acesso aos dados no banco, podendo ser personalizado.

![image](https://github.com/user-attachments/assets/f854669c-ced2-47ae-92b1-95cdb6fa1ec6)

---

## Tecnologias Utilizadas  

### Backend  
- ![Java](https://img.shields.io/badge/Java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white)  
  **Descrição**: Linguagem de programação principal utilizada no desenvolvimento do backend.  
- ![Spring](https://img.shields.io/badge/Spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white)  
  **Descrição**: Framework que facilita o desenvolvimento de aplicações Java, com suporte para APIs RESTful e injeção de dependências.  
- ![Hibernate](https://img.shields.io/badge/Hibernate-59666C?style=for-the-badge&logo=Hibernate&logoColor=white)  
  **Descrição**: Framework de mapeamento objeto-relacional (ORM) para facilitar o acesso e manipulação de dados no banco de dados.  
- ![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=Postman&logoColor=white)  
  **Descrição**: Ferramenta para testar e documentar APIs REST, garantindo a qualidade das requisições e respostas.

### Banco de Dados  
- **H2 (Ambiente de Teste)**  
  **Descrição**: Banco de dados leve e embutido, utilizado para simulações e testes locais.  
- ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)  
  **Descrição**: Banco de dados relacional utilizado em ambiente de produção, garantindo alta performance e robustez.  
- ![Docker](https://img.shields.io/badge/Docker-2CA5E0?style=for-the-badge&logo=docker&logoColor=white)  
  **Descrição**: Ferramenta para gerenciamento de contêineres, usada para facilitar o deploy do banco de dados PostgreSQL e outros serviços do sistema.  

### Links Úteis  
- [Java](https://www.oracle.com/java/)  
- [Spring](https://spring.io/)  
- [Hibernate](https://hibernate.org/)  
- [Postman](https://www.postman.com/)  
- [PostgreSQL](https://www.postgresql.org/)  
- [Docker](https://www.docker.com/)  


---

## 🚀 Como Clonar o Repositório  
Para clonar o repositório, basta rodar o comando abaixo:

```bash
git clone https://github.com/dev-aguiar/dslist.git
```
