# li

## Definition

li is "language of intentions", to communicate wishes and/or intentions in a clear and objective way to humans and machines.

Today it is been used only for software documentation writing, but in the future, parsers can be created for it, to be interpreted by
computers.

1. Each `li` file starts with

```
li
 li
```

## Examples

1. Comments inside li code are written inside of de parenthesis

```
li
 li
  (above I defined li)
```

2. Value assignment is in the form o \n (new line) followed by a space:

```
(here I initialize li telling that the value of li is li)
li
 li
```

```
(here I say that "arthur" is the creator of li)
arthur
 creator
  li
```

3. The use of the question mark is to ask things, for the search for reason, for the reason that it was written

```
li
 li
  ?
   li initialization
```

4. Strings are writing normally, but without punctuation and without quotation marks

```
li
 li
  ?
   eh language of intentions
   ("eh" is a portuguese-li word that corresponds to "is" in English)
```

5. The use of \_ (underscore) indicates the creation of variables with that name

```
li
 li
  _language_of_intents
   (store the above node tree)

  _language_of_intents
   ?
    li
```

6. Each indented block in li is a node, that explicits a thinking block. Blocks like that have no end, but to improve reading, blocks can be divided into many different blocks, that are connected by variables.

```
li
 li

(here we will do a report of some workshop parts)
engine
 ?
  (part responsible to move its bearer)
 car
 motorcycle
 _boat
 (here, the indentation means that the car, motorcycle and the boat, have engines and at the same time there is only three vehicles inside the workshop at the moment)

(here the _boat variable has been redefined to improve reading and writing)
_boat
 color
  blue
   engine quantity
    2
 status
  45%
 _boat_parts_value
  8500

 _boat_parts_value
 gearshift 1500
 propeller 7000
```

7. Master blocks (or master-nodes) are blocks that have precedence over other blocks. Generally, they contain definitions that need to be read and/or processed first for that other blocks makes sense. Example: Rock Paper Scissors Game:

```
(here are listed the rules of the game)
-rock-paper-scissor
 rock
  > scissor
 paper
  > rock
 scissor
  > paper

(The game starts here)
arthur
 scissor
  \_result?

computer
 rock
  _result?

\_result?
 computer
 (computer wins)
```

## Previous commits

Various aspects of li behavior and history aren't present here on this introductory README.

They are instead embedded in previous commits since its first existence on this repository.

You can check another forms both in english-li and portuguese-li by searching previous commits or forking it. Enjoy! :)

## Trivia

PS: linguagem-intencoes is the name of li in Brazilian Portuguese

PS2: A little bit of the history of this project:

Jan 2018

Project description
Theory of Language of Intentions - how to quickly express wishes for humans and robots

This project arose as a side effect of the second manic phase of bipolar disorder. For several days I mostly didn't sleep thinking and crafting an optimized language to communicate fast with both humans and robots (computers). All this sacrifice and cerebral cells burning turned out into a lot of verbs, nouns, and keywords that expressed wishes well and straightforward both in English and Portuguese. But, as I lacked the strength and knowledge to develop a compiler or interpreter for it (I started one in JavaScript but without success), it didn't work with computers.

Now it stands as a mark in my life and career, representing a lot of my personality and tastes for language and computer programming. I do not have plans to improve or finish it for now, mainly because I have found a perfect substitute: Ruby! :)
