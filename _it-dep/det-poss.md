---
layout: relation
title: 'det:poss'
shortdef: 'possessive determiner'
---

Whenever there is a possessive determiner, <code>det:poss</code> should be used instead of <code>det</code>. All possessive determiners have the feature <code>Possessive</code> defined as <code>Yes</code> and the only instances of the <code>det:poss</code> relation attested in the Italian Treebank appear with those elements.

~~~ sdparse
Sarà mia cura verificare . 
det:poss(cura, mia)
~~~
~~~ sdparse
Ha da poco annunciato le proprie dimissioni . 
det:poss(dimissioni, proprie)
~~~
