Desafio Hyperativa
==================

## Sobre o desafio

### Criação de uma página promocional

Criar uma página web utilizando [Angular](https://angular.io/) realizando a consulta de informações através da API fornecida. A página é dividida em 3 seções: 

#### Seção 01: Destaque

Área de apresentação da promoção.

![Highlight](https://github.com/hyperativa/back-end-jr/blob/master/sections/highlight.jpg)

#### Seção 02: Mecânica

Área com informações da mecânica promocional.

![Infos](https://github.com/hyperativa/back-end-jr/blob/master/sections/information.jpg)

#### Seção 03: FAQ

Área com o FAQ da promoção com o uso de _collapse_ para melhor exibição das respostas.

![Infos](https://github.com/hyperativa/back-end-jr/blob/master/sections/faq.jpg)

#### Requisitos Obrigatórios

* Recriar o layout seguindo as imagens apresentadas.
* Desenvolver a página utilizando [Angular](https://angular.io/) e os conceitos de [SPA](https://en.wikipedia.org/wiki/Single-page_application)
* Todo o conteúdo da página deve ser obtido através da API fornecida.
* Utilizar _id_ promoção (campo da API) como rota na aplicação para a exibição do conteúdo.


#### Requisitos Opcionais (Não necessário)

* Implementar meta tags do site.
* Ter uma cobertura de teste unitários.
* Gerar uma documentação a partir do código fonte.



## Instruções para uso da API

Para o desafio foi disponibilizado um arquivo [JSON](https://github.com/hyperativa/back-end-jr/blob/master/api.json) para simular as respostas da API. Para executar a API siga os seguintes passos:

1. Instalar [Node.js](https://nodejs.org/en/).
2. Garantir que o comando `npm -v` (gerenciador de pacotes) está funcionando corretamente.
3. Instalar o pacote **json-server**.

   `npm install -g json-server`

4. Iniciar o servidor local da API.

    `json-server --port 3000 --watch .\api.json --static ./assets`

5. Acesse a URL http://localhost:3000/promotions e http://localhost:3000/facebook.jpg através do seu navegador para verificar o correto funcionamento da API.

> _Obs.: Garanta que a pasta **assets** (fornecida no projeto) esteja no mesmo caminho que o comando acima foi executado._


## Orientações

* Coloque o código em um repositório GIT.
* Procure fazer um código sucinto e organizado. 
* Siga as instruções descritas nos itens do desafio.
* Faça as suposições e definições que considerar necessário.
* Colocar as orientações de setup e uso no README do seu repositório.

Ao final, você deve entregar uma página semelhante a esta:

![Webpage](https://github.com/hyperativa/back-end-jr/blob/master/sections/entire-page.jpg)

# Boa sorte 







# Hyperativa

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 11.2.11.

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

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
