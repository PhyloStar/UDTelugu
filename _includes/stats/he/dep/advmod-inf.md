

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Hebrew)

This relation is a language-specific subtype of [advmod]().
There are also 1 other language-specific subtypes of `advmod`: [advmod:phrase]().

12 nodes (0%) are attached to their parents as `advmod:inf`.

12 instances of `advmod:inf` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.16666666666667.

The following 2 pairs of parts of speech are connected with `advmod:inf`: [he-pos/NOUN]()-[he-pos/VERB]() (10; 83% instances), [he-pos/ADV]()-[he-pos/VERB]() (2; 17% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 advmod:inf	color:blue
1	עכשיו	עכשיו	ADV	ADV	_	2	advmod	_	_
2	עת	עת	NOUN	NOUN	Gender=Fem|Number=Sing	0	root	_	_
3	להרוג	הרג	VERB	VERB	HebBinyan=PAAL|VerbForm=Inf|Voice=Act	2	advmod:inf	_	_
4	.	_	PUNCT	PUNCT	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 18	bgColor:blue
# visual-style 18	fgColor:white
# visual-style 17	bgColor:blue
# visual-style 17	fgColor:white
# visual-style 17 18 advmod:inf	color:blue
1	ב	ב	ADP	ADP	_	4	case	_	_
2	כל	כול	DET	DET	Definite=Cons	4	det	_	_
3	ה	ה	SCONJ	SCONJ	_	4	mark	_	_
4	קשור	קשר	VERB	VERB	Gender=Masc|HebBinyan=PAAL|Number=Sing|Person=1,2,3|VerbForm=Part|Voice=Act	13	obl	_	_
5	ל	ל	ADP	ADP	_	6	case	_	_
6	סדרי	סדר	NOUN	NOUN	Definite=Cons|Gender=Masc|Number=Plur	4	iobj	_	_
7	ה	ה	DET	DET	PronType=Art	8	det:def	_	_
8	כניסה	כניסה	NOUN	NOUN	Gender=Fem|Number=Sing	6	compound:smixut	_	_
9	ו	ו	CCONJ	CCONJ	_	11	cc	_	_
10	ה	ה	DET	DET	PronType=Art	11	det:def	_	_
11	יציאה	יציאה	NOUN	NOUN	Gender=Fem|Number=Sing	8	conj	_	_
12	,	_	PUNCT	PUNCT	_	13	punct	_	_
13	יש	יש	VERB	VERB	HebExistential=True	0	root	_	_
14	ל	ל	ADP	ADP	_	15	case	_	_
15	יוניוורסל	יוניוורסל	PROPN	PROPN	_	13	obl	_	_
16	הרבה	הרבה	DET	DET	Definite=Cons	17	det	_	_
17	מה	מה	ADV	ADV	PronType=Int	13	nsubj	_	_
18	לשפר	שיפר	VERB	VERB	HebBinyan=PIEL|VerbForm=Inf|Voice=Act	17	advmod:inf	_	_
19	.	_	PUNCT	PUNCT	_	13	punct	_	_

~~~


