---
layout: relation
title: 'nmod:appos'
shortdef: 'nominal modifier apposition'
udver: '2'
---

In FrenchSpoken the `nmod:appos` relation is used for appositions which modify nominal elements. The nominal modifier is not introduced by a preposition (else we use the [nmod]() relation). Contrary to the [conj:appos]() relation, the `nmod:appos` relation doesn't respect the prosody of lists.

Here are a few examples :

~~~ sdparse
Le journal Libération a refusé de dévoiler ses sources concernant le dossier Fillon . \n The newspaper Liberation refused to reveal its sources in the fillon case.
nmod:appos(journal, Libération)
nmod:appos(dossier, Fillon)
~~~

~~~ sdparse
l' affaire Dreyfus
nmod:appos(affaire, Dreyfus)
~~~

~~~ sdparse
la société Hebrard
nmod:appos(société, Hebrard)
~~~

~~~ sdparse
la région Auvergne
nmod:appos(région, Auvergne)
~~~


N.B.: for phrases like "la ville de Paris" we use the [nmod]() relation because of the preposition (which cannot be removed *la ville Paris)

~~~ sdparse
la ville de Paris
nmod(ville, Paris)
case(Paris, de)
~~~


~~~ sdparse
La rue Faidherbe et la place Voltaire sont situées dans le même quartier. \n Faidherbe street and place Voltaire are located in the same neigbourhood.
nmod:appos(rue, Faidherbe)
nmod:appos(place, Voltaire)
~~~

~~~ sdparse
Monsieur Dupont habitait près de la ligne Maginot. \n Mister Dupont lived close to the Maginot Line. 
nmod:appos(Monsieur, Dupont)
~~~

We use `nmod:appos`, instead of flat, for "le président Macron", which follows in French the same pattern as other `nmod:appos`. The relation is also used between first and second name:

~~~ sdparse
le président Macron
nmod:appos(président, Macron)
~~~

~~~ sdparse
Emmanuel Macron
nmod:appos(Emmanuel, Macron)
~~~

~~~ sdparse
l’ acteur Gaspard Ulliel
nmod:appos(acteur, Gaspard)
nmod:appos(Gaspard, Ulliel)
~~~

~~~ sdparse
la rue Victor Hugo
nmod:appos(rue, Victor)
nmod:appos(Victor, Hugo)
~~~
