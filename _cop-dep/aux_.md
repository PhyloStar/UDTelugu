---
layout: relation
title: 'aux'
shortdef: 'auxiliary'
# The filename "aux" is not allowed on Windows, so we redirect instead
# (see https://github.com/UniversalDependencies/docs/issues/20)
redirect_from: "cop/dep/aux.html"
---

The relation between a lexical verb and a conjugation base marks the base as aux to the verb, as shown below. This applies to all tripartite conjugation bases, but NOT to converters, which receive the `mark` label.

~~~ sdparse
ⲁ/AUX ⲩ/PRON ⲥⲟⲧⲡ/VERB ⲥ/PRON \n They chose her (or: she was chosen)
nsubj(ⲥⲟⲧⲡ, ⲩ)
aux(ⲥⲟⲧⲡ, ⲁ) 
dobj(ⲥⲟⲧⲡ, ⲥ)
~~~

Some other elements that are marked as aux include the future auxiliary ⲛⲁ (tagged FUT) and the potential verb ϣ ‘be able to’, which is marked as an auxiliary to the lexical verb that follows it. This should not be confused with the impersonal verb ϣϣⲉ ‘it is appropriate’, which is treated as a main verb governing an infinitive.
