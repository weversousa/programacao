## PROGRAMAÇÃO
É o processo de criação de instruções ou códigos que são interpretados ou executados por computadores para realizar uma tarefa ou solucionar um problema.

## VARIÁVEL
É um espaço em memória que armazena um valor ou uma referência a um objeto, que pode ser acessado e manipulado por meio de seu nome dentro do escopo em que foi definida.

## MÉTODO
É um bloco de código que define uma ação a ser realizada por um objeto ou por uma classe, podendo receber parâmetros, manipular variáveis e retornar um valor.

### ASSINATURA DE UM MÉTODO
É a sua declaração que inclui o seu nome, tipo de retorno, número e tipo de seus parâmetros, permitindo sua identificação e chamada a partir de outras partes do programa.

## PROCEDIMENTO
A única coisa que difere de um [método](#método) é que o procedimento não tem retorno.

## ESTRUTURAS DE ARMAZENAMENTOS
São mecanismos que permitem a organização e o armazenamento de dados de forma estruturada, utilizando tipos de dados como arrays, listas, pilhas, filas, map, entre outros.

### ARRAY
Armazena um conjunto de elementos em uma sequência fixa de tamanho pré-definido, permitindo o acesso aos elementos por meio de índices.

### LISTA
Armazena um conjunto de elementos em uma sequência, permitindo a adição, remoção e acesso aos elementos por meio de índices ou iteração.

### PILHA
O último elemento adicionado é o primeiro a ser removido (LIFO - Last In First Out), permitindo operações como push (inserir) e pop (remover).

### FILA
O primeiro elemento adicionado é o primeiro a ser removido (FIFO - First In First Out), permitindo operações como enqueue (inserir) e dequeue (remover).

### MAP
É uma coleção associativa que permite armazenar e recuperar pares chave-valor de forma eficiente.

## ESTRUTURAS DE REPETIÇÃO
São mecanismos que permitem a execução repetida de um conjunto de instruções enquanto uma condição é verdadeira, utilizando loops como for, while ou do-while.

### FOR
É uma estrutura de controle de fluxo que permite a repetição de um conjunto de instruções por um número definido de vezes, de forma iterativa, utilizando uma variável de controle e uma condição de parada.

### WHILE
É uma estrutura de controle de fluxo que permite a repetição de um conjunto de instruções enquanto uma condição especificada for verdadeira, de forma iterativa.

### DO-WHILE
É uma estrutura de repetição que executa um conjunto de instruções pelo menos uma vez, e então continua repetindo enquanto a condição especificada é verdadeira.

## ESTRUTURAS DE CONDIÇÃO
São mecanismos que permitem a execução condicional de um conjunto de instruções com base em uma condição ou expressão booleana, utilizando condicionais como if, if-else ou switch-case.

### IF-ELSE
É uma estrutura de condição que permite a execução condicional de um conjunto de instruções, executando uma sequência de instruções se a condição especificada for verdadeira e uma sequência diferente se a condição for falsa

### CASE
É uma estrutura de controle de fluxo que permite a seleção entre várias opções de ações possíveis, com base no valor de uma expressão ou variável, sem a necessidade de repetição de instruções condicionais

## PARADIGMAS

### POO - PROGRAMAÇÃO ORIENTADA A OBJETOS
É um paradigma de programação que utiliza classes e objetos para representar entidades do mundo real, encapsulando dados e comportamentos em um conjunto coeso e modular, permitindo o reuso, a extensibilidade e a organização estruturada do código.

#### CLASSE
É um modelo que define a estrutura e comportamento dos objetos que serão criados a partir dela em programação orientada a objetos.

#### OBJETO
É uma instância de uma classe que possui seus próprios valores de atributos e pode executar os métodos definidos pela classe.

#### INTERFACE
Define um contrato que especifica quais métodos uma classe deve implementar, sem especificar como eles devem ser implementados.

#### CLASSE ABSTRATA
uma classe que não pode ser instanciada, mas pode ser usada como um modelo para outras classes, definindo métodos que devem ser implementados por suas subclasses.

##### MÉTODOS ABSTRATOS
É um método definido em uma classe abstrata que não possui implementação, mas que deve ser implementado por suas subclasses para realizar uma ação específica.

#### PILARES
* **Encapsulamento**: é o conceito de ocultar a complexidade interna de um objeto, protegendo seus dados e permitindo o acesso apenas por meio de métodos definidos pela classe.

* **Herança**: É o conceito de criar uma nova classe a partir de uma classe existente, herdar seus atributos e métodos e adicionar ou modificar seu comportamento.

* **Polimorfismo**
    * **Sobreposição**: É o conceito de uma classe substituir o comportamento de um método herdado de sua classe pai, com a [mesma assinatura](#assinatura-de-um-método), para alterar sua funcionalidade de acordo com as necessidades da classe.

    * **Sobrecarga**: É o conceito de criar vários métodos com o mesmo nome, mas com diferentes parâmetros ou tipos de retorno, permitindo que a mesma operação possa ser realizada com diferentes argumentos.

#### AGREGAÇÃO
É um tipo de associação onde uma classe é composta por uma ou mais instâncias de outra classe, mas as instâncias podem existir independentemente da classe que as contém.
