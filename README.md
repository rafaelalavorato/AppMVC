# AppMVC 

Projeto ASP.NET MVC com Identity para cadastro e gerenciamento de alunos.

## 🧠 Tecnologias utilizadas

- ASP.NET Core MVC
- ASP.NET Identity (autenticação e registro)
- Entity Framework Core (EF Core)
- SQLite (banco de dados)
- Bootstrap 5 (layout e responsividade)

## ✨ Funcionalidades

- Registro de novos usuários com Identity
- Login e logout
- Cadastro de alunos
- Edição de alunos
- Exclusão de alunos
- Listagem de alunos cadastrados
- Validações de formulário (cliente e servidor)

## 🏁 🗃️ Banco de dados
- Este projeto utiliza o SQLite, e o arquivo do banco será criado automaticamente com o nome MinhaAppFuncional.db <br>
  após rodar o dotnet ef database update.

## 🔒 Autenticação
- A autenticação é feita com ASP.NET Identity
- Usuário precisa se registrar antes de acessar as funcionalidades protegidas
- Apenas usuários logados podem cadastrar, editar ou remover alunos

## 📌 Observações
- O e-mail de confirmação está desativado por padrão
- O projeto pode ser expandido facilmente com roles, upload de arquivos, ou dashboard administrativo
