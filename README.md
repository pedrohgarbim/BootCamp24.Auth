## API de autenticação simples desenvolvida em .NET Core. A API permite o registro de novos usuários e o login, gerando um JWT (JSON Web Token) para autenticação em futuras requisições.
## Tecnologias Utilizadas
.NET Core

Entity Framework Core

JWT (JSON Web Token) para autenticação

## Endpoints
### 1. Registro de Usuário
Endpoint: POST para registro de usuário 

Este endpoint permite o registro de um novo usuário no sistema.

Exemplo de Requisição no Postman:
![image](https://github.com/user-attachments/assets/f2e89bd2-4892-4986-ac81-fcfde22ae8fb)

### 2. Login de Usuário
Endpoint: POST para Login de usuário criado 

Este endpoint permite que um usuário registrado faça login no sistema.

Exemplo de Requisição no Postman:
![image](https://github.com/user-attachments/assets/3ba6ebb2-c58d-4477-82a8-30bc54eef37a)

## JWT
O token JWT retornado no login pode ser decodificado usando jwt.io para visualizar as informações contidas no payload.
Ele contém os dados do usuário, como firstName, lastName, email, além de outras informações importantes, como a data de expiração do token.

Entrar em https://jwt.io/ para vizualizar o usuário criado com o token JWT
![image](https://github.com/user-attachments/assets/39487f12-f4d8-4d8f-aa64-cfa09d1c0148)
Token utilazado no exemplo:

https://jwt.io/#debugger-io?token=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJuYW1laWQiOiJjYmZlYTAxZS0zNmE0LTQ5OTMtYjYyOC04YWQ0NzI2MjE4MjciLCJlbWFpbCI6ImZhbWlseWludmljaWJsZUBleC5jb20iLCJnaXZlbl9uYW1lIjoibm9sYW4iLCJmYW1pbHlfbmFtZSI6ImdyYXlzb24iLCJNeUN1c3RvbUNsYWltIjoiTXlDdXN0b21WYWx1ZSIsIm5iZiI6MTcyNDk1NjM3MywiZXhwIjoxNzI1ODIwMzczLCJpYXQiOjE3MjQ5NTYzNzMsImlzcyI6Imh0dHA6Ly9sb2NhbGhvc3Q6NTE5NyJ9.M_sH6lMRxcSJxdGzYxwEW2NFg6ayOUr_PP6Jw7IMbWM



