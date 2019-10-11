# Motivação
Este projeto criado como estudo de caso para realizar uma prova de conceito, onde em um cliente foi solicitado que de acordo com a classificação de setor do operador que se logar deverá ser alterado as cores do tema. Para simular esse desafio será adicionado no service um random que deverá aleatóriamente selecionar um tema a cada vez que a tela carregar. No sistema de verdade isso será de responsabilidade da API que deverá retornar nos dados do operador o setor, para que então  a UI montada de acordo com essas implementações altere o tema dinamicamente.

Então mãos a obra ;)

# Montagem do ambiente

Caso esteja iniciando os estudos no angular siga os passos na ordem.

1. Abra o terminal (Terminal, Prompt-DOS, Node-Prompt, GitBash, Windows-Terminal, etc...) e acesse uma pasta de sua preferência.
2. $ git clone https://github.com/atrombetone/material-theme.git
3. cd material-theme
4. npm install
5. ng serve --open
6. Após o comando acima completar o processo o navegador deverá ser aberto automáticamente, caso não ocorra isso acesse seu navegador prefêrido e acesse a url http://localhost:4200

# MaterialTheme

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.3.2.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
