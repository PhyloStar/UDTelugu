

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Lithuanian)

This relation is universal.

262 nodes (5%) are attached to their parents as `obj`.

161 instances of `obj` (61%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.22519083969466.

The following 16 pairs of parts of speech are connected with `obj`: [lt-pos/VERB]()-[lt-pos/NOUN]() (171; 65% instances), [lt-pos/VERB]()-[lt-pos/PRON]() (52; 20% instances), [lt-pos/VERB]()-[lt-pos/ADJ]() (8; 3% instances), [lt-pos/VERB]()-[lt-pos/PROPN]() (8; 3% instances), [lt-pos/ADJ]()-[lt-pos/NOUN]() (6; 2% instances), [lt-pos/ADJ]()-[lt-pos/PRON]() (5; 2% instances), [lt-pos/VERB]()-[lt-pos/DET]() (3; 1% instances), [lt-pos/ADJ]()-[lt-pos/PROPN]() (1; 0% instances), [lt-pos/ADV]()-[lt-pos/NOUN]() (1; 0% instances), [lt-pos/NOUN]()-[lt-pos/NOUN]() (1; 0% instances), [lt-pos/NOUN]()-[lt-pos/PRON]() (1; 0% instances), [lt-pos/PART]()-[lt-pos/NOUN]() (1; 0% instances), [lt-pos/PRON]()-[lt-pos/NOUN]() (1; 0% instances), [lt-pos/PROPN]()-[lt-pos/PROPN]() (1; 0% instances), [lt-pos/VERB]()-[lt-pos/PART]() (1; 0% instances), [lt-pos/VERB]()-[lt-pos/VERB]() (1; 0% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 11 8 obj	color:blue
1	Kiti	kitas	PRON	DT	Case=Nom|Gender=Masc|Number=Plur	11	nsubj	_	En=other|SpaceAfter=No
2	,	,	PUNCT	PUNCT	_	4	punct	_	En=,
3	kaip	kaip	SCONJ	UH	_	4	mark	_	En=how
4	žinoma	žinoti	VERB	VBNH	Definite=Ind|Gender=Neut|Polarity=Pos|Reflex=No|Tense=Pres|VerbForm=Part|Voice=Pass	11	parataxis	_	En=of_course|SpaceAfter=No
5	,	,	PUNCT	PUNCT	_	4	punct	_	En=,
6	aiškios	aiškus	ADJ	JJL	Case=Gen|Definite=Ind|Degree=Pos|Gender=Fem|Number=Sing	8	amod	_	En=obviuos
7	tautinės	tautinis	ADJ	JJL	Case=Gen|Definite=Ind|Degree=Pos|Gender=Fem|Number=Sing	8	amod	_	En=ethnic
8	sąmonės	sąmonė	NOUN	NN	Case=Gen|Gender=Fem|Number=Sing	11	obj	_	En=consciousness
9	iš	iš	ADP	UH	_	10	case	_	En=from
10	vis	vis	ADV	RB	Degree=Pos	11	obl	_	En=still
11	neturėjo	turėti	VERB	VBC	Mood=Ind|Number=Plur|Person=3|Polarity=Neg|Reflex=No|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	En=have|SpaceAfter=No
12	.	.	PUNCT	PUNCT	_	11	punct	_	En=.

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 5 obj	color:blue
1	Santykiuose	santykis	NOUN	NN	Case=Loc|Gender=Masc|Number=Plur	4	obl	_	En=relations
2	su	su	ADP	UH	_	3	case	_	En=with
3	žydais	žydas	NOUN	NN	Case=Ins|Gender=Masc|Number=Plur	1	nmod	_	En=Jews
4	nematyti	matyti	VERB	VB	Polarity=Neg|Reflex=No|VerbForm=Inf|Voice=Act	0	root	_	En=see
5	nieko	niekas	PRON	DT	Case=Gen|Gender=Masc|Number=Sing	4	obj	_	En=nothing
6	naujo	naujas	ADJ	JJL	Case=Gen|Definite=Ind|Degree=Pos|Gender=Masc|Number=Sing	5	amod	_	En=new|SpaceAfter=No
7	.	.	PUNCT	PUNCT	_	4	punct	_	En=.

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 7 obj	color:blue
1	Šiose	šis	DET	DT	Case=Loc|Gender=Fem|Number=Plur	2	det	_	En=this
2	srityse	sritis	NOUN	NN	Case=Loc|Gender=Fem|Number=Plur	9	obl	_	En=domain|SpaceAfter=No
3	,	,	PUNCT	PUNCT	_	4	punct	_	En=,
4	deja	deja	INTJ	UH	_	9	parataxis	_	En=unfortunately|SpaceAfter=No
5	,	,	PUNCT	PUNCT	_	4	punct	_	En=,
6	dar	dar	ADV	RB	Degree=Pos	9	advmod	_	En=yet
7	maža	mažas	ADJ	PRED	Definite=Ind|Degree=Pos|Gender=Neut	10	obj	_	En=little
8	kuo	kas	PRON	WP	Case=Ins	7	fixed	_	En=one
9	galime	galėti	VERB	VBC	Mood=Ind|Number=Plur|Person=1|Polarity=Pos|Reflex=No|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	En=can
10	didžiuotis	didžiuotis	VERB	VB	Polarity=Pos|Reflex=Yes|VerbForm=Inf|Voice=Act	9	xcomp	_	En=be_proud_of|SpaceAfter=No
11	.	.	PUNCT	PUNCT	_	9	punct	_	En=.

~~~


