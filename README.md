<img src="/img/favicon.png" width="50px" height="50px">

# Nexter
Nexter é um site no qual pessoas de diferentes lugares podem comprar casas ao redor do mundo.

<img src="/img/nexter.PNG">

O projeto foi desenvolvido apenas no front-end, pois **_tem como objetivo demonstrar a aplicação do grid layout em situações reais de desenvolvimento_**. Sendo assim conta com o uso de diversas propriedades de grid layout disponibilizadas pelo CSS3 a fim de tornar o desenvolvimento do front-end de sites o mais moderno possivel. Abaixo é mostrado um exemplo de aplicação do grid layout para a criação de uma galeria de imagens:

<img src="/img/gallery.PNG">

# Responsividade
Nexter foi **_desenvolvido para ser totalmente responsivo_**, dessa forma, o site **_se adapta à todos os dispositivos e tamanhos de tela_**. Isso foi possivel graças a **_aplição dos recursos repeat(), auto-fit e minmax() disponiveis no grid layout_**. O que acontece é que devido o uso desses recursos a implementação da responsividade torna-se mais fácil, o que também faz com que o **_número de media querries na página seja menor_**, o que resulta em um **_código mais limpo e leve_**.

### Nexter em desktop
<img src="/img/features-desktop.PNG"> 

### Nexter em mobile
<img src="/img/features-mobile.PNG">

# Inicializando o projeto
Nexter **_faz uso de pacotes npm_**, sendo assim, para inicializá-lo corretamente **_você precisará instalar o NodeJS_** na sua máquina. Após a instalação você precisará das seguintes dependências:

* npm-run-all;
* live-server;
* node-sass.

Para instalar todas elas basta abrir o terminal do computador, navegar até a pasta do projeto e digitar:

```
npm install
```

No arquivo .json do projeto existem 3 tasks, sendo elas:

* watch-sass;
* server;
* start.

Se quiser realizar suas próprias modificações, você precisará abrir o terminal, navegar até a pasta do projeto e digitar o seguinte código:

```
npm run start
```

**_Obs: Existe uma quarta task no arquivo .json chamada "prefix", mas ela foi apenas utilizada para criar uma cópia do arquivo final .css, no qual eu rodei a extensão "Autoprefixer" do VScode para adicionar todas as vendors prefixes no código, caso fosse preciso. No momento esse arquivo não está sendo linkado ao html da página._**

Após isso você poderá realizar mudanças no código do projeto, mas muita atenção, **_essas mudanças devem ser feitas nos arquivos .scss_**.

# Sass
Nexter foi **_desenvolvido utilizando HTML5, CSS3, NodeJS e Sass_**. Após realizar o download do repositório será possivel perceber que o pré-processador de CSS conhecido como **_Sass foi utilizado ao longo do desenvolvimento do projeto_**. Nexter teve seu **_código separado em diversos arquivos parciais com o extensão .scss, que foram importados para um arquivo .scss principal, que por sua vez foi compilado para um arquivo .css com a ajuda da dependência node-sass do NodeJS._**
