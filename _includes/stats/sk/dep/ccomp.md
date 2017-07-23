

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Slovak)

This relation is universal.

1210 nodes (1%) are attached to their parents as `ccomp`.

655 instances of `ccomp` (54%) are left-to-right (parent precedes child).
Average distance between parent and child is 5.01074380165289.

The following 9 pairs of parts of speech are connected with `ccomp`: [sk-pos/VERB]()-[sk-pos/VERB]() (1021; 84% instances), [sk-pos/VERB]()-[sk-pos/NOUN]() (81; 7% instances), [sk-pos/VERB]()-[sk-pos/ADJ]() (78; 6% instances), [sk-pos/VERB]()-[sk-pos/PRON]() (12; 1% instances), [sk-pos/ADJ]()-[sk-pos/VERB]() (9; 1% instances), [sk-pos/VERB]()-[sk-pos/DET]() (4; 0% instances), [sk-pos/VERB]()-[sk-pos/NUM]() (2; 0% instances), [sk-pos/VERB]()-[sk-pos/PROPN]() (2; 0% instances), [sk-pos/VERB]()-[sk-pos/ADV]() (1; 0% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 8 ccomp	color:blue
1	Väčšina	väčšina	NOUN	SSfs1	Case=Nom|Gender=Fem|Number=Sing	4	nsubj	_	_
2	zdrojov	zdroj	NOUN	SSip2	Animacy=Inan|Case=Gen|Gender=Masc|Number=Plur	1	nmod	_	_
3	však	však	PART	T	_	4	advmod	_	_
4	uvádza	uvádzať	VERB	VKesc+	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin	0	root	_	SpaceAfter=No
5	,	,	PUNCT	ZIP	VerbForm=Inf	8	punct	_	_
6	že	že	SCONJ	O	_	8	mark	_	_
7	by	by	AUX	Y	Mood=Cnd	8	aux	_	_
8	mal	mať	VERB	VLescm+	Animacy=Anim|Aspect=Imp|Gender=Masc|Number=Sing|Person=3|Polarity=Pos|Tense=Past|VerbForm=Part	4	ccomp	_	_
9	byť	byť	VERB	VIe+	Aspect=Imp|Polarity=Pos|VerbForm=Inf	8	xcomp	_	_
10	v	v	ADP	Eu6	AdpType=Prep|Case=Loc	11	case	_	_
11	Šanghaji	šanghaj	PROPN	SSis6:r	Animacy=Inan|Case=Loc|Gender=Masc|Number=Sing	9	obl	_	SpaceAfter=No
12	.	.	PUNCT	ZIP	VerbForm=Inf	4	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 4 ccomp	color:blue
1	To	to	DET	PFns1	Case=Nom|Gender=Neut|Number=Sing|PronType=Dem	4	nsubj	_	_
2	je	byť	AUX	VKesc+	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin	4	cop	_	_
3	fantastická	fantastický	ADJ	AAfs1x	Case=Nom|Degree=Pos|Gender=Fem|Number=Sing	4	amod	_	_
4	novina	novina	NOUN	SSfs1	Case=Nom|Gender=Fem|Number=Sing	7	ccomp	_	SpaceAfter=No
5	!	!	PUNCT	Z	_	4	punct	_	SpaceAfter=No
6	“	“	PUNCT	Z	_	4	punct	_	_
7	zvolala	zvolať	VERB	VLdsaf+	Aspect=Perf|Gender=Fem|Number=Sing|Person=1|Polarity=Pos|Tense=Past|VerbForm=Part	0	root	_	_
8	som	byť	AUX	VKesa+	Aspect=Imp|Mood=Ind|Number=Sing|Person=1|Polarity=Pos|Tense=Pres|VerbForm=Fin	7	aux	_	_
9	a	a	CCONJ	O	_	10	cc	_	_
10	objala	objať	VERB	VLdsaf+	Aspect=Perf|Gender=Fem|Number=Sing|Person=1|Polarity=Pos|Tense=Past|VerbForm=Part	7	conj	_	_
11	ju	ona	PRON	PFfs4	Case=Acc|Gender=Fem|Number=Sing|PronType=Prs	10	obj	_	SpaceAfter=No
12	.	.	PUNCT	Z	_	7	punct	_	_

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 10 ccomp	color:blue
1	Ako	ako	SCONJ	O	_	2	mark	_	_
2	dôvod	dôvod	NOUN	SSis4	Animacy=Inan|Case=Acc|Gender=Masc|Number=Sing	4	xcomp	_	_
3	administratíva	administratíva	NOUN	SSfs1	Case=Nom|Gender=Fem|Number=Sing	4	nsubj	_	_
4	uviedla	uviesť	VERB	VLdscf+	Aspect=Perf|Gender=Fem|Number=Sing|Person=3|Polarity=Pos|Tense=Past|VerbForm=Part	0	root	_	SpaceAfter=No
5	,	,	PUNCT	Z	_	10	punct	_	_
6	že	že	SCONJ	O	_	10	mark	_	_
7	už	už	PART	T	_	10	advmod	_	_
8	nie	nie	PART	T	_	10	advmod	_	_
9	je	byť	AUX	VKesc-	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Neg|Tense=Pres|VerbForm=Fin	10	cop	_	_
10	relevantná	relevantný	ADJ	AAfs1x	Case=Nom|Degree=Pos|Gender=Fem|Number=Sing	4	ccomp	_	SpaceAfter=No
11	.	.	PUNCT	Z	_	4	punct	_	_

~~~


