---
layout: relation
title:  'dislocated'
shortdef : 'dislocated elements'
udver: '2'
---

The `dislocated` relation is used for fronted or postposed elements
that do not fulfill the usual core grammatical relations of a
sentence. Dislocated elements are attached to the same governor as the dependent that they double for.

This construction is quite frequent in spoken French. 

~~~ sdparse
Pierre je ne l' aime pas beaucoup  \n Peter I don't like him much
dislocated(aime, Pierre)
dobj(aime, l')
~~~

In FrenchSpoken we also use the `dislocated` relation. Here are some examples from FrenchSpoken.

~~~ sdparse
lui il avait passé les quatres nuits ou trois nuits à ramper dans les décombres \n He had spent the four nights or three nights crawling in the rubble 
dislocated(passé, lui)
nsubj(passé, il)
~~~

~~~ sdparse
c' est déjà arrivé ça \n  it's already happened
dislocated(arrivé, ça)
nsubj(arrivé, c')
~~~

~~~ sdparse
ces rails du tram eh ben je vais les longer \n these tram rails well I'm gonna walk along them
dislocated(longer, rails)
obj(longer, les)
~~~
