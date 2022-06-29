# ***Flex Box***



## **Flex-container**

#### Display

 Especifica o tipo do container usado para o elemento HTML.



#### Flex-direction

A propriedade `flex-direction` define em qual direção o container deseja empilhar os itens flexíveis.

* row / row-reverse
* column / column-reverse



#### Flex-wrap

A propriedade `flex-wrap` especifica se os itens flexíveis devem ser encapsulados ou não. Define se os itens flexíveis são forçados a ficarem na mesma linha ou se podem ser quebradas em varias linhas. Se o argumento for valido, ele define a direção em que as linhas são empilhadas.

* wrap / nowrap / wrap-reverse



#### Flex-flow

A propriedade `flex-flow` é uma propriedade abreviada para definir as propriedades `flex-direction`e `flex-wrap`. 

* row wrap; / row nowrap; / row wrap-reverse;
* row-reverse wrap; / row-reverse nowrap; / row-reverse wrap-reverse
* column wrap; / column nowrap; / column wrap-reverse;
* column-reverse wrap; / column-reverse nowrap; / column-reverse wrap-reverse;



#### Justify-content

A propriedade `justify-content` é usada para alinhar os itens flexíveis:

* center; alinha os itens flexíveis no centro do contêiner
* flex-start; alinha os itens flexíveis no início do contêiner
* flex-end; alinha os itens flexíveis no final do contêiner
* space-around; exibe os itens flexíveis com espaço antes, entre e depois das linhas
* space-between; exibe os itens flexíveis com espaço entre as linhas



#### Align-items

A propriedade `align-items` é usada para alinhar os itens flexíveis.

* center; alinha os itens flexíveis no meio do contêiner
* flex-start; alinha os itens flexíveis na parte superior do contêiner
* flex-end; alinha os itens flexíveis na parte inferior do contêiner
* stretch; estica os itens flexíveis para preencher o contêiner
* baseline; alinha os itens flexíveis, como suas linhas de base alinham



#### Aling-content

A propriedade `align-content` é usada para alinhar as linhas flexíveis.

* space-between; exibe as linhas flexíveis com espaço igual entre elas
* space-around; exibe as linhas flexíveis com espaço antes, entre e depois delas
* stretch; estica as linhas flexíveis para ocupar o espaço restante
* center; exibe as linhas flexíveis no meio do contêiner
* flex-start; exibe as linhas flexíveis no início do contêiner
* flex-end; exibe as linhas flexíveis no final do contêiner



## Flex-items

#### Flex-grow

A propriedade `flex-grow`especifica quanto um item flexível crescerá em relação ao restante dos itens flexíveis. O valor deve ser um número, o valor padrão é 0.



#### Flex-shrink

A propriedade`flex-shrink` especifica quanto um item flexível diminuirá em relação ao restante dos itens flexíveis. O valor deve ser um número, o valor padrão é 1.



#### Flex-basis

A propriedade `flex-basis` especifica o comprimento inicial de um item flexível.



#### Flex

A propriedade `flex` é uma propriedade abreviada para as propriedades `flex-grow`, `flex-shrink`e `flex-basis`.



#### Order

A propriedade `order` especifica a ordem dos itens flexíveis.



#### Align-self

A propriedade `align-self` especifica o alinhamento do item selecionado dentro do contêiner flexível.

A propriedade `align-self ` substitui o alinhamento padrão definido pela propriedade `align-items` do contêiner.