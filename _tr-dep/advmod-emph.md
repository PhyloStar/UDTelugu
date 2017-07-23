---
layout: relation
title: 'advmod:emph'
shortdef: 'emphasizing word, intensifier'
---

This is a subtype of  [advmod](). 
It used for (non-clausal) modifiers that emphasize or intensify their heads.

~~~ sdparse
Çok da güzel bir kızmış \n She was (apparently) a very (very) beautiful girl.
admod:emph(Çok, da)
admod(güzel, Çok)
~~~

~~~ sdparse
Güzel mi güzel bir kız \n A very (very,very) beautiful girl
advmod:emph(Güzel-1, mi)
~~~

~~~ sdparse
Kitabı bile okumamış \n He (apparently) hasn't even read the book
admod:emph(okumamış, bile)
~~~

~~~ sdparse
İlk kitabı bile okumamış \n He (apparently) hasn't read even the book
admod:emph(kitabı, bile)
~~~


