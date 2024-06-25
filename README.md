# Notes Web Restful - PTBR

Essa é uma aplicação web que utiliza os conceitos de REST, onde é um 'site' para poder fazer e gerenciar notas e guardar links. 

Dentro das funcionalidades, há a possibilidade de pesquisa, do uso de filtros para organizar as notas entre outras aplicações.

De início o usuário precisa se cadastrar, criando um login para poder acessar sua página. Todos os cadastros de usuários, cadastros de notas e outras ações que usem dados são registrados no banco de dados.

Foram utilizadas tecnologias de criptografia para armazenar dados sensíveis como senhas e tokens de autenticação e diversos outros conceitos e tecnologias que podem ser explorados olhando nos arquivos.

**Desenvolvido com**:
- Node no Backend 
- React no Frontend.


# Notes Web Restful - EN

This is a web application that uses REST concepts, where it is a 'site' for making and managing notes and saving links. 

Its functionalities include the possibility of searching, using filters to organize notes and other applications.

To begin with, the user needs to register, creating a login to access the page. All user registrations, grade registrations and other actions that use data are recorded in the database.

Encryption technologies were used to store sensitive data such as passwords and authentication tokens and various other concepts and technologies can be explored by looking at the files.

**Developed with**:
- Node on the Backend 
- React on the Frontend.


## Project Structure:
To make it easier to upgrade and maintain the code in the future, the REST architecture was adopted:

## Screenshots:
### Back-end
**Auth Middleware**
![Auth_middleware](./img/auth_middleware.png)

Above is an example of the authentication middleware to grant access to specific routes.

**Routes**
![Routes](./img/notes_routes.png)

Above is an example of the application using the authentication middleware to grant access to specific routes.

**Encryption used to save passwords**
![Encryption](./img/user_service.png)

### Database
**User Data**
![User_database](./img/user_database.png)

Above is an example of how it stores User information.

**Tags Data**
![Tags_database](./img/tags_database.png)

Above is an example of how it stores Tags information.

### Front-end
**Login Page**
![login_page](./img/login_page.png)

Above is how the application's home page looks like.

**New User**
![new_user](./img/new_user.png)

Above is how the application's register page looks like.

**Home Page**
![home_page](./img/home_page.png)

Above is how the application's home page after the login looks like.

**Profile Page**
![profile_page](./img/profile_page.png)

Above is how the application's profile edit page looks like.

**Using Filters**
![filter](./img/filter.png)

Above is how the application's filters looks like.

[![portfolio](https://img.shields.io/badge/my_portfolio-000?style=for-the-badge&logo=ko-fi&logoColor=white)](https://github.com/thpgoncalves)
[![linkedin](https://img.shields.io/badge/linkedin-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thiago-pereira-goncalves/)
