# 📌 Gerenciador de Tarefas - API em ASP.NET Core

Este é um projeto de uma API RESTful para gerenciamento de tarefas (To‑Do List), desenvolvido com C# e ASP.NET Core. Ele tem como principal objetivo consolidar conhecimentos em arquitetura de software, autenticação, segurança e testes automatizados.

No futuro, também está prevista a criação de uma interface front-end utilizando Angular.

---

## 🎯 Objetivos do Projeto

- Aplicar conceitos de **arquitetura de software** (camadas, SOLID, Clean Architecture)
- Melhorar o domínio de **ASP.NET Core** e **Entity Framework Core**
- Aprender e aplicar práticas de **autenticação e segurança**
- Implementar **testes automatizados** (unitários e de integração)
- Criar uma base sólida para um **front-end com Angular** futuramente

---

## 🛠️ Tecnologias e Ferramentas

- **Linguagem**: C#
- **Framework**: ASP.NET Core
- **Banco de Dados**: SQLite (ou SQL Server)
- **ORM**: Entity Framework Core
- **Mapeamento de Objetos**: AutoMapper
- **Autenticação**: JWT (JSON Web Token)
- **Testes**: xUnit ou NUnit
- **Documentação da API**: Swagger
- **Versionamento de Código**: Git + GitHub
- **Editor**: Visual Studio 2022 ou superior

---

## 📁 Estrutura Planejada do Projeto

/src
    ├── Application # Casos de uso e lógica da aplicação
    ├── Domain # Entidades e interfaces
    ├── Infrastructure # Acesso a dados e serviços externos
    ├── WebAPI # Camada de apresentação (controllers, middlewares)
/tests
    ├── UnitTests # Testes unitários
    ├── IntegrationTests # Testes de integração


---

## 🔐 Funcionalidades Previstas

- [ ] Cadastro e autenticação de usuários
- [ ] Criação, edição e exclusão de tarefas
- [ ] Organização das tarefas por status (pendente, em andamento, concluída)
- [ ] Filtro de tarefas por usuário
- [ ] Segurança com JWT
- [ ] Documentação da API com Swagger
- [ ] Testes unitários e de integração

---

## 🚧 Status do Projeto

🟡 Em desenvolvimento

---

## 📌 Como Executar

> Pré-requisitos:
> - .NET SDK 6.0 ou superior
> - Visual Studio ou VS Code
> - Banco de dados configurado (SQLite ou SQL Server)

```bash
# Clone o repositório
git clone https://github.com/seu-usuario/seu-repositorio.git

# Acesse o diretório do projeto
cd seu-repositorio

# Restaure as dependências
dotnet restore

# Execute a aplicação
dotnet run --project src/WebAPI
