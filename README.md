# IgniteTodoManager

*Don't know portuguese? No worries, i've got you! Just click [here]() and go the the english version* 

<!-- Badges -->
![GitHub top language](https://img.shields.io/github/languages/top/gabrielloppes/IgniteTodoManager?style=for-the-badge)
![GitHub language count](https://img.shields.io/github/languages/count/gabrielloppes/IgniteTodoManager?style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/gabrielloppes/IgniteTodoManager?style=for-the-badge)
[![GitHub license](https://img.shields.io/github/license/gabrielloppes/IgniteTodoManager?style=for-the-badge)](https://github.com/gabrielloppes/IgniteTodoManager)
<!-- ts -->
## Tabela de conteúdos
* [Sobre](#sobre)
* [Funcionalidades](#funcionalidades)
  * [Testes HTTP](#testes-http)
* [Tecnologias Utilizadas](#tecnologias-utilizadas)
* [Como Usar](#como-usar)
  * [Pré-requisitos](#pré-requisitos)
  * [Clonar o repositório](#clonar-o-repositório)
  * [Rodando a aplicação](#rodando-a-aplicação)
* [Testes](#testes)
  * [Suíte de testes](#suíte-de-testes)
<!-- te -->

## Sobre
IgniteTodoManager é a primeira aplicação em NodeJS no bootcampo [Ignite](https://www.rocketseat.com.br/ignite) da [Rocketseat](https://www.rocketseat.com.br), essa aplicação tem como objetivo, fazer uma introdução ao mundo do [NodeJS](https://nodejs.org/en/) e suas possibilidades

## Funcionalidades
- [x] Cadastro de um novo usuário
- [x] Listar os TODO's de um usuário
- [x] Criar um novo TODO
- [x] Alterar uma tarefa
- [x] Marcar uma tarefa como feita
- [x] Deletar uma tarefa

* ## Testes HTTP
  Para testar as requisições HTTP, utilize [esse](arquivoJSON) arquivo JSON, importe no seu [Insomnia](https://insomnia.rest/download), [Postman](https://www.postman.com/) ou em seu cliente HTTP favorito
## Tecnologias Utilizadas
Neste projeto foram utilizadas as seguintes tecnologias

| NodeJS | Express | Jest | SuperTest |
|--------|---------|------|-----------|

## Como Usar
* ## Pré-requisitos
  Para rodar esse projeto voê deverá ter o [NodeJS](https://nodejs.org/en/) instalado em sua máquina
* ## Clonar o repositório
  Para clonar o repositório em sua máquina, utilize um dos seguintes comando

  Via HTTP
  ```bash
  https://github.com/gabrielloppes/IgniteTodoManager.git
  ```

  Via SSH
  ```bash
  git@github.com:gabrielloppes/IgniteTodoManager.git
  ```

  Via GitHub CLI
  ```bash
  gh repo clone gabrielloppes/IgniteTodoManager
  ```
* ## Rodando a aplicação
  Após clonar o repositório, entre no diretório da aplicação
  ```bash
  cd IgniteTodoManager
  ```
  Após entrar no diretório da aplicação, rode o comando para instalar as dependências necessárias
  ```bash
  yarn
  ```
  Após ter instalado as dependências, suba a aplicação rodando o seguinte comando
  ```bash
  yarn dev
  ```

## Testes
Para rodas os testes, abra o seu terminal ou use o terminal integrado do seu editor de código e insira o comando
```bash
yarn test
```

Caso você queira ver os testes com mais detalhes insira o seguinte comando no seu terminal:
```bash
yarn test --verbose
```
* ## Suíte de teste
  <details>
    <summary>Todos</summary>
    
    :heavy_check_mark: should be able to list all user's todo

    :heavy_check_mark: should be able to create a new todo

    :heavy_check_mark: should be able to update a todo

    :heavy_check_mark: should not be able to update a non existing todo

    :heavy_check_mark: should be able to mark a todo as done

    :heavy_check_mark: should not be able to mark a non existing todo as done

    :heavy_check_mark: should be able to delete a todo

    :heavy_check_mark: should not be able to delete a non existing todo
  </details>
