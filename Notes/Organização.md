## Organização sem módulos

- Removidos os arquivos de html e css do componente principal 
- Utilizado apenas o template para pegar o elemento das rotas

````javascript
@Component({
  selector: 'app-root',
  template: '<router-outlet></router-outlet>'
})
````