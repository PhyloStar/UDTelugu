---
layout: relation
title: 'flat'
redirect_from: "it/dep/name.html"
shortdef: 'name'
---

<code>name</code> is one of the three relations for compounding in UD (together with <code>compound</code> and <code>mwe</code>). It is used for proper nouns constituted of multiple nominal elements. It is not used to replace the usual relations in a phrasal or clausal name, like titles of books, where the actual dependencies should be preserved. 

~~~ sdparse
Ecco l'arringa di Tiziana Maiolo . 
name(Tiziana, Maiolo)
~~~

Names are annotated in a flat, head-initial structure, in which all words in the name modify the first one using the <code>name</code> label. This also works for prepostions or determiners and numerals that are part of the names.

~~~ sdparse
Formula 1/NUM . 
name(Formula, 1)
~~~
~~~ sdparse
Marcello Dell' Utri . 
name(Marcello, Dell')
name(Marcello, Utri)
~~~

Words joined by <code>name</code> should all be part of a minimal noun phrase; otherwise regular syntactic relations should be used. For organization names with clear syntactic modification structure, the dependencies should reflect the syntactic modification structure using regular syntactic relation. 

~~~ sdparse
L' ordine Mauriziano . 
det(ordine, L')
amod(ordine, Mauriziano)
~~~
~~~ sdparse
Il Ministero di gli Interni 
det(Ministero, Il)
nmod(Ministero, Interni)
det(Interni, gli)
case(Interni, di)
~~~

In addition, regular syntactic relations are used: 

* for a modifying determiner or 
* to connect together the words of a description or name which involve embedded prepositional phrases, sentences, etc.

~~~ sdparse
Mariatersa Di Lascia
name(Mariatersa, Lascia)
case(Lascia, Di)
~~~
~~~ sdparse
Università di Pristina 
name(Università, Pristina)
case(Pristina, di)
~~~


