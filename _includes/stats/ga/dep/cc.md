

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Irish)

This relation is universal.

408 nodes (3%) are attached to their parents as `cc`.

407 instances of `cc` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.0171568627451.

The following 15 pairs of parts of speech are connected with `cc`: [ga-pos/NOUN]()-[ga-pos/CCONJ]() (218; 53% instances), [ga-pos/VERB]()-[ga-pos/CCONJ]() (94; 23% instances), [ga-pos/ADJ]()-[ga-pos/CCONJ]() (25; 6% instances), [ga-pos/ADP]()-[ga-pos/CCONJ]() (24; 6% instances), [ga-pos/PRON]()-[ga-pos/CCONJ]() (11; 3% instances), [ga-pos/PROPN]()-[ga-pos/CCONJ]() (11; 3% instances), [ga-pos/NUM]()-[ga-pos/CCONJ]() (9; 2% instances), [ga-pos/ADV]()-[ga-pos/CCONJ]() (4; 1% instances), [ga-pos/SCONJ]()-[ga-pos/CCONJ]() (3; 1% instances), [ga-pos/X]()-[ga-pos/CCONJ]() (3; 1% instances), [ga-pos/NOUN]()-[ga-pos/PUNCT]() (2; 0% instances), [ga-pos/ADJ]()-[ga-pos/SCONJ]() (1; 0% instances), [ga-pos/NOUN]()-[ga-pos/SCONJ]() (1; 0% instances), [ga-pos/PART]()-[ga-pos/CCONJ]() (1; 0% instances), [ga-pos/VERB]()-[ga-pos/SCONJ]() (1; 0% instances).


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 7 cc	color:blue
1	Bronnfar	bronn	VERB	VT	Mood=Ind|Tense=Fut|Voice=Auto	0	root	_	_
2	é	é	PRON	Pers	Gender=Masc|Number=Sing|Person=3	1	obj	_	_
3	ar	ar	ADP	Simp	_	5	case	_	_
4	an	an	DET	Art	Definite=Def|Number=Sing|PronType=Art	5	det	_	_
5	Chnuasach	cnuasach	NOUN	Noun	Case=NomAcc|Form=Len|Gender=Masc|Number=Sing	1	obl	_	_
6	Gearrscéalta	gearrscéal	NOUN	Noun	Case=Gen|Gender=Masc|NounType=Strong|Number=Plur	5	compound	_	_
7	nó	nó	CCONJ	Coord	_	9	cc	_	_
8	an	an	DET	Art	Definite=Def|Number=Sing|PronType=Art	9	det	_	_
9	dráma	dráma	NOUN	Noun	Case=NomAcc|Definite=Def|Gender=Masc|Number=Sing	5	conj	_	_
10	is	is	PART	Sup	_	11	mark:prt	_	_
11	fearr	maith	ADJ	Adj	Degree=Cmp,Sup	5	amod	_	SpaceAfter=No
12	.	.	PUNCT	.	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 4 cc	color:blue
1	D'	do	PART	Vb	PartType=Vb	2	mark:prt	_	SpaceAfter=No
2	iúntaigh	iúntaigh	NOUN	Noun	Case=NomAcc|Gender=Fem|Number=Sing	0	root	_	_
3	Pinocchio	Pinocchio	PROPN	Noun	Case=NomAcc|Gender=Masc|Number=Sing	4	nsubj	_	_
4	agus	agus	CCONJ	Coord	_	6	cc	_	_
5	d'	do	PART	Vb	PartType=Vb	6	mark:prt	_	SpaceAfter=No
6	fhéach	féach	VERB	VTI	Form=Len|Mood=Ind|Tense=Past	2	conj	_	_
7	sé	sé	PRON	Pers	Gender=Masc|Number=Sing|Person=3	6	nsubj	_	_
8	air	ar	ADP	Prep	Gender=Masc|Number=Sing|Person=3	6	obl:prep	_	SpaceAfter=No
9	.	.	PUNCT	.	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 12 10 cc	color:blue
1	Thiocfadh	tar	VERB	VI	Form=Len|Mood=Cnd	0	root	_	_
2	leat	le	ADP	Prep	Number=Sing|Person=2	1	obl:prep	_	_
3	caint	caint	NOUN	Noun	VerbForm=Inf	1	nsubj	_	_
4	agus	agus	CCONJ	Coord	_	5	cc	_	_
5	scríobh	scríobh	NOUN	Noun	VerbForm=Inf	3	conj	_	_
6	fá	faoi	X	CU	Dialect=Ulster|Gender=Masc|Number=Sing|Person=3	7	case	_	_
7	seo	seo	PRON	Dem	PronType=Dem	3	nmod	_	_
8	go	go	PART	Ad	PartType=Ad	9	mark:prt	_	_
9	minic	minic	ADJ	Adj	Degree=Pos	1	advmod	_	_
10	agus	agus	CCONJ	Coord	_	12	cc	_	_
11	go	go	PART	Ad	PartType=Ad	12	mark:prt	_	_
12	fada	fada	ADJ	Adj	Degree=Pos	9	conj	_	SpaceAfter=No
13	.	.	PUNCT	.	_	1	punct	_	_

~~~


