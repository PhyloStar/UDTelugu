

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Danish)

This relation is universal.

28 nodes (0%) are attached to their parents as `vocative`.

17 instances of `vocative` (61%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.64285714285714.

The following 14 pairs of parts of speech are connected with `vocative`: [da-pos/VERB]()-[da-pos/PROPN]() (12; 43% instances), [da-pos/VERB]()-[da-pos/NOUN]() (3; 11% instances), [da-pos/VERB]()-[da-pos/ADJ]() (2; 7% instances), [da-pos/ADJ]()-[da-pos/NOUN]() (1; 4% instances), [da-pos/ADJ]()-[da-pos/PROPN]() (1; 4% instances), [da-pos/ADP]()-[da-pos/ADJ]() (1; 4% instances), [da-pos/ADV]()-[da-pos/NOUN]() (1; 4% instances), [da-pos/ADV]()-[da-pos/PRON]() (1; 4% instances), [da-pos/INTJ]()-[da-pos/NOUN]() (1; 4% instances), [da-pos/INTJ]()-[da-pos/PROPN]() (1; 4% instances), [da-pos/NOUN]()-[da-pos/NOUN]() (1; 4% instances), [da-pos/NOUN]()-[da-pos/PROPN]() (1; 4% instances), [da-pos/VERB]()-[da-pos/PRON]() (1; 4% instances), [da-pos/X]()-[da-pos/PROPN]() (1; 4% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 1 vocative	color:blue
1	Lotte	Lotte	PROPN	_	_	4	vocative	_	_
2	,	,	PUNCT	_	_	1	punct	_	_
3	jeg	jeg	PRON	_	Case=Nom|Gender=Com|Number=Sing|Person=1|PronType=Prs	4	nsubj	_	_
4	elsker	elske	VERB	_	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_
5	dig	du	PRON	_	Case=Acc|Gender=Com|Number=Sing|Person=2|PronType=Prs	4	obj	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 6 vocative	color:blue
1	Du	du	PRON	_	Case=Nom|Gender=Com|Number=Sing|Person=2|PronType=Prs	3	nsubj	_	_
2	sku'	skulle	AUX	_	Mood=Ind|Tense=Past|VerbForm=Fin|Voice=Act	3	aux	_	_
3	prøve	prøve	VERB	_	VerbForm=Inf|Voice=Act	0	root	_	_
4	det	det	PRON	_	Case=Acc|Gender=Neut|Number=Sing|Person=3|PronType=Prs	3	obj	_	_
5	,	,	PUNCT	_	_	3	punct	_	_
6	knægt	knægt	NOUN	_	Definite=Ind|Gender=Com|Number=Sing	3	vocative	_	_
7	.	.	PUNCT	_	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 2 vocative	color:blue
1	"	"	PUNCT	_	_	5	punct	_	_
2	Søde	sød	ADJ	_	Definite=Def|Degree=Pos|Number=Sing	5	vocative	_	_
3	,	,	PUNCT	_	_	2	punct	_	_
4	hvad	hvad	PRON	_	Number=Sing|PronType=Int,Rel	5	obj	_	_
5	gør	gøre	VERB	_	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_
6	jeg	jeg	PRON	_	Case=Nom|Gender=Com|Number=Sing|Person=1|PronType=Prs	5	nsubj	_	_
7	med	med	ADP	_	AdpType=Prep	9	case	_	_
8	mine	min	DET	_	Number=Plur|Number[psor]=Sing|Person=1|Poss=Yes|PronType=Prs	9	det	_	_
9	proteiner	protein	NOUN	_	Definite=Ind|Gender=Neut|Number=Plur	5	obl	_	_
10	hvis	hvis	SCONJ	_	_	12	mark	_	_
11	jeg	jeg	PRON	_	Case=Nom|Gender=Com|Number=Sing|Person=1|PronType=Prs	12	nsubj	_	_
12	får	få	VERB	_	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Act	5	advmod	_	_
13	lyst	lyst	NOUN	_	Definite=Ind|Gender=Com|Number=Sing	12	obj	_	_
14	til	til	ADP	_	AdpType=Prep	16	mark	_	_
15	at	at	PART	_	PartType=Inf	16	mark	_	_
16	fyre	fyre	VERB	_	VerbForm=Inf|Voice=Act	13	advcl	_	_
17	en	en	DET	_	Gender=Com|Number=Sing|PronType=Ind	18	det	_	_
18	spiller	spiller	NOUN	_	Definite=Ind|Gender=Com|Number=Sing	16	obj	_	_
19	?	?	PUNCT	_	_	5	punct	_	_
20	"	"	PUNCT	_	_	5	punct	_	_

~~~


