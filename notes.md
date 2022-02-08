# Notas

## POO

## DESIGN PATTERN
 - SOLID
    - Single Responsiblity:  uma classe deve ser especializada em um único assunto e possuir apenas uma responsabilidade dentro do software.
    - Open-Closed: objetos ou entidades devem estar abertos para extensão, mas fechados para modificação.
    - Liskov Substitution: uma classe derivada deve ser substituível por sua classe base.
    - Interface Segregation: uma classe não deve ser forçada a implementar interfaces e métodos que não irão utilizar.
    - Dependency Inversion: dependa de abstrações e não de implementações.
    - https://medium.com/desenvolvendo-com-paixao/o-que-%C3%A9-solid-o-guia-completo-para-voc%C3%AA-entender-os-5-princ%C3%ADpios-da-poo-2b937b3fc530

- Injeção de dependência
    - É um design pattern que faz com que uma classe seja independente de suas dependências. Está fortemente ligado ao SOLID ( principalmente o S e D) e o Design Pattern "Strategy".
    - Constructor injection: faz a injeção de depêndencia através do construtor.
    - Setter Injection: com as propiedades da classe usando setter.
    - Method/Interface Injection: onde a injeção a classe do cliente implementa uma interface que declara um método para fornecer a dependência, e o injetor usa essa interface para fornecer essa dependência a classe cliente.

 - Inversão de controle
    - É um termo amplo, onde a responsabilidade de informar a implementação a ser utilizada deixa de ser da classe, e passa a ser do consumidor da classe.

 - Factory Method

 - Adapta
 
## JAVA
 
 - Modificadores de acesso
    - Existem somente 3 modificadores: private, protected e public.
    - Existem 4 níveis de visibilidade: private, default, protected e public.
    - Private: proíbe qualquer acesso externo à própria classe, inclusive das classes filhas.
    - Default: (ausência de modificadores) permite acesso a todas as classes que estiverem no mesmo pacote que a classe que possui o atributo.
    - Protected: permite acesso às classes do mesmo pacote e classes filhas, mas proíbe a qualquer outro acesso externo.
    - Public: permite acesso a qualquer código externo a classe.
    - https://pt.stackoverflow.com/questions/23/qual-%C3%A9-a-diferen%C3%A7a-entre-modificadores-public-default-protected-e-private

## SPRING
