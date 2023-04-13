## Ciclo de vida do componente

#### Construtor
- Componentes são classes, então é necessário um método construtor.
- Todo estágio da vida do componente passa pelo construtor
- Ou seja, ele sempre vem primeiro

#### OnInit
- É chamado assim que o componente é iniciado
- Similar ao useEffect com o array de dependências vazio
- Utilizado principalmente para preencher com dados do backend
- Necessário importar

#### onChange
- É chamado quando se altera algum dado dentro de algum componente
- É utilizado junto com 0 @input, que se parece com as props do react

#### DoCheck
- Quando o componente se inicia e são verificados os valores dos componentes
- ngDoCheck possui vários filhos
##### AfterContentInit
- É chamado sempre que mostra alguma coisa
##### AfterContentChecked
- Verificado quando acontece alguma alteração dentro do componente, por exemplo uma soma
##### AfterViewInit
- Assim que o componente for inicializado e carregado, essa função será invocada
##### AfterViewChecked
- É detectado uma mudança nos componentes filhos

#### onDestroy
- Chamado quando o componente é destruído
