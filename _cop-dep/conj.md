---
layout: relation
title: 'conj'
shortdef: 'conjunct'
---

This function marks the coordinate (not the coordinating word ‘and’ etc.) and attaches it to the first member of the chain of coordinates. To retrieve the function of the daughter of`conj`, only its parent needs to be examined, cf. the guidelines for cc. The same example applies:

~~~ sdparse
ϩⲛ/ADP ⲙ/DET ⲙⲛⲧⲁⲡⲓⲥⲧⲟⲥ/NOUN ,/PUNCT ⲙⲛ/ADP ⲙⲛⲧⲁⲕⲁⲑⲁⲣⲧⲟⲥ/NOUN ⲛⲓⲙ/PRON \n In faithlessness and every impurity

case(ⲙⲛⲧⲁⲡⲓⲥⲧⲟⲥ, ϩⲛ)
det(ⲙⲛⲧⲁⲡⲓⲥⲧⲟⲥ, ⲙ)
cc(ⲙⲛⲧⲁⲡⲓⲥⲧⲟⲥ, ⲙⲛ)
conj(ⲙⲛⲧⲁⲡⲓⲥⲧⲟⲥ, ⲙⲛⲧⲁⲕⲁⲑⲁⲣⲧⲟⲥ)
det(ⲙⲛⲧⲁⲕⲁⲑⲁⲣⲧⲟⲥ, ⲛⲓⲙ)
~~~

The first coordinate points right to the second (conj goes from the first member in the coordination to all other members, left to right). 
