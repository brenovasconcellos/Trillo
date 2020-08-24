<img src="/img/favicon.png" width="50px" height="50px">

# Trillo
Trillo é um site de busca de hotéis moderno onde você encontra o melhor hotel de acordo com o que você deseja.

<img src="/img/prttrillo.jpg">

O projeto foi desenvolvido apenas para front-end através da tecnologias HTML e CSS, **_uma vez que tem como o objetivo mostrar o desenvolvimento de aplicações baseadas no Flexbox._** Deste modo, Trillo foi totalmente baseado nas funcionalidades do Flexbox que demonstra ser uma ótima escolha para desenvolver interfaces em CSS3 com mais versatilidade e facilidade.

# Responsivo
O projeto Trillo foi desenvolvido para ser **responsivo para vários tipos de dispositívos**, ou seja, **o site se adapta totalmente em vários tipos de dispositivo, sendo ele Desktop, Tablets e Celulares**. A responsovidade é um fator importante para o desenvolvimento de uma aplicação, uma vez que é importante a inclusão da aplicação em vários tipos de dispositivos diferentes para os mais variados tipos de usuários 

### Trillo em dispositivo mobile

<img src="/img/mobiletrillo.jpg">

# Sass e npms

**Trillo foi totalmente desenvolvido por Sass** (Syntactically Awesome Style Sheets) que um pré-processador de CSS que nos permite maior dinamismo, produtividade, permitindo escrever linhas de código em CSS utilizando uma sitaxe mais simplificada e contanto como recursos de aninhanmento ao qual não é permitido pelo CSS3. Nota-se que o projeto Trillo ao ser feito por Sass, foi separado em alguns arquivos em que existe um arquivo principal que faz o link entre os demais arquivos com a extensão .scss. Foi utilizado o node-sass que depende do Node.js

Além disso, **Trillo faz uso de pacotes npms**, ou seja, a visualização do projeto depende da instalação do Node.js e das dependentes mostradas no seguinte passo-a-passo.

* npm-run-all;
* live-server;
* node-sass.

Para instalá-las abra o terminal do seu computador, navegue até a pasta do projeto e digite:

```
npm install
```

No arquivo .json do projeto existem 3 tasks, sendo elas:

* watch-sass;
* server;
* start.

Feito os seguintes passos, digite no terminal: 

```
npm run watch:sass
```

Para ter uma melhor experiência do projeto, indico a utilização de Idles para Vs-code como live-server.
