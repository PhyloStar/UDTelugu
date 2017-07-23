---
layout: relation
title: 'advmod'
shortdef: 'adverbial modifier'
---
Adverbial modifier advmod is an adverbial modifying an adverb, a verb, an adjective or a nominal. 

~~~ sdparse
jooksis väga kiiresti
advmod(kiiresti-3, väga-2)
advmod(jooksis-1, kiiresti-3)
~~~

ran very quickly

~~~ sdparse
Kass nägi ka koera .
nsubj(nägi-2, Kass-1)
advmod(koera-4, ka-3)
dobj(nägi-2, koera-4)
punct(nägi-2, .-5)
~~~
The cat saw also the dog.
