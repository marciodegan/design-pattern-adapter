## Design Pattern - Adapter

### Notes:
- Continuação do: https://github.com/marciodegan/design-patterns-observer

- Depender sempre de abstrações, e não de implementações específicas. Inclusive, esse é um dos princípios de SOLID (Dependency Inversion Principle, a letra D). Devemos sempre preferir depender de abstrações, ou seja, interfaces ou classes abstratas, sempre que possível, ao invés de implementações específicas.
- Usando a analogia do adaptador da tomada...se você compra um cel novo cuja tomada é diferente da sua casa, usamos um adaptador e não precisamos alterar nem o cel e nem a casa.
- Neste exemplo, foi criado um adaptador para as requisições HTTP. Em uma mudança, basta mudar o adapter, sem mexer no código existente.
- Exemplo de duas classes em que uma delas depende demais de detalhes de estrutura da outra...pode-se tentar criar um adaptador que faz a ponte.
  Quando precisamos utilizar código legado ou código de componentes externos em nosso sistema, é muito comum não ter a interface (métodos públicos) batendo com o que a gente precisa, então nesses casos nós criamos adapters.
- Padrões estruturais nos ajudam a relacionar diversas classes de forma organizada
- Detalhes de infraestrutura devem ser abstraídos através de interfaces
- Padrão Adapter pode nos ajudar a trocar detalhes de infraestrutura, sem muitas dores de cabeça
- Esse padrão é muito simples e muito utilizado no dia a dia do desenvolvimento, então vale a pena a sua leitura com mais calma: https://refactoring.guru/design-patterns/adapter

#### Notes from book Heads up - Design Patterns
- O padrão adapter converte a interface de uma classe para outra interface que o cliente espera encontrar.
- O adaptador permite que classes com interfaces incompatíveis trabalhem juntas.
- Cliente só vê interface alvo -> Interface alvo <- adaptador (solicitação()) -> adaptado (solicitação específica())
 
