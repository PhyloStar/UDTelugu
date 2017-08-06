---
layout: postag
title: 'NUM'
shortdef: 'numeral'
---

Cardinal numbers are treated as **NUM** tag (e.g., ఒకటి, రెండు, మూడు, 4, IV  etc). Fractions (సగం, పదో వంతు, రెండుంబావు etc.,) will also be treated as **NUM** tag(s). In case of multi-word numeric expressions, all words are tagged **NUM** and connected by a FLAT dependency relation.

Numbers in Telugu can also function as ADJ, ADV and NOUN apart from being a NUM. **Inflected numbers**, when not appearing as a multi-word numeric expression, will be either of these POS (ADJ/ADV/NOUN) depending on their syntactic function in the sentence. e.g.,

a) In "ఒక పాట పాడండి." (Sing one song), ఒక is a NUM.

b) In the sentence: "నిన్న ఒకడు మా ఇంటికి వచ్చాడు." (Yesterday, oneman/someone came to our house), ఒకడు (one man/someone) is a NOUN.  

c) In "రెండో పాట", "ఒకటవ పాట" (second song, first song) etc., the inflected number word is tagged ADJ.

d) In "ఉల్లి ధర నాలుగింతలు అయింది" (Onion price increased by 4 times), "నాలుగింతలు" (4 times) is tagged ADV.

* In ordinal numbers (e.g., number expressions in మొదటి రోజు, ఒకటో పాట etc.,) the number words function as **ADJ** to the following nouns and should be tagged such. [UD guidelines](http://universaldependencies.org/u/pos/NUM.html) suggest the same.

* Multiples (రెండురెళ్ళు - two times two) when not appearing as a multi-word numeric expression, and Denominations (వందల, వందలలో, వేలలో, రూపాయలు, రూపాయలకి, పైసలు  etc) are tagged **NOUN**. 

* As UD Guidelines say, multiplicative numerals are **ADV** (e.g., మూడింతలు, రెండింతలు, పదిరెట్లు - thrice, twice, ten times etc.). But, when they appear as separate words - పది రెట్లు instead of పదిరెట్లు - is it NUM NN or NUM ADV? (We have been doing as NUM NN)




