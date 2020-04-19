<img alt="GoStack" src="./src/assets/gostack.png" />

<h3 align="center">
   Desafio 06: Banco de dados e upload de arquivos no Node.js
</h3>

<p align="center">“Só deseje as coisas as quais você está disposto a lutar”!</blockquote>

<br>

## :rocket: Sobre o desafio

- Continuação do desenvolvimento da aplicação de gestão de transações, com Node.js junto ao TypeScript, mas dessa vez incluindo o uso de banco de dados (PostgreSQL) com o TypeORM e envio de arquivos com o Multer!
- Uma aplicação que deve armazenar transações financeiras de entrada e saída, que deve permitir o cadastro e a listagem dessas transações, além de permitir a geração de relatórios a partir do envio de um arquivo csv.

- Utilizado Docker com DBeaver para consulta dos dados;

## :checkered_flag: Startando o projeto

PS: ⚠️ Para rodar o projeto é necessário estar utilizando o Docker, criar um banco de dados com o nome gostack_postgres na porta 5432.

1° Clonar: `git clone https://github.com/leopacciulli/Bootcamp-Desafio-Node-BancoORM.git`

2° Rodar o back end:

```sh
$ cd Bootcamp-Desafio-Node-BancoORM
$ yarn dev:server
```

3° Rodar os testes:

PS: ⚠️ Antes de rodar os testes, crie um banco de dados com o nome "gostack_desafio06_tests" para que todos os testes possam executar corretamente.

```sh
$ cd Bootcamp-Desafio-Node-BancoORM
$ yarn test
```
---

Desenvolvido por: [Leonardo Pacciulli](https://www.linkedin.com/in/leonardo-pacciulli-a4b86a92/)
