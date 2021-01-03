<h1 align="center">
    <img alt="Docker" src="assets/docker-logo.png" height="130px" />
    <br>📚 🐳 Curso de Docker 🐳 📚<br/>
</h1>

<p align="center">
    &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;<a href="https://www.cod3r.com.br/courses/docker">cod3r.com.br</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
</p>

## Sobre o Curso

...

### O que Aprendemos

...

<p align="center">
    <img src="assets/tela-docker.jpg" />
</p>


## Etapas

- 1. Introdução
- 2. Conceitos
- 3. Instalação
- 4. Uso básico do Docker
- 5. Deixando de ser apenas um usuário
- 6. Redes
- 7. Coordenando múltiplos containers
- 8. Projeto cadastro simples (CRUD)
- 9. Projeto de envio de emails com Workers

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
