## Pré-requisitos 
- Angular
- Node.js
- Java
- IDE

## Comandos
Ver a versão do Node.js:
>node -v

Realizar o build:
>npm install -g @angular/cli

Ver a versão do Angular:
>ng v

Criar um projeto:
>ng new spaangular --prefix=spa <br>

Would you like to add Angular Routing? Yes <br>
Which stylesheet format would you like to use? CSS

Iniciar o servidor:
>ng serve -o

Gerar um componente:
>ng g c exemplo

## Dica 
O comando `CTRL + K + S` mostra todos os atalhos no Visual Studio Code.

## Entendendo o código
`app-routing.module.ts`: Adicionei das rotas do projeto. <br>
`app.component.html`: Temos o `<router-outlet></router-outlet>` que mostra os componentes. <br>
`app.module.ts`: Importei o `MatToolbarModule`, `MatIconModule`. <br>
`home.component.html`: Apresenta o Toolbar importado do Angular Material. <br>
