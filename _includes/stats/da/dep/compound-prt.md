

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Danish)

This relation is a language-specific subtype of [compound]().

361 nodes (0%) are attached to their parents as `compound:prt`.

302 instances of `compound:prt` (84%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.10249307479224.

The following 6 pairs of parts of speech are connected with `compound:prt`: [da-pos/VERB]()-[da-pos/ADV]() (238; 66% instances), [da-pos/ADP]()-[da-pos/ADP]() (36; 10% instances), [da-pos/ADV]()-[da-pos/ADP]() (34; 9% instances), [da-pos/NOUN]()-[da-pos/ADV]() (27; 7% instances), [da-pos/VERB]()-[da-pos/ADP]() (22; 6% instances), [da-pos/ADV]()-[da-pos/ADV]() (4; 1% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 compound:prt	color:blue
1	Flippen	flip	NOUN	_	Definite=Def|Gender=Com|Number=Sing	2	nsubj	_	_
2	strammer	stramme	VERB	_	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_
3	til	til	ADV	_	_	2	compound:prt	_	_
4	om	om	ADP	_	AdpType=Prep	6	case	_	_
5	Peters	Peter	PROPN	_	Case=Gen	6	nmod:poss	_	_
6	hals	hals	NOUN	_	Definite=Ind|Gender=Com|Number=Sing	2	obl	_	_
7	.	.	PUNCT	_	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 8 compound:prt	color:blue
1	Er	være	AUX	_	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Act	5	cop	_	_
2	Jorden	Jorden	NOUN	_	_	5	nsubj	_	_
3	en	en	DET	_	Gender=Com|Number=Sing|PronType=Ind	5	det	_	_
4	død	død	ADJ	_	Definite=Ind|Degree=Pos|Gender=Com|Number=Sing	5	amod	_	_
5	klippe	klippe	NOUN	_	Definite=Ind|Gender=Com|Number=Sing	0	root	_	_
6	med	med	ADP	_	AdpType=Prep	7	case	_	_
7	liv	liv	NOUN	_	Definite=Ind|Gender=Neut|Number=Sing	5	nmod	_	_
8	på	på	ADP	_	AdpType=Prep	6	compound:prt	_	_
9	-	-	PUNCT	_	_	5	punct	_	_
10	eller	eller	CCONJ	_	_	5	cc	_	_
11	selv	selv	PRON	_	PronType=Dem	5	nmod	_	_
12	levende	levende	ADJ	_	Degree=Pos	5	amod	_	_
13	?	?	PUNCT	_	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 compound:prt	color:blue
1	Stakken	stak	NOUN	_	Definite=Def|Gender=Com|Number=Sing	7	nsubj	_	_
2	blev	blive	AUX	_	Mood=Ind|Tense=Past|VerbForm=Fin|Voice=Act	7	cop	_	_
3	tæt	tæt	ADV	_	Degree=Pos	6	advmod	_	_
4	på	på	ADP	_	AdpType=Prep	3	compound:prt	_	_
5	2	2	NUM	_	NumType=Card	6	nummod	_	_
6	meter	meter	NOUN	_	Definite=Ind|Gender=Com|Number=Plur	7	obl	_	_
7	høj	høj	ADJ	_	Definite=Ind|Degree=Pos|Gender=Com|Number=Sing	0	root	_	_
8	og	og	CCONJ	_	_	9	cc	_	_
9	vejede	veje	VERB	_	Mood=Ind|Tense=Past|VerbForm=Fin|Voice=Act	7	conj	_	_
10	43,5	43,5	NUM	_	NumType=Card	11	nummod	_	_
11	kg.	kilo	NOUN	_	Definite=Ind|Gender=Neut|Number=Plur	9	obj	_	_
12	.	.	PUNCT	_	_	7	punct	_	_

~~~


