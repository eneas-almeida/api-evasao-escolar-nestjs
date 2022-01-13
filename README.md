# API de Evasão Escolar

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/venzel/api-evasao-escolar-nestjs/blob/master/LICENSE)

> **API Evasão Escolar** - Backend desenvolvido com NestJs, Prisma e Postgres.<br /> 👉 <a href="http://143.198.112.106:3000/api/" target="_blank"> Link do Swagger da API</a><br />👉 <a href="https://evasaoifpbcg.com.br" target="_blank">Link do projeto</a>

\* O código fonte da aplicação é mantido em um repositório privado.

## Stack de tecnologias

<p align="left">
  <img src="./media/images/nestjs.svg" alt="NestJs" title="NestJs" width="30" height="30" />
  <img src="https://cdn.worldvectorlogo.com/logos/python-5.svg" alt="Typescript" title="Typescript" width="30" height="30" />  
  <img src="https://cdn.worldvectorlogo.com/logos/typescript.svg" alt="Typescript" title="Typescript" width="30" height="30" />
  <img src="https://cdn.worldvectorlogo.com/logos/logo-javascript.svg" alt="Javascript" title="Javascript" width="30" height="30" />
  <img src="https://cdn.worldvectorlogo.com/logos/prisma-4.svg" alt="Prisma" title="Prisma" width="30" height="30" />
</p>

-   NestJs
-   Python
-   Typescript
-   Prisma
-   Autenticação Token JWT

## Persistência

-   Postgres com Docker

## Paths

### Authentication

-   /auth/signup -> Cria um usuário (POST)
-   /auth/signin -> Autenticação de usuário (POST)

### Estudante

-   /students -> Lista todos (GET)
-   /students/page?first=10 -> Lista paginados (GET)
-   /students/{id} -> Exibe um estudante pelo id (GET)

### Períodos

-   /periods -> Lista todos os períodos (GET)

## Estrutura de pastas

<p align="center"><img src="./media/images/folders.png" width="400" /></p>
