# Curso Lógica de Programação Essencial

Neste arquivo estão contidas as anotações das informações retiradas do curso de LP da DIO.

## O que é lógica de programação?

"Lógica de programação significa apenas contextualizar a lógica na programação de computadores, buscando a melhor sequência de ações para solucionar um problema"

obs: Programar é resolver problemas. 



## Metacognição

A metacognição pode ser entendida como  a ação de refletir sobre o que se aprender. Bem como a capacidade de avaliar e controlar o aprendizado. "Pensar como você pensa". 



### Abstração 

"Abstração é a habilidade de se concentrar nos aspectos essenciais de um contexto qualquer, ignorando características menos importantes ou acidentais "



## Algoritmo e Pseudocódigos

**Algoritmo:** é uma sequência de passos que resolvem um problema.

**Pseudocódigo:** é uma forma genérica de escrever um algoritmo, utilizando linguagem simples (nativa). Ou seja, se escreve em português, no caso do brasil, de forma a ser entendida por qualquer pessoa. 



## Tomada de decisão e Expressões 

**Expressões aritméticas:** são expressões que utilizam operadores aritméticos e funções aritméticas envolvendo constantes variáveis. 

Exemplos: 

50 + 50

total + 50

**Expressões literais:** São expressões com constates e/ou variáveis que tem como resultado valores literais. Iremos utilizar as expressões literais na atribuição de valor para uma variável ou constante. 

Exemplos:

nome = "José Maria"

media= (nota1,nota2,nota3,nota4)/4

**Operações racionais:** São expressões compostas por outras expressões ou variáveis numéricas com operadores relacionais. As expressões relacionais retornam valores lógicos (verdadeiro/falso). 



**Tomada de Decisão:** Quando escrevemos programas, geralmente ocorre a necessidade de decidir o que fazer dependendo de alguma condição encontrada durante a execução. 



## Concatenação 

É um termo usado em computação para designar a operação de unir o conteúdo de duas strings.

* String é uma sequência de caracteres. 

Sinais usados para fazer a concatenação: 

(., + ou &)

Exemplo: " o seu nome é:" + nome + "o seu sobrenome é: " + sobrenome + "sua idade é:" + idade

Concatenação é útil para criar informações/exibição para o usuário. 



## O que são linguagem de programação? 

É uma linguagem escrita e formal que especifica um conjunto de instruções e regras usadas para gerar programas (software). A função da linguagem de programação é servir de um meio de comunicação entre o computador e o humano. 



### Existem dois tipos de linguagem de programação

**Alto nível:** essas são aquelas cuja sintaxe se aproxima mais da nossa linguagem e se distanciam mais da linguagem da máquina. 

**Baixo nível:** é aquela que se aproxima mais da linguagem da máquina. 



## Portugol 

é uma pseudo linguagem que permite ao leitor desenvolver algoritmos estruturados em português de forma simples e intuitiva. 

**Comandos do portugol:**

* escreva(texto)
* cadeia 



#### Desvios condicionais e comentários no portugol 

**Desvio condicional:  se**

é utilizada a palavra reservada **se** , a condição de ser testada entre parenteses as instruções que devem ser executadas entre chaves caso o desvio seja verdadeiro. 

Exemplo: 

se (media >=7) {

escreva("parabéns!! você foi aprovado".)

}

**Senao**

Agora vamos imaginar que se a condição for falsa um outro conjunto de comandos deve ser executado. 

Exemplo: 

se(media>=7) {

escreva ("Parabéns! Você foi aprovado")}

 senao { 

escreva("Infelizmente você foi reprovado. ")

Para fazer comentários dentro do projeto use: 

//

**Caso**

Este comando é similar aos comandos **se e senao**, e reduz a complexidade na escolha de diversas opções. Apesar de suas similaridades com o **se**, ele possui algumas diferenças. Neste comando não é possível o uso de operadores lógicos, ele apenas trabalha com valores definidos. 

exemplo: 

inteiro valor =0

escolha (valor)

{

caso1: // testa se o valor é igual a 1

escreva("Ok! Abrir Netflix.")

pare

caso 2: // testa se o valor é igual a 2

escreva ("Ok! abrir Amazon Prime.")

pare

caso 3: // testa se o valor é igual a 3

escreva("Ok! Abrir HBO GO.")

pare

caso contrário: 

escreva("Você deve escolher as opções 1, 2 ou3")

}













