#### Observer
&emsp;É frequentemente usado quando há uma relação um-para-muitos entre objetos. O padrão garante que todos os dependentes 'observem' um objeto e sejam imediatamente notificados se ele mudar de estado. É um pouco como quando os varejistas informam aos assinantes sobre eventos que são de seu interesse, ou seja, o lançamento de um novo produto ou uma venda.

#### Chain of Responsibility
&emsp;Este padrão é usado para passar solicitações de clientes ao longo de uma cadeia de objetos 'manipuladores' a serem processados. Cada elo na cadeia decidirá se processará a solicitação ou a passará para o próximo da fila.

#### Strategy
&emsp;Este padrão permite agrupar algoritmos relacionados. Dessa forma, é possível colocar cada algoritmo em uma classe separada ('estratégias') e tornar os objetos intercambiáveis ​​sem modificar o cliente. Assim, o comportamento de uma classe ou seu algoritmo pode ser alterado em tempo de execução, dependendo da estratégia selecionada.