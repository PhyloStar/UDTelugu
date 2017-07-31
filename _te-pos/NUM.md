---
layout: postag
title: 'NUM'
shortdef: 'numeral'
---

Cardnial numbers are treated as **NUM** tag (e.g., ఒకటి, రెండు, మూడు, 4, IV  etc). Fractions (సగం, పదో వంతు, రెండుంబావు etc.,) will also be treated as **NUM** tag(s). 

In case of multi-word numeric expressions, all words are tagged **NUM** and connected by a FLAT dependency relation.

Numbers in Telugu can also function as ADJ, ADV and NOUN. **Inflected numbers**, when not appearing as a multi-word numeric expression, will be either of these POS depending on their syntactic function in the sentence.

In ordinal numbers (e.g., number expressions in మొదటి రోజు, ఒకటో పాట etc.,) the number words function as **ADJ** to the following nouns and should be tagged such. [UD guidelines](http://universaldependencies.org/u/pos/NUM.html) suggest the same.

Multiples (రెండురెళ్ళు - two times two) and Denominations (వందల, వందలలో, వేలలో, రూపాయలు, రూపాయలకి, పైసలు  etc), when not appearing as a multi-word numeric expression, are tagged **NOUN**. 

As UD Guidelines say, multiplicative numerals are **ADV** (e.g., మూడింతలు, రెండింతలు, పదిరెట్లు - thrice, twice, ten times etc.) 

Words used with numerals to indicate quantities 



