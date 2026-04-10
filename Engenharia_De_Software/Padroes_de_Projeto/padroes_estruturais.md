#### Adapter
&emsp;Funciona como uma ponte entre duas interfaces incompatíveis. Pense em um intérprete sentado entre duas pessoas conversando em idiomas diferentes (um problema comum em programação!), ou um simples adaptador de tomada que permite carregar seu telefone americano em qualquer país.
Ao permitir que os objetos se comuniquem de uma maneira que ambos entendam, o padrão do adaptador combina a capacidade de duas interfaces independentes.

#### Decorator
&emsp;O padrão **Decorator** tem como objetivo adicionar novos comportamentos ou responsabilidades a um objeto **dinamicamente**, sem alterar a classe original.

Em vez de modificar a classe principal ou criar várias subclasses através de herança, o Decorator envolve o objeto original e implementa a mesma interface, permitindo:
- Chamar o método original (delegação)
- Adicionar lógica extra antes ou depois da chamada
- Combinar múltiplos decoradores de forma flexível\

#### Facade
&emsp;O padrão Facade ou Fachada esconde um pipeline complexo dentro de uma interface simples
ao invés de descrever esse pipe toda vex que tal ação for executada.
