---
layout: relation
title:  'det'
shortdef : 'determiner'
---

A determiner is the relation between the head of an NP and its determiner. 

~~~ sdparse
The man is here
det(man, The)
~~~

~~~ sdparse
Which book do you prefer ?
det(book, Which)
~~~

~~~ sdparse
You 've all won !
nsubj(won, You)
det(You, all)
aux(won, 've)
~~~
