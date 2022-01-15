# API de Evasão Escolar

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/venzel/api-evasao-escolar-nestjs/blob/master/LICENSE)

> **API Evasão Escolar** - Backend desenvolvido com NestJs, TypeOrm e Postgres.<br /> 👉 <a href="http://143.198.112.106:3000/api/" target="_blank"> Link do Swagger da API</a><br />👉 <a href="https://evasaoifpbcg.com.br" target="_blank">Link do projeto</a>

\* O código fonte da aplicação é mantido em um repositório privado.

## Dashboard

<img src="./media/images/dashboard.png" />

## Stack de tecnologias

<p align="left">
  <img src="./media/images/nestjs.svg" alt="NestJs" title="NestJs" width="30" height="30" />
  <img src="https://cdn.worldvectorlogo.com/logos/python-5.svg" alt="Typescript" title="Typescript" width="30" height="30" />  
  <img src="https://cdn.worldvectorlogo.com/logos/typescript.svg" alt="Typescript" title="Typescript" width="30" height="30" />
  <img src="https://cdn.worldvectorlogo.com/logos/logo-javascript.svg" alt="Javascript" title="Javascript" width="30" height="30" />
</p>

-   NestJs
-   Python
-   Typescript
-   TypeORM (Postgres)
-   Autenticação Token JWT

## Persistência

-   Postgres com Docker

## Paths

### Authentication

-   /auth/signup -> Cria um usuário (POST)
-   /auth/signin -> Autenticação de usuário (POST)

### Estudante

-   /students -> Lista todos (GET)
-   /students/filter?curso=computacao&page=1&limit=10 -> Filtra e pagina estudantes (GET)
-   /students/{id} -> Exibe um estudante pelo id (GET)

### Períodos

-   /periods -> Cria período (POST)
-   /periods -> Lista todos os períodos (GET)

### Análises

-   /analysis -> Cria análise (POST)

## Estrutura de pastas

<p align="center"><img src="./media/images/folders-v2.png" width="400" /></p>
