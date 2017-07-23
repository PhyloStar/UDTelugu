---
layout: relation
title: 'foreign'
shortdef: 'foreign words'
---

We use <code>foreign</code> to label sequences of foreign words. These are given a linear analysis: the head is the first token in the foreign phrase. 
In the Italian Treebank, the only cases attested appear with words POS tagged as <code>X</code>. The only exception to that happens when foreign proper names are part of a sequence of foreign words (as in the last example).

~~~ sdparse
Dulcis/X in/X fundo/X, il portamento .
foreign(Dulcis, in)
foreign(Dulcis, fundo)
~~~
~~~ sdparse
Home/X run/X .
foreign(Home, run)
~~~
~~~ sdparse
Il primo disco si chiama Greetings/X from/X Asbury/PROPN Park/PROPN .
foreign(Greetings, from)
foreign(Greetings, Asbury)
foreign(Greetings, Park)
~~~
