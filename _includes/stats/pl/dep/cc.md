

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Polish)

This relation is universal.

1509 nodes (2%) are attached to their parents as `cc`.

1509 instances of `cc` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.779324055666.

The following 11 pairs of parts of speech are connected with `cc`: [pl-pos/VERB]()-[pl-pos/CCONJ]() (684; 45% instances), [pl-pos/NOUN]()-[pl-pos/CCONJ]() (562; 37% instances), [pl-pos/ADJ]()-[pl-pos/CCONJ]() (152; 10% instances), [pl-pos/PROPN]()-[pl-pos/CCONJ]() (77; 5% instances), [pl-pos/NUM]()-[pl-pos/CCONJ]() (12; 1% instances), [pl-pos/PRON]()-[pl-pos/CCONJ]() (10; 1% instances), [pl-pos/AUX]()-[pl-pos/CCONJ]() (6; 0% instances), [pl-pos/DET]()-[pl-pos/CCONJ]() (2; 0% instances), [pl-pos/NOUN]()-[pl-pos/PART]() (2; 0% instances), [pl-pos/NOUN]()-[pl-pos/NUM]() (1; 0% instances), [pl-pos/VERB]()-[pl-pos/PART]() (1; 0% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 4 cc	color:blue
1	Albo	albo	CCONJ	conj	_	2	advmod	_	_
2	jest	być	VERB	fin:sg:ter:imperf	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	SpaceAfter=No
3	,	,	PUNCT	interp	_	7	punct	_	_
4	ale	ale	CCONJ	conj	_	7	cc	_	_
5	niczego	nic	PRON	subst:sg:gen:n	Case=Gen|Gender=Neut|Number=Sing|PronType=Neg	7	obj	_	_
6	nie	nie	PART	qub	_	7	advmod	_	_
7	otwiera	otwierać	VERB	fin:sg:ter:imperf	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	2	conj	_	SpaceAfter=No
8	.	.	PUNCT	interp	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 8 cc	color:blue
1	Będziesz	być	AUX	bedzie:sg:sec:imperf	Aspect=Imp|Mood=Ind|Number=Sing|Person=2|Tense=Fut|VerbForm=Fin	2	aux	_	_
2	mieć	mieć	VERB	inf:imperf	Aspect=Imp|VerbForm=Inf	0	root	_	_
3	prawdopodobnie	prawdopodobnie	ADV	adv:pos	Degree=Pos	2	advmod	_	_
4	zyski	zysk	NOUN	subst:pl:acc:m3	Animacy=Inan|Case=Acc|Gender=Masc|Number=Plur	2	obj	_	_
5	dzięki	dzięki	ADP	prep:dat	AdpType=Prep|Case=Dat	7	case	_	_
6	swej	swój	DET	adj:sg:dat:f:pos	Case=Dat|Gender=Fem|Number=Sing|Poss=Yes|PronType=Prs|Reflex=Yes	7	det	_	_
7	pracy	praca	NOUN	subst:sg:dat:f	Case=Dat|Gender=Fem|Number=Sing	2	obl	_	_
8	i	i	CCONJ	conj	_	9	cc	_	_
9	zawodowi	zawód	NOUN	subst:sg:dat:m3	Animacy=Inan|Case=Dat|Gender=Masc|Number=Sing	7	conj	_	SpaceAfter=No
10	.	.	PUNCT	interp	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 4 cc	color:blue
1	Pokonał	pokonać	VERB	praet:sg:m1:perf	Animacy=Hum|Aspect=Perf|Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part|Voice=Act	0	root	_	_
2	nieznane	nieznane	NOUN	subst:sg:acc:n	Case=Acc|Gender=Neut|Number=Sing	1	obj	_	SpaceAfter=No
3	,	,	PUNCT	interp	_	8	punct	_	_
4	ale	ale	CCONJ	conj	_	8	cc	_	_
5	nie	nie	PART	qub	_	8	advmod	_	_
6	było	być	AUX	praet:sg:n:imperf	Aspect=Imp|Gender=Neut|Number=Sing|Tense=Past|VerbForm=Part|Voice=Act	8	cop	_	_
7	mu	on	PRON	ppron3:sg:dat:m1:ter:nakc:npraep	Animacy=Hum|Case=Dat|Gender=Masc|Number=Sing|Person=3|PrepCase=Npr|PronType=Prs|Variant=Short	8	obj	_	_
8	dane	dany	ADJ	adj:sg:nom:acc:n:pos	Case=Acc|Degree=Pos|Gender=Neut|Number=Sing	1	conj	_	_
9	opowiedzieć	opowiedzieć	VERB	inf:perf	Aspect=Perf|VerbForm=Inf	8	xcomp	_	_
10	o	o	ADP	prep:loc	AdpType=Prep|Case=Loc	11	case	_	_
11	tym	to	PRON	subst:sg:loc:n	Case=Loc|Gender=Neut|Number=Sing|PronType=Dem	9	obj	_	SpaceAfter=No
12	.	.	PUNCT	interp	_	1	punct	_	SpaceAfter=No
13	.	.	PUNCT	interp	_	1	punct	_	SpaceAfter=No
14	.	.	PUNCT	interp	_	1	punct	_	_

~~~


