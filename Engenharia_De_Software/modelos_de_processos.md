### Modelos de Processos de software
&emsp;Os modelos de processos de software são modelos que auxiliam no processo de construção de um sistema, desde o levantamento de requisistos até o funcionamento em produção e sua manutenção. Entre esses modelos alguns se destacam por sua eficiência, tempo em atividade e evolução ao longo dos anos (lembrando que não existe regra sobre qual modelo usar e qual o mais eficiente, cada um tem seus prós, contras e melhores casos de uso, e pode-se também aproveitar algumas características ou etapas de vários modelos sem a necessidade de usar o modelo completo).

#### Modelo em cascata 
&emsp;O modelo em cascata ou waterfall, representa um detalhamento de suas atividades em um processo linear onde para avançar em um processo é necessário concluir o atual, esse processo é útil em casos que os requisitos do sistema são muito bem definidos e que não haja mudanças, já que após um processo ser concluído ele fica para trás até o reinício do cliclo.

&emsp;Também não há capacidade de ver e experimentar o software até que o último estágio de desenvolvimento seja concluído, o que resulta em altos riscos do projeto e resultados imprevisíveis. Os testes, geralmente, são apressados, ​​e os erros são caros para corrigir  

![alt text](images/modelo_cascata.png)  



### Modelo Incremental
&emsp;Especifica e implementa uma parte do software que é revisada e outros requisitos adicionados e implementados em grupos.
&emsp;É como se o sistema fosse desenvolvido em pequenos pedaços e validados pelo cliente
e cada acerto se mantém e a cada passo gera uma aplicaçao mais polida e próxima do resiltado final.
&emsp;Cada versão entrega um produto operacional, apresentando aos clientes funcionalidades importantes primeiro, reduzindo os custos de entrega inicial. O risco de alterar os requisitos é bastante reduzido e os cliente podem responder a cada construção.
&emsp;Apesar de seus pontos fortes, esse modelo requer um bom planejamento e definição precoce do sistema completo e totalmente funcional. Também requer interfaces de módulo bem definidas. A figura abaixo ilustra esse modelo.
![alt text](images/modelo_incremental.png)

### Modelo Espiral
&emsp;O modelo espiral usa alguns pontos positivos de seus modelos antecessores, ele tem metodologia iterativa e usa ma abordagem sistemática e a capacidade de controlar o processo. A maior ênfase atual recai sobre a análise de risco. Além disso, ele entrega um projetoem iterações que giram em torno da espiral.
![alt text](images/modelo_espiral.png)
###### Note que o modelo possui quatro etapas que serão explicadas logo abaixo.

##### Identificação
&emsp;É a parte em que a ênfase é a comunicação entre o cliente e o analista de sistema para definir quais são os requisitos a serem desenvolvidos, fora o que será necessário para a implantação.

##### Projeto 
&emsp;Começa na espiral básica com o projeto conceitual e inclui espirais subsequentes com projeto arquitetônico, projeto lógico de módulos, projeto físico do produto e projeto final.

##### Construção (desenvolvimento)
&emsp;É o desenvolvimento do produto de software real em cada espiral. Na espiral básica, quando o conceito precisa ser avaliado de acordo com sua viabilidade, então, deve-se desenvolver uma POC (Prova de Conceito) e tentar obter um feedback valioso do cliente. Conhecendo todos os requisitos e detalhes de projeto, é produzida uma versão numerada do modelo de trabalho (build) do software. O cliente revisa todas as construções e dá feedback.

##### Avaliação (análise de risco)
&emsp;É um processo de identificação, estimativa e monitoramento da viabilidade técnica gestão de riscos. Por exemplo, cronograma em atraso e custos excedidos.

#####  Modelo de Pototipação
&emsp;Nesse modelo os requisitos são parciais ou imprecisos, então é criado um protótipo para apresentação e coleta de feedback, dependendo da abordagem o protótipo pode ser refinado ou utilizado para o produto final, ou também pode ser descartado.