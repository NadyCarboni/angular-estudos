## Componentes
- Aplicação angular, assim como react é baseada em componentes reútilizaveis
- Cada parte da aplicação é como um bloco isolado, sem dependeências externas

#### Como é constituído um componente?
- Template html
- Style CSS
- Classe TypeScript

#### Identificando um componente
`import { Component } from '@angular/core'; // import`

```javascript
@Component({
  selector: 'app-root',  // Nome do componente, o que vai ser chamado
  templateUrl: './app.component.html', // HTML
  styleUrls: ['./app.component.scss'] // CSS
})
```

No lugar do templateUrl e do styleUrl, eu posso colocar meu elemento/estilo direto não precisando ser um caminho.

#### Criar um componente via terminal
- `ng generate component "Nome do componente"`

- `ng g component "Nome do componente"`

- `ng g c "Nome do componente"`

- `ng generate c "Nome do componente"`

#### Lembretes
- Não se esqueça de declarar seu compnente
- Não se esqueça de importar/exportar seu componente