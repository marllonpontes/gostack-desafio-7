<div align="center">
  <img alt="GoStack"
    src="https://storage.googleapis.com/golden-wind/bootcamp-gostack/header-desafios.png"
  />
</div>

<h2 align="center">
  Desafio 07: GoFinances Web
</h2>

<p align="center">
  <img alt="language version" src="https://img.shields.io/badge/React-v_16.13.1-339933?logo=react">
  <img alt="language version" src="https://img.shields.io/badge/Yarn-v_1.22.4-2C8EBB?logo=Yarn">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/marllonpontes/gostack-desafio-7">

</p>

<hr/>

<p align="center">
  <a href="#rocket-sobre-o-desafio">Sobre o desafio</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#🔥-funcionalidades">Funcionalidades</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#⚙️-tecnologias">Tecnologias</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#⛏-ferramentas">Ferramentas</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#computer-execute-o-projeto">Execute o projeto</a>
</p>

## :rocket: Sobre o desafio

Nesse desafio, você deve continuar desenvolvendo a aplicação de gestão de transações, a GoFinances. Agora você irá praticar o que você aprendeu até agora no React.js junto com TypeScript, utilizando rotas e envio de arquivos por formulário.

Essa será uma aplicação que irá se conectar ao seu backend do [Desafio 06](https://github.com/marllonṕontes/gostack-desafio-6), e exibir as transações criadas e permitir a importação de um arquivo CSV para gerar novos registros no banco de dados.
## 🔥 Funcionalidades

Neste projeto, as rotas foram implementadas usando métodos HTTP:
- **`Listar as transações da sua API`**: Sua página `Dashboard` deve ser capaz de exibir uma listagem através de uma tabela, com o campo `title`, `value`, `type` e `category` de todas as transações que estão cadastradas na sua API.
- **`Exibir o balance da sua API`**: Sua página `Dashboard`, você deve exibir o balance que é retornado do seu backend, contendo o total geral, junto ao total de entradas e saídas.
- **`Importar arquivos CSV`**: Na sua página `Import`, você deve permitir o envio de um arquivo no formato `csv` para o seu backend, que irá fazer a importação das transações para o seu banco de dados. O arquivo csv deve seguir o seguinte [modelo](https://github.com/marllon/gostack-desafio-6/blob/master/src/__tests__/import_template.csv).


## ⚙️ Tecnologias

* __ReactJS__
* Yarn
* Jest

## :computer: Execute o projeto

Clone este repositório:

```bash
$ git clone https://github.com/marllonpontes/gostack-desafio-7
```

Mova-se para diretório da aplicação:

```bash
$ cd gostack-desafio-7
```

Para instalar as dependências execute:

```bash
yarn install
```

E para iniciar a aplicação:

```bash
yarn start
```
