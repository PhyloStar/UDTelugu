

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Slovak)

This relation is a language-specific subtype of [csubj]().

13 nodes (0%) are attached to their parents as `csubj:pass`.

13 instances of `csubj:pass` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 5.46153846153846.

The following 3 pairs of parts of speech are connected with `csubj:pass`: [sk-pos/VERB]()-[sk-pos/VERB]() (9; 69% instances), [sk-pos/VERB]()-[sk-pos/NOUN]() (3; 23% instances), [sk-pos/ADJ]()-[sk-pos/VERB]() (1; 8% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 csubj:pass	color:blue
1	Obom	oba	NUM	NNmp3	Animacy=Anim|Case=Dat|Gender=Masc|Number=Plur	3	obj	_	_
2	sa	sa	PRON	R	PronType=Prs|Reflex=Yes	3	expl:pass	_	_
3	chcelo	chcieť	VERB	VLescn+	Aspect=Imp|Gender=Neut|Number=Sing|Person=3|Polarity=Pos|Tense=Past|VerbForm=Part	0	root	_	_
4	spať	spať	VERB	VIe+	Aspect=Imp|Polarity=Pos|VerbForm=Inf	3	csubj:pass	_	SpaceAfter=No
5	.	.	PUNCT	ZIP	VerbForm=Inf	3	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 8 csubj:pass	color:blue
1	Predpokladá	predpokladať	VERB	VKesc+	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin	0	root	_	_
2	sa	sa	PRON	R	PronType=Prs|Reflex=Yes	1	expl:pass	_	SpaceAfter=No
3	,	,	PUNCT	Z	_	8	punct	_	_
4	že	že	SCONJ	O	_	8	mark	_	_
5	toto	toto	DET	PFns1	Case=Nom|Gender=Neut|Number=Sing|PronType=Dem	6	det	_	_
6	hélium	hélium	NOUN	SSns1	Case=Nom|Gender=Neut|Number=Sing	8	nsubj	_	_
7	je	byť	AUX	VKesc+	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin	8	cop	_	_
8	produktom	produkt	NOUN	SSis7	Animacy=Inan|Case=Ins|Gender=Masc|Number=Sing	1	csubj:pass	_	_
9	jadrového	jadrový	ADJ	AAis2x	Animacy=Inan|Case=Gen|Degree=Pos|Gender=Masc|Number=Sing	10	amod	_	_
10	rozpadu	rozpad	NOUN	SSis2	Animacy=Inan|Case=Gen|Gender=Masc|Number=Sing	8	nmod	_	_
11	prvkov	prvok	NOUN	SSip2	Animacy=Inan|Case=Gen|Gender=Masc|Number=Plur	10	nmod	_	_
12	v	v	ADP	Eu6	AdpType=Prep|Case=Loc	14	case	_	_
13	zemskej	zemský	ADJ	AAfs6x	Case=Loc|Degree=Pos|Gender=Fem|Number=Sing	14	amod	_	_
14	kôre	kôra	NOUN	SSfs6	Case=Loc|Gender=Fem|Number=Sing	11	nmod	_	SpaceAfter=No
15	.	.	PUNCT	Z	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 11 12 csubj:pass	color:blue
1	Jeho	jeho	DET	PUfp1	Case=Nom|Gender=Fem|Gender[psor]=Masc,Neut|Number=Plur|Number[psor]=Sing|Poss=Yes|PronType=Prs	2	det	_	_
2	knihy	kniha	NOUN	SSfp1	Case=Nom|Gender=Fem|Number=Plur	4	nsubj:pass	_	_
3	boli	byť	AUX	VLepcf+	Aspect=Imp|Gender=Fem|Number=Plur|Person=3|Polarity=Pos|Tense=Past|VerbForm=Part	4	aux:pass	_	_
4	odstránené	odstránený	ADJ	Gtfp1x	Case=Nom|Degree=Pos|Gender=Fem|Number=Plur|Polarity=Pos|VerbForm=Part|Voice=Pass	0	root	_	_
5	z	z	ADP	Eu2	AdpType=Prep|Case=Gen	7	case	_	_
6	verejných	verejný	ADJ	AAfp2x	Case=Gen|Degree=Pos|Gender=Fem|Number=Plur	7	amod	_	_
7	knižníc	knižnica	NOUN	SSfp2	Case=Gen|Gender=Fem|Number=Plur	4	obl	_	_
8	a	a	CCONJ	O	_	11	cc	_	_
9	bolo	byť	AUX	VLescn+	Aspect=Imp|Gender=Neut|Number=Sing|Person=3|Polarity=Pos|Tense=Past|VerbForm=Part	11	aux:pass	_	_
10	mu	on	PRON	PFms3	Animacy=Anim|Case=Dat|Gender=Masc|Number=Sing|PronType=Prs	11	obj	_	_
11	bránené	bránený	ADJ	Gtns1x	Case=Nom|Degree=Pos|Gender=Neut|Number=Sing|Polarity=Pos|VerbForm=Part|Voice=Pass	4	conj	_	_
12	vykonávať	vykonávať	VERB	VIe+	Aspect=Imp|Polarity=Pos|VerbForm=Inf	11	csubj:pass	_	_
13	akékoľvek	akýkoľvek	DET	PAns4	Case=Acc|Gender=Neut|Number=Sing|PronType=Ind	15	det	_	_
14	zárobkové	zárobkový	ADJ	AAns4x	Case=Acc|Degree=Pos|Gender=Neut|Number=Sing	15	amod	_	_
15	povolanie	povolanie	NOUN	SSns4	Case=Acc|Gender=Neut|Number=Sing	12	obj	_	SpaceAfter=No
16	.	.	PUNCT	Z	_	4	punct	_	_

~~~


