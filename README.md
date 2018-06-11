# li

## Definição

li é linguagem de intenções, para comunicar desejos e/ou intenções de forma clara e objetiva para humanos e máquinas.

Atualmente está sendo usada apenas para escrita de documentação de software, mas no futuro parsers podem ser criados
para ela, a fim de ser interpretada por computadores.

1. Todo arquivo ```li``` começa com

```
li
 li 
```

## Exemplos

1. Comentários dentro do código li são escritos dentro de parênteses

```
li
 li
(aqui em cima eu defini li)
```

2. Atribuição de valores se dá na forma de um \r (carriage return) seguido de espaço:

```
(aqui eu inicializo li dizendo que o valor de li é li)
li
 li

(aqui eu digo que o arthur é o criador de li)
arthur
 criador
  li
```
3. O uso de interrogação denota questionamento, ou busca pela razão, pelo por quê daquilo que foi escrito:

```
li
 li
  ?
   inicializacao de li
```

4. Strings são escritas normalmente, mas sem pontuação, e sem aspas

```
li
 li
  ?
   eh linguagem de intencoes
```

5. O uso de _ (underscore) indica criação de variáveis com aquele nome

```
li
 li
  _linguagem_de_intencoes
   guarda a arvore de nos acima

_linguagem_de_intencoes
 ?
  li
```

6. Cada bloco identado em li é um nó, que explicita um bloco de pensamento. 
Blocos assim não tem fim, mas para melhorar a leitura, os blocos podem ser
divididos em vários blocos diferentes, que são ligados por variáveis.

```
li
 li
 
(aqui faremos uma descrição das peças em uma oficina) 
motor
 ?
  (peça responsável por movimentar o portador dela)
 carro
 moto
 _barco
 (aqui a identação significa que carro, moto e _barco possuem motores e que ao mesmo tempo,
 só existem três veículos dentro da oficina, no momento)

(aqui o _barco foi redefinido para melhorar a leitura e escrita)
_barco
 cor
  azul
 qtd motores
  2
 estado (ou status, em inglês)
  45%
 _valor_parts_barco
  8500

_valor_parts_barco
 cambio 1500
 helice 7000
```
