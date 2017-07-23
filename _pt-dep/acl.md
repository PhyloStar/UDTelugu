---
layout: relation
title: 'acl'
shortdef: 'clausal modifier of noun (adjectival clause)'
---

`acl` stands for finite and non-finite clauses that modify a nominal.
The `acl` relation contrasts with the [advcl]() relation, which is
used for adverbial clauses that modify a predicate. The head of the
`acl` relation is the noun that is modified, and the dependent is the
head of the clause that modifies the noun.

In Portuguese, there are also 2 other language-specific subtypes of
`acl`: `acl:part`, `acl:relcl`.

Examples:

~~~ sdparse
Uma defesa bem parecida com aquela de Lula, no começo das denúncias contra José Paulo Bisol.
acl(defesa, parecida)
~~~

~~~ sdparse
O caso nasceu de uma "vendetta", obra de um certo Francesco Farina, dono do Modena, um time rebaixado à 3ª divisão.
acl(time, rebaixado)
~~~

~~~ sdparse
A Liga de Assistência e Recuperação, órgão ligado à Prefeitura de Salvador, está desenvolvendo um projeto.
acl(orgão, ligado)
~~~
