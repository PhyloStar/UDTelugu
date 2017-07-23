---
layout: relation
title: 'discourse'
shortdef: 'discourse element'
---

This is used for interjections and other discourse particles and elements (which are not clearly linked to the structure of the sentence, except in an expressive way). In Italian the use of <code>discourse</code> is attested for interjections (or nouns used as interjections) only, but is also generally recommended for emoticons or elements POS tagged as <code>SYM</code> not elsewhere classified.

~~~ sdparse
Grazie/INTJ Italia , ti ho dato l' oro .
discourse(dato, Grazie)
~~~
~~~ sdparse
Sì/INTJ , proprio l' Italia .
discourse(Italia, Sì)
~~~
~~~ sdparse
Brava , brava , complimenti/INTJ .
discourse(Brava, complimenti)
~~~
