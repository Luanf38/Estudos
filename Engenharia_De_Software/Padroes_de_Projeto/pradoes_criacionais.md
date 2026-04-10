#### Singleton
&emsp;Padrão que garante que uma classe tenha apenas **uma única instância** em todo o ciclo de vida da aplicação e fornece um ponto de acesso global a essa instância.

É comumente usado em situações como:
- Conexão com banco de dados (ex: SQLite em apps mobile)
- Gerenciamento de configurações
- Cache de dados
- Classe que armazena informações do usuário logado

#### Factory
&emsp;é um padrão criacional da Gang of Four que define uma interface para criar objetos, mas delega a decisão de qual classe instanciar para as subclasses.

##### Objetivo principal:
Permitir a criação de objetos de forma flexível e centralizada, sem que o código cliente precise usar `new` diretamente nas classes concretas.

##### Vantagens:
- Permite criar objetos com diferentes configurações ou contextos
- A classe pode ter múltiplos métodos fábrica (ex: `createDefault()`, `createEmpty()`, `createWithUserData()`)
- Facilita a manutenção e a extensão do código
- Oculta a lógica de criação e os detalhes de implementação

#### Builder

O padrão **Builder** (Construtor) é um padrão criacional da Gang of Four que permite criar objetos complexos de forma gradual e controlada, separando o processo de construção da representação final do objeto.

### Objetivo principal:
- Evitar construtores gigantes com muitos parâmetros (`Telescoping Constructor`)
- Permitir a criação de um objeto passo a passo
- Possibilitar a reutilização do mesmo processo de construção para criar variações diferentes do objeto

### Quando usar:
- Quando um objeto possui muitos campos opcionais
- Quando a criação do objeto envolve vários passos com ordem específica
- Quando você quer esconder a complexidade da criação do objeto do cliente