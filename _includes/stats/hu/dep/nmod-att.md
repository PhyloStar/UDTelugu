

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Hungarian)

This relation is a language-specific subtype of [nmod]().
There are also 3 other language-specific subtypes of `nmod`: [nmod:attlvc](), [nmod:obl](), [nmod:obllvc]().

1920 nodes (6%) are attached to their parents as `nmod:att`.

1875 instances of `nmod:att` (98%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.03802083333333.

The following 22 pairs of parts of speech are connected with `nmod:att`: [hu-pos/NOUN]()-[hu-pos/NOUN]() (1249; 65% instances), [hu-pos/NOUN]()-[hu-pos/PROPN]() (347; 18% instances), [hu-pos/NOUN]()-[hu-pos/PRON]() (96; 5% instances), [hu-pos/ADJ]()-[hu-pos/NOUN]() (81; 4% instances), [hu-pos/ADJ]()-[hu-pos/PROPN]() (45; 2% instances), [hu-pos/VERB]()-[hu-pos/NOUN]() (21; 1% instances), [hu-pos/PROPN]()-[hu-pos/PROPN]() (11; 1% instances), [hu-pos/VERB]()-[hu-pos/PRON]() (11; 1% instances), [hu-pos/NOUN]()-[hu-pos/ADJ]() (10; 1% instances), [hu-pos/PRON]()-[hu-pos/NOUN]() (9; 0% instances), [hu-pos/NUM]()-[hu-pos/NOUN]() (8; 0% instances), [hu-pos/PROPN]()-[hu-pos/NOUN]() (8; 0% instances), [hu-pos/NOUN]()-[hu-pos/NUM]() (6; 0% instances), [hu-pos/VERB]()-[hu-pos/PROPN]() (4; 0% instances), [hu-pos/NOUN]()-[hu-pos/X]() (3; 0% instances), [hu-pos/PRON]()-[hu-pos/PRON]() (3; 0% instances), [hu-pos/ADJ]()-[hu-pos/ADJ]() (2; 0% instances), [hu-pos/ADJ]()-[hu-pos/PRON]() (2; 0% instances), [hu-pos/ADJ]()-[hu-pos/VERB]() (1; 0% instances), [hu-pos/ADV]()-[hu-pos/NOUN]() (1; 0% instances), [hu-pos/PROPN]()-[hu-pos/ADJ]() (1; 0% instances), [hu-pos/PROPN]()-[hu-pos/PRON]() (1; 0% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 8 nmod:att	color:blue
1	Az	az	DET	_	Definite=Def|PronType=Art	5	det	_	_
2	utolsó	utolsó	ADJ	_	Case=Nom|Degree=Pos|Number=Sing|Number[psed]=None|Number[psor]=None|Person[psor]=None	5	amod:att	_	_
3	hat	hat	NUM	_	Case=Nom|Number=Sing|Number[psed]=None|Number[psor]=None|NumType=Card|Person[psor]=None	4	nummod	_	_
4	hónapos	hónapos	ADJ	_	Case=Nom|Degree=Pos|Number=Sing|Number[psed]=None|Number[psor]=None|Person[psor]=None	5	amod:att	_	_
5	időszak	időszak	NOUN	_	Case=Nom|Number=Sing|Number[psed]=None|Number[psor]=None|Person[psor]=None	10	nsubj	_	_
6	azonban	azonban	CCONJ	_	_	10	cc	_	_
7	a	a	DET	_	Definite=Def|PronType=Art	8	det	_	_
8	hét	hét	NOUN	_	Case=Nom|Number=Sing|Number[psed]=None|Number[psor]=None|Person[psor]=None	9	nmod:att	_	_
9	elején	eleje	NOUN	_	Case=Sup|Number=Sing|Number[psed]=None|Number[psor]=Sing|Person[psor]=3	10	nmod:obl	_	_
10	lejárt	le+jár	VERB	_	Definite=Ind|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	SpaceAfter=No
11	.	.	PUNCT	_	_	10	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 nmod:att	color:blue
1	Szakmai	szakmai	ADJ	_	Case=Nom|Degree=Pos|Number=Sing|Number[psed]=None|Number[psor]=None|Person[psor]=None	2	amod:att	_	_
2	szervezetek	szervezet	NOUN	_	Case=Nom|Number=Plur|Number[psed]=None|Number[psor]=None|Person[psor]=None	4	nsubj	_	_
3	is	is	CCONJ	_	_	2	cc	_	ToDo=cc-without-conj
4	tiltakoznak	tiltakozik	VERB	_	Definite=Ind|Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_
5	Jeszenszky	Jeszenszky	PROPN	_	Case=Nom|Number=Sing|Number[psed]=None|Number[psor]=None|Person[psor]=None	6	nmod:att	_	_
6	levele	levél	NOUN	_	Case=Nom|Number=Sing|Number[psed]=None|Number[psor]=Sing|Person[psor]=3	4	obl	_	_
7	ellen	ellen	ADP	_	_	6	case	_	SpaceAfter=No
8	.	.	PUNCT	_	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 nmod:att	color:blue
1	"	"	PUNCT	_	_	6	punct	_	SpaceAfter=No
2	Az	az	DET	_	Definite=Def|PronType=Art	4	det	_	_
3	ő	ő	PRON	_	Case=Nom|Number=Sing|Number[psed]=None|Number[psor]=None|Person=3|Person[psor]=None|PronType=Prs	4	nmod:att	_	_
4	kocsija	kocsi	NOUN	_	Case=Nom|Number=Sing|Number[psed]=None|Number[psor]=Sing|Person[psor]=3	6	nsubj	_	_
5	mindenhol	mindenhol	ADV	_	PronType=Tot	6	advmod:locy	_	_
6	átmegy	át+megy	VERB	_	Definite=Ind|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	SpaceAfter=No
7	.	.	PUNCT	_	_	6	punct	_	SpaceAfter=No
8	"	"	PUNCT	_	_	6	punct	_	_

~~~


