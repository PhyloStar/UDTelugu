---
layout: relation
title: 'conj'
shortdef: 'conjunct'
---

`conj` relation is used to annotate the different conjuncts in a coordination structure.

Coordination in the Basque UD annotation follows the general schema where the first element of the conjunction is the head, and each conjunct, conjunction complementizer or puntuation mark acting as a conjunction should be attached to the first conjunct:

***Zidane, Henry, Barthez, Deschamps, Blanc eta enparauek** Europako Talde sendoena osatzen dute aditu gehienentzat .*

***Zidane, Henry, Barthez, Deschamps, Blanc and the rest** form the most robust team of Europe according to most experts .*


~~~ sdparse
Zidane, Henry, Barthez, Deschamps, Blanc eta enparauek Europako Talde sendoena osatzen dute aditu gehienentzat . \n Zidane, Henry, Barthez, Deschamps, Blanc and rest_the Europe_of team robust_the_most experts most_according_to .

Zidane , Henry , Barthez , Deschamps , Blanc eta enparauek Europako talde sendoena osatzen dute aditu gehienentzat .
punct(Zidane-1, ,-2)
conj(Zidane-1, Henry-3)
punct(Zidane-1, ,-4)
conj(Zidane-1, Barthez-5)
punct(Zidane-1, ,-6)
conj(Zidane-1, Deschamps-7)
conj(Zidane-1, ,-8)
conj(Zidane-1, Blanc-9)
cc(Zidane-1, eta-10)
conj(Zidane-1, enparauek-11)
nmod(talde-13, Europako-12)
dobj(osatzen-15, talde-13)
amod(talde-13, sendoena-14)
aux(osatzen-15, dute-16)
nmod(osatzen-15, aditu-17)
det(aditu-17, gehienentzat-18)
punct(osatzen-15, .-19)
~~~ 

