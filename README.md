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

## Conteúdo bônus
### Interpolação: {{ valor }}
Associa informação do componente para o template (HTML).

### Property Binding: [propriedade]="valor"
Associa informação do componente para o template (HTML).

### Event Binding: (evento)="handler"
Associa informação do template (HTML) para o componente.

### Two-Way Data Binding: [(ngModel)]="propriedade"
Associa informação entre ambos, ou seja, mantém ambos atualizados (componente e template (HTML)).

## Diretivas: ngIf / ngFor
ngIf: Adiciona um elemento na marcação, geralmente um elemento de contâiner como um div. 
ngFor: Processa cada item de um objeto iterável, gerando uma marcação para cada um. Ela é conhecida como uma diretiva estrutural porque pode alterar o layout do DOM adicionando e removendo elementos DOM de visualização. 

## Event Emitter
Input Property - @Input(): Você irá utilizá-lo quando quiser receber dados de um componente pai.
Output Property - @Output(): Você irá utilizá-lo quando quiser enviar dados de um componente filho para um componente pai.

## Observable
É uma coleção que funciona de forma unidirecional, ou seja, ele emite notificações sempre que ocorre uma mudança em um de seus itens e a partir disso podemos executar uma ação. 

## Life Cycle hooks
Cada componente do Angular possui um conjunto de Eventos de Ciclo de Vida, eles ocorrem quando o componente é criado, renderizado, tem o valor de suas propriedades alteradas, ou quando ele é destruído. Quando um desses eventos é chamado, o Angular invoca uma série de métodos que são executados imediatamente. Um exemplo de seu uso pode ser aplicado em um site de compras, onde conseguiríamos agir de acordo com cada mudança feita pelo usuário, ao adicionar um item no carrinho.

## Constructor
Constrói tudo que precisa antes de iniciar um componente. 

## NgOnInit 
É chamado toda vez que inicia um componente, facilitando a chamada de métodos que precisamos que sejam executados assim que o componente for chamado.
