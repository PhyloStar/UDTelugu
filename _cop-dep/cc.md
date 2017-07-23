---
layout: relation
title: 'cc'
shortdef: 'coordinating conjunction'
---

The label for coordinating conjunctions. These are usually ⲁⲩⲱ ‘and’ between clauses and ⲙⲛ ‘and, with’ between phrases, but could also be ϩⲓ in the sense ‘X upon Y’ or ⲏ ‘or’. If the sense is not coordinating (e.g. ⲙⲛ to mean ‘with’), cc should not be used, but nmod as with a regular preposition. 

Coordination is marked left to right, with the first coordinate dominating all subsequent coordinations and receiving the incoming grammatical relations. The reasoning is that to retrieve the function of any coordinate, we can check its parent’s function, even without knowing how many coordinates there are (X and Y and Z and …). For example:

~~~ sdparse
ϩⲛ/ADP ⲙ/DET ⲙⲛⲧⲁⲡⲓⲥⲧⲟⲥ/NOUN ,/PUNCT ⲙⲛ/ADP ⲙⲛⲧⲁⲕⲁⲑⲁⲣⲧⲟⲥ/NOUN ⲛⲓⲙ/PRON \n In faithlessness and every impurity

case(ⲙⲛⲧⲁⲡⲓⲥⲧⲟⲥ, ϩⲛ)
det(ⲙⲛⲧⲁⲡⲓⲥⲧⲟⲥ, ⲙ)
cc(ⲙⲛⲧⲁⲡⲓⲥⲧⲟⲥ, ⲙⲛ)
conj(ⲙⲛⲧⲁⲡⲓⲥⲧⲟⲥ, ⲙⲛⲧⲁⲕⲁⲑⲁⲣⲧⲟⲥ)
det(ⲙⲛⲧⲁⲕⲁⲑⲁⲣⲧⲟⲥ, ⲛⲓⲙ)
~~~

Note that the function of ⲙⲛⲧⲁⲡⲓⲥⲧⲟⲥ ‘faithlessness’ is nmod. To recover the function of ⲙⲛⲧⲁⲕⲁⲑⲁⲣⲧⲟⲥ ‘impurity’, we can look at ‘faithlessness’, its immediate parent and establish that ‘impurity’ is also nmod. Also note that the word ⲙⲛ ‘and’ is ambiguous with the meaning of comitative ‘with’ (e.g. go somewhere with someone). When used in the latter way, it is not labeled cc + conj but rather nmod + case, as with all other prepositions.

Exceptionally, clause initial ‘and’ or ‘but’ is connected to the root of the clause, pointing backwards, as in this example:

~~~ sdparse
ⲏ/CONJ ϯ/PRON ⲥⲟⲟⲩⲛ/VERB ⲁⲛ/ADV \n Or don't I know? 

cc(ⲥⲟⲟⲩⲛ, ⲏ)
nsubj(ⲥⲟⲟⲩⲛ, ϯ)
neg(ⲥⲟⲟⲩⲛ, ⲁⲛ)
~~~

In this case, the word ⲏ ‘or’ cannot be attached to a preceding word, so it is pointed to from the following conjunct ‘know’ with the usual function, cc.
