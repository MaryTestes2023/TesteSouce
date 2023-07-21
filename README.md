[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
# projeto-soucedomo: Cypress + Cucumber + Typescript + BDD

# Índice 

* [Descrição_do_projeto](#Descrição_do_projeto)
* [Funcionalidades](#Funcionalidades)
* [Demonstração](#Demonstração)
* [Tecnologias_utilizadas](#Tecnologias_utilizadas)
* [Autora](#Autora)

# :hammer: Descrição do projeto
Este é um projeto fake na qual eu utilizo o site da soucedemos para demonstrações de algumas funcionalidades.
O intuito deste projeto e facilitar o entendimento de algumas funções do Cypress.
Exemplos básico, usando o Cypress with Cucumber (BDD). This `Gherkin` example includes:
- Basic Scenario
- Scenario Outline
- Tagged tests
- 
# Get started

## Installation
Primeiro precisamos baixar: node.js e o Visual Code. Logo após iremos abrir o Visual Code e iniciar a configuração do arquivo. package.json.
- Abra o visual code, na guia "Terminal". click para a brir o terminal
- Dentro do terminal, vamos crir nossa pasta do projeto, com o seguinte comando: mkdir + nome da pasta e logo após click “Enter”  Ex.: mkdir QA
```bash
mkdir QA
```
- Pasta criada com sucesso, vamos acessar nosso diretório, com o seguinte comando: cd + nome da pasta, Ex.: cd QA e logo após click “Enter”
```bash
cd QA
```
- Vamos abrir nossa pasta dentro do Visual code, com o seguinte comando: code . e logo após click “Enter”
```bash
code .
```
- Vamo crirar nosso package.json, com o seguinte comando: npm init --y
```bash
npm init --y
```
- Pacote criado. dentro do arquivo package.json, insrira informações na linha do script. Onde está: "test": "echo \"Error: no test specified\" && exit 1". troque por: "open": "cypress open"
- Dê um ctrl + S, para salvar as informações.
- Agova vamos iniciar a instalação do Cypress com o seguinte comando: “npm install --save-dev cypress”
```bash
npm install --save-dev cypress
```
- Logo após, dentro do terminal, insira o seguinte comando, para abrir o cypress: “npm run open”
```bash
npm run open
```
<h4 align="left"> 
    😍:  Cypress Instalado  😍:
</h4>

##Setting up Snario Outline

- Dentro da pasta Cypress 2e2 crie um arquivo .feature -> Ex.: login.features
- Dentro da pasta e2e crie uma pasta chamada step_definition e dentro da pasta crie um arquivo .js -> Ex.: login.js
- Não esqueça de configurar o arquivo -< para aceitar os arquivos do tipo: .js e .ts
- Dentro do arquivo login.feature, vamos criar nosso scenario Outline
<h4 align="left"> 
    😍: Dá uma olhadinha nos arquivos do projeto, copia e cola no seu projeto  😍:
</h4>

<h3>Autora: Marília Correia</h3>

<h4 align="center"> 
    :construction:  Projeto em construção  :construction:
</h4>
