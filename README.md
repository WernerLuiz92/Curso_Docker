<h1 align="center">
    <img alt="Docker" src=src="assets/docker-logo.png" height="130px" />
    <br>Curso de Docker - Cod3r<br/>
</h1>

<p align="center">
    <img src="" />
</p>

<p align="center">
    &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;<a href="https://projetos-werner.000webhostapp.com/">CRUD Estoque</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

<p align="center">
    <a href="#bookmark-sobre-o-projeto">Sobre</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#rocket-tecnologias-utilizadas">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#boom-como-executar">Como Executar</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
    <a href="#memo-licença">Licença</a>
</p>

<p align="center">
    <img alt="Home Page" src=".github/HomePage_Screen.png" />
<p>

## Sobre o Projeto

Trata-se de um sistema de CRUD, projetado com o intuíto de por em pratica os conhecimentos adquiridos durante o curso.

A proposta é um sistema de controle de estoque, com controle de usuários e níveis de acesso.

### _Definição de CRUD_

CRUD é uma abreviação das iniciais de **Create**, **Read**, **Update** e **Delete**. Que são as funcionalidades básicas principais de um sistema de software.

Este projeto foi proposto durante o curso _**CRUD Básico com Bootstrap 4 , PHP e MySQL**_, criado pelo professor [Ricardo Milbrath Gonçalves](https://www.udemy.com/course/curso-basico-de-bootstrap-4-php-e-mysql-gratis/).

## Tecnologias Utilizadas

- [PHP 7.4.11](https://www.php.net/)
- [MySQL](https://www.mysql.com/)
- [Bootstrap 4](https://getbootstrap.com/)
- [Fontawesome](https://fontawesome.com/)

## Como Executar o Projeto

- ### _Pré-requisitos_

  - É _**necessário**_ possuir o **[Node.js](https://nodejs.org/en/)** instalado no computador.
  - É _**necessário**_ possuir o **[Git](https://git-scm.com/)** instalado e configurado no computador.
  - Também, é _**preciso**_ ter um gerenciador de pacotes seja o **[Yarn](https://yarnpkg.com/)** ou **[NPM](https://www.npmjs.com/)**.
  - Por fim, é _**essencial**_ ter o **[MySQL](https://www.mysql.com/)** instalado na máquina.

1. Faça um clone do repositório:

```sh
  $ git clone https://github.com/WernerLuiz92/URL_Shortener_Pitu.git
```

2. Executando a Aplicação:

```sh
  # API
  $ cd backend
  # Instalando as dependências do projeto.
  $ npm install # yarn install
  # Inicie a API
  $ npm start # ou yarn start

  # CONEXÃO COM BANCO DE DADOS MYSQL
  # backend > database.ts
  # mysql://<USUARIO>:<SENHA_MY_SQL>@<SUA_URL>:3306/<NOME_DO_BANCO_DE_DADOS>

  # APLICAÇÃO WEB
  $ cd frontend
  # Instalando as dependências do projeto.
  $ yarn install # ou npm install
  # Inicie a aplicação web
  $ yarn start # ou npm start
```

## Licença

Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.<br />

---

<sup>Projeto desenvolvido com a tutoria de [Ricardo Milbrath Gonçalves](https://ricardomilbrath.com.br/), na [Udemy](https://www.udemy.com/user/ricardomilbrathgonalves/).</sup>
