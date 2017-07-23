

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Czech)

This relation is a language-specific subtype of [aux]().

5382 nodes (0%) are attached to their parents as `aux:pass`.

5272 instances of `aux:pass` (98%) are right-to-left (child precedes parent).
Average distance between parent and child is 2.25083612040134.

The following 1 pairs of parts of speech are connected with `aux:pass`: [cs-pos/ADJ]()-[cs-pos/AUX]() (5382; 100% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 aux:pass	color:blue
1	Na	na	ADP	RR--4----------	AdpType=Prep|Case=Acc	2	case	_	LId=na-1
2	požádání	požádání	NOUN	NNNS4-----A----	Case=Acc|Gender=Neut|Number=Sing|Polarity=Pos	5	obl	_	LDeriv=požádat
3	může	moci	VERB	VB-S---3P-AA---	Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	LGloss=(mít_možnost_[něco_dělat])
4	být	být	AUX	Vf--------A----	Polarity=Pos|VerbForm=Inf	5	aux:pass	_	_
5	zaslán	zaslaný	ADJ	VsYS---XX-AP---	Gender=Masc|Number=Sing|Polarity=Pos|Variant=Short|VerbForm=Part|Voice=Pass	3	obj	_	_
6	seznam	seznam	NOUN	NNIS1-----A----	Animacy=Inan|Case=Nom|Gender=Masc|Number=Sing|Polarity=Pos	3	nsubj	_	_
7	firem	firma	NOUN	NNFP2-----A----	Case=Gen|Gender=Fem|Number=Plur|Polarity=Pos	6	nmod	_	SpaceAfter=No
8	.	.	PUNCT	Z:-------------	_	3	punct	_	_

~~~




--------------------------------------------------------------------------------

## Treebank Statistics (UD_Czech-CAC)

This relation is a language-specific subtype of [aux]().

2496 nodes (1%) are attached to their parents as `aux:pass`.

2475 instances of `aux:pass` (99%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.98277243589744.

The following 4 pairs of parts of speech are connected with `aux:pass`: [cs-pos/ADJ]()-[cs-pos/AUX]() (2485; 100% instances), [cs-pos/ADJ]()-[cs-pos/SYM]() (9; 0% instances), [cs-pos/ADJ]()-[cs-pos/NOUN]() (1; 0% instances), [cs-pos/ADJ]()-[cs-pos/NUM]() (1; 0% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 6 aux:pass	color:blue
1	Rekultivační	rekultivační	ADJ	AAIS1----1A----	Animacy=Inan|Case=Nom|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	2	amod	_	_
2	výzkum	výzkum	NOUN	NNIS1-----A----	Animacy=Inan|Case=Nom|Gender=Masc|Number=Sing|Polarity=Pos	4	nsubj	_	_
3	je	být	AUX	VB-S---3P-AA---	Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	4	cop	_	_
4	dlouhodobý	dlouhodobý	ADJ	AAIS1----1A----	Animacy=Inan|Case=Nom|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	0	root	_	_
5	a	a	CCONJ	J^-------------	_	8	cc	_	LId=a-1
6	je	být	AUX	VB-S---3P-AA---	Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	8	aux:pass	_	_
7	průběžně	průběžně	ADV	Dg-------1A----	Degree=Pos|Polarity=Pos	8	advmod	_	LDeriv=průběžný
8	zajišťován	zajišťovaný	ADJ	VsYS---XX-AP---	Aspect=Imp|Gender=Masc|Number=Sing|Polarity=Pos|Variant=Short|VerbForm=Part|Voice=Pass	4	conj	_	SpaceAfter=No
9	.	.	PUNCT	Z:-------------	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 16	bgColor:blue
# visual-style 16	fgColor:white
# visual-style 16 13 aux:pass	color:blue
1	Dřevěné	dřevěný	ADJ	AAIP1----1A----	Animacy=Inan|Case=Nom|Degree=Pos|Gender=Masc|Number=Plur|Polarity=Pos	2	amod	_	_
2	obklady	obklad	NOUN	NNIP1-----A----	Animacy=Inan|Case=Nom|Gender=Masc|Number=Plur|Polarity=Pos	5	nsubj	_	_
3	jsou	být	AUX	VB-P---3P-AA---	Mood=Ind|Number=Plur|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	5	cop	_	_
4	poměrně	poměrně	ADV	Dg-------1A----	Degree=Pos|Polarity=Pos	5	advmod	_	LDeriv=poměrný
5	odolné	odolný	ADJ	AAIP1----1A----	Animacy=Inan|Case=Nom|Degree=Pos|Gender=Masc|Number=Plur|Polarity=Pos	0	root	_	_
6	a	a	CCONJ	J^-------------	_	7	cc	_	LId=a-1
7	trvanlivé	trvanlivý	ADJ	AAIP1----1A----	Animacy=Inan|Case=Nom|Degree=Pos|Gender=Masc|Number=Plur|Polarity=Pos	5	conj	_	SpaceAfter=No
8	,	,	PUNCT	Z:-------------	_	11	punct	_	_
9	ale	ale	CCONJ	J^-------------	_	11	cc	_	_
10	jen	jen	PART	TT-------------	_	11	advmod:emph	_	LId=jen-1|LGloss=(pouze)
11	tehdy	tehdy	ADV	Db-------------	PronType=Dem	5	conj	_	SpaceAfter=No
12	,	,	PUNCT	Z:-------------	_	16	punct	_	_
13	*	*	SYM	Xx-------------	Abbr=Yes	16	aux:pass	_	_
14	-	-	PUNCT	Z:-------------	_	16	punct	_	_
15	li	li	PART	TT-------------	_	16	mark	_	_
16	osazeny	osazený	ADJ	VsTP---XX-AP---	Animacy=Inan|Aspect=Perf|Gender=Fem,Masc|Number=Plur|Polarity=Pos|Variant=Short|VerbForm=Part|Voice=Pass	11	orphan	_	_
17	na	na	ADP	RR--4----------	AdpType=Prep|Case=Acc	19	case	_	LId=na-1
18	suché	suchý	ADJ	AANS4----1A----	Case=Acc|Degree=Pos|Gender=Neut|Number=Sing|Polarity=Pos	19	amod	_	_
19	zdivo	zdivo	NOUN	NNNS4-----A----	Case=Acc|Gender=Neut|Number=Sing|Polarity=Pos	16	obl	_	SpaceAfter=No
20	.	.	PUNCT	Z:-------------	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 35	bgColor:blue
# visual-style 35	fgColor:white
# visual-style 36	bgColor:blue
# visual-style 36	fgColor:white
# visual-style 36 35 aux:pass	color:blue
1	Elektrická	elektrický	ADJ	AAFS1----1A----	Case=Nom|Degree=Pos|Gender=Fem|Number=Sing|Polarity=Pos	2	amod	_	_
2	vozba	vozba	NOUN	NNFS1-----A----	Case=Nom|Gender=Fem|Number=Sing|Polarity=Pos	3	nsubj	_	_
3	konala	konat	VERB	VpQW---XR-AA---	Aspect=Imp|Gender=Fem,Neut|Number=Plur,Sing|Polarity=Pos|Tense=Past|VerbForm=Part|Voice=Act	0	root	_	_
4	asi	asi	PART	TT-------------	_	5	advmod:emph	_	_
5	#	&camount;	NUM	C=-------------	NumForm=Digit|NumType=Card	3	obj	_	_
6	*	*	SYM	Xx-------------	Abbr=Yes	5	nmod	_	_
7	z	z	ADP	RR--2----------	AdpType=Prep|Case=Gen	10	case	_	LId=z-1
8	celkové	celkový	ADJ	AAFS2----1A----	Case=Gen|Degree=Pos|Gender=Fem|Number=Sing|Polarity=Pos	10	amod	_	_
9	dopravní	dopravní	ADJ	AAFS2----1A----	Case=Gen|Degree=Pos|Gender=Fem|Number=Sing|Polarity=Pos	10	amod	_	_
10	práce	práce	NOUN	NNFS2-----A----	Case=Gen|Gender=Fem|Number=Sing|Polarity=Pos	5	nmod	_	LGloss=(jako_činnost_i_místo)
11	železniční	železniční	ADJ	AAFS2----1A----	Case=Gen|Degree=Pos|Gender=Fem|Number=Sing|Polarity=Pos	12	amod	_	_
12	sítě	síť	NOUN	NNFS2-----A----	Case=Gen|Gender=Fem|Number=Sing|Polarity=Pos	10	nmod	_	_
13	a	a	CCONJ	J^-------------	_	20	cc	_	LId=a-1
14	hospodárnost	hospodárnost	NOUN	NNFS1-----A----	Case=Nom|Gender=Fem|Number=Sing|Polarity=Pos	20	nsubj	_	LDeriv=hospodárný
15	i	i	CCONJ	J^-------------	_	16	cc	_	LId=i-1
16	návratnost	návratnost	NOUN	NNFS1-----A----	Case=Nom|Gender=Fem|Number=Sing|Polarity=Pos	14	conj	_	LDeriv=návratný
17	elektrizačních	elektrizační	ADJ	AAFP2----1A----	Case=Gen|Degree=Pos|Gender=Fem|Number=Plur|Polarity=Pos	18	amod	_	_
18	investic	investice	NOUN	NNFP2-----A---1	Case=Gen|Gender=Fem|Number=Plur|Polarity=Pos	14	nmod	_	_
19	se	se	PRON	P7-X4----------	Case=Acc|PronType=Prs|Reflex=Yes|Variant=Short	20	expl:pv	_	LGloss=(zvr._zájmeno/částice)
20	prokázala	prokázat	VERB	VpQW---XR-AA---	Gender=Fem,Neut|Number=Plur,Sing|Polarity=Pos|Tense=Past|VerbForm=Part|Voice=Act	3	conj	_	_
21	příznivým	příznivý	ADJ	AAIS7----1A----	Animacy=Inan|Case=Ins|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	22	amod	_	_
22	poměrem	poměr	NOUN	NNIS7-----A----	Animacy=Inan|Case=Ins|Gender=Masc|Number=Sing|Polarity=Pos	20	obl	_	LGloss=(vztah_mezi_2_věcmi/lidmi)
23	provozních	provozní	ADJ	AAIP2----1A----	Animacy=Inan|Case=Gen|Degree=Pos|Gender=Masc|Number=Plur|Polarity=Pos	24	amod	_	_
24	nákladů	náklad	NOUN	NNIP2-----A----	Animacy=Inan|Case=Gen|Gender=Masc|Number=Plur|Polarity=Pos	22	nmod	_	SpaceAfter=No
25	,	,	PUNCT	Z:-------------	_	26	punct	_	_
26	provozu	provoz	NOUN	NNIS2-----A----	Animacy=Inan|Case=Gen|Gender=Masc|Number=Sing|Polarity=Pos	24	conj	_	_
27	parního	parní	ADJ	AAIS2----1A----	Animacy=Inan|Case=Gen|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	26	amod	_	SpaceAfter=No
28	,	,	PUNCT	Z:-------------	_	29	punct	_	_
29	dieselového	dieselový	ADJ	AAIS2----1A----	Animacy=Inan|Case=Gen|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	27	conj	_	SpaceAfter=No
30	,	,	PUNCT	Z:-------------	_	31	punct	_	_
31	elektrického	elektrický	ADJ	AAIS2----1A----	Animacy=Inan|Case=Gen|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	27	conj	_	SpaceAfter=No
32	,	,	PUNCT	Z:-------------	_	22	punct	_	_
33	v	v	ADP	RR--6----------	AdpType=Prep|Case=Loc	34	case	_	LId=v-1
34	poměru	poměr	NOUN	NNIS6-----A----	Animacy=Inan|Case=Loc|Gender=Masc|Number=Sing|Polarity=Pos	36	obl	_	LGloss=(vztah_mezi_2_věcmi/lidmi)
35	#	&camount;	NUM	C=-------------	NumForm=Digit|NumType=Card	36	aux:pass	_	_
36	vztaženo	vztažený	ADJ	VsNS---XX-AP---	Gender=Neut|Number=Sing|Polarity=Pos|Variant=Short|VerbForm=Part|Voice=Pass	22	dep	_	_
37	na	na	ADP	RR--4----------	AdpType=Prep|Case=Acc	40	case	_	LId=na-1
38	užitečnou	užitečný	ADJ	AAFS4----1A----	Case=Acc|Degree=Pos|Gender=Fem|Number=Sing|Polarity=Pos	40	amod	_	_
39	dopravní	dopravní	ADJ	AAFS4----1A----	Case=Acc|Degree=Pos|Gender=Fem|Number=Sing|Polarity=Pos	40	amod	_	_
40	práci	práce	NOUN	NNFS4-----A----	Case=Acc|Gender=Fem|Number=Sing|Polarity=Pos	36	obl	_	LGloss=(jako_činnost_i_místo)
41	v	v	ADP	RR--6----------	AdpType=Prep|Case=Loc	42	case	_	LId=v-1
42	*	*	SYM	Xx-------------	Abbr=Yes	40	advmod	_	_
43	.	.	PUNCT	Z:-------------	_	3	punct	_	_

~~~




--------------------------------------------------------------------------------

## Treebank Statistics (UD_Czech-CLTT)

This relation is a language-specific subtype of [aux]().

89 nodes (0%) are attached to their parents as `aux:pass`.

89 instances of `aux:pass` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.76404494382022.

The following 2 pairs of parts of speech are connected with `aux:pass`: [cs-pos/VERB]()-[cs-pos/AUX]() (87; 98% instances), [cs-pos/VERB]()-[cs-pos/NOUN]() (2; 2% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 aux:pass	color:blue
1	Průběh	průběh	NOUN	NNIS1-----A----	Animacy=Inan|Case=Nom|Gender=Masc|Number=Sing|Polarity=Pos	3	nsubj	_	_
2	používání	používání	NOUN	NNNS2-----A----	Case=Gen|Gender=Neut|Number=Sing|Polarity=Pos	1	nmod	_	_
3	může	moci	VERB	VB-S---3P-AA---	Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_
4	být	být	AUX	Vf--------A----	Polarity=Pos|VerbForm=Inf	5	aux:pass	_	_
5	vyjádřen	vyjádřit	VERB	VsYS---XX-AP---	Gender=Masc|Number=Sing|Polarity=Pos|VerbForm=Part|Voice=Pass	3	ccomp	_	_
6	i	i	CCONJ	J^-------------	_	7	advmod:emph	_	LId=i-1
7	jinak	jinak	ADV	Db-------------	_	5	advmod	_	_
8	než	než	SCONJ	J,-------------	_	10	mark	_	LId=než-2
9	ve	v	ADP	RV--6----------	AdpType=Voc|Case=Loc	10	case	_	LId=v-1
10	vazbě	vazba	NOUN	NNFS6-----A----	Case=Loc|Gender=Fem|Number=Sing|Polarity=Pos	7	dep	_	LId=vazba-8
11	na	na	ADP	RR--4----------	AdpType=Prep|Case=Acc	12	case	_	LId=na-1
12	čas	čas	NOUN	NNIS4-----A----	Animacy=Inan|Case=Acc|Gender=Masc|Number=Sing|Polarity=Pos	10	nmod	_	SpaceAfter=No
13	,	,	PUNCT	Z:-------------	_	16	punct	_	_
14	například	například	ADV	Db-------------	_	16	cc	_	_
15	na	na	ADP	RR--4----------	AdpType=Prep|Case=Acc	16	case	_	LId=na-1
16	výkony	výkon	NOUN	NNIP4-----A----	Animacy=Inan|Case=Acc|Gender=Masc|Number=Plur|Polarity=Pos	12	appos	_	SpaceAfter=No
17	.	.	PUNCT	Z:-------------	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 2 aux:pass	color:blue
1	(2)	(2)	PUNCT	Z:-------------	_	9	punct	_	_
2	Není-li	Není-li	NOUN	NNNXX-----A----	Gender=Neut|Polarity=Pos	4	aux:pass	_	_
3	dále	dále	ADV	Db------------1	_	4	advmod	_	LId=dále-3
4	stanoveno	stanovit	VERB	VsNS---XX-AP---	Gender=Neut|Number=Sing|Polarity=Pos|VerbForm=Part|Voice=Pass	9	advcl	_	_
5	jinak	jinak	ADV	Db-------------	_	4	advmod	_	SpaceAfter=No
6	,	,	PUNCT	Z:-------------	_	4	punct	_	_
7	účetní	účetní	ADJ	AAFP1----1A----	Case=Nom|Degree=Pos|Gender=Fem|Number=Plur|Polarity=Pos	8	amod	_	LId=účetní-1
8	jednotky	jednotka	NOUN	NNFP1-----A----	Case=Nom|Gender=Fem|Number=Plur|Polarity=Pos	9	nsubj	_	_
9	uzavírají	uzavírat	VERB	VB-P---3P-AA---	Mood=Ind|Number=Plur|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_
10	účetní	účetní	ADJ	AAFP4----1A----	Case=Acc|Degree=Pos|Gender=Fem|Number=Plur|Polarity=Pos	11	amod	_	LId=účetní-1
11	knihy	kniha	NOUN	NNFP4-----A----	Case=Acc|Gender=Fem|Number=Plur|Polarity=Pos	9	obj	_	_
12	a)	a)	X	X@-------------	_	9	obl	_	_
13	ke	k	ADP	RV--3----------	AdpType=Voc|Case=Dat	12	case	_	LId=k-1
14	dni	den	NOUN	NNIS3-----A---1	Animacy=Inan|Case=Dat|Gender=Masc|Number=Sing|Polarity=Pos	12	obl	_	_
15	zániku	zánik	NOUN	NNIS2-----A----	Animacy=Inan|Case=Gen|Gender=Masc|Number=Sing|Polarity=Pos	14	nmod	_	_
16	povinnosti	povinnost	NOUN	NNFS2-----A----	Case=Gen|Gender=Fem|Number=Sing|Polarity=Pos	15	nmod	_	_
17	vést	vést	VERB	Vf--------A----	Polarity=Pos|VerbForm=Inf	16	acl	_	LId=vést-1
18	účetnictví	účetnictví	NOUN	NNNS4-----A----	Case=Acc|Gender=Neut|Number=Sing|Polarity=Pos	17	obj	_	SpaceAfter=No
19	,	,	PUNCT	Z:-------------	_	20	punct	_	_
20	b)	b)	X	X@-------------	_	12	conj	_	_
21	k	k	ADP	RR--3----------	AdpType=Prep|Case=Dat	20	case	_	LId=k-1
22	poslednímu	poslední	ADJ	AAIS3----1A----	Animacy=Inan|Case=Dat|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	23	amod	_	_
23	dni	den	NOUN	NNIS3-----A---1	Animacy=Inan|Case=Dat|Gender=Masc|Number=Sing|Polarity=Pos	20	obl	_	_
24	účetního	účetní	ADJ	AANS2----1A----	Case=Gen|Degree=Pos|Gender=Neut|Number=Sing|Polarity=Pos	25	amod	_	LId=účetní-1
25	období	období	NOUN	NNNS2-----A----	Case=Gen|Gender=Neut|Number=Sing|Polarity=Pos	23	nmod	_	SpaceAfter=No
26	,	,	PUNCT	Z:-------------	_	27	punct	_	_
27	c)	c)	X	X@-------------	_	12	conj	_	_
28	ke	k	ADP	RV--3----------	AdpType=Voc|Case=Dat	27	case	_	LId=k-1
29	dni	den	NOUN	NNIS3-----A---1	Animacy=Inan|Case=Dat|Gender=Masc|Number=Sing|Polarity=Pos	27	obl	_	_
30	předcházejícímu	předcházející	ADJ	AGMS3-----A----	Animacy=Anim|Aspect=Imp|Case=Dat|Gender=Masc|Number=Sing|Polarity=Pos|Tense=Pres|VerbForm=Part|Voice=Act	29	amod	_	_
31	dni	den	NOUN	NNIS3-----A---1	Animacy=Inan|Case=Dat|Gender=Masc|Number=Sing|Polarity=Pos	30	obj	_	_
32	vstupu	vstup	NOUN	NNIS2-----A----	Animacy=Inan|Case=Gen|Gender=Masc|Number=Sing|Polarity=Pos	31	nmod	_	_
33	do	do	ADP	RR--2----------	AdpType=Prep|Case=Gen	34	case	_	LId=do-1
34	likvidace	likvidace	NOUN	NNFS2-----A----	Case=Gen|Gender=Fem|Number=Sing|Polarity=Pos	32	nmod	_	SpaceAfter=No
35	,	,	PUNCT	Z:-------------	_	36	punct	_	_
36	d)	d)	X	X@-------------	_	12	conj	_	_
37	ke	k	ADP	RV--3----------	AdpType=Voc|Case=Dat	36	case	_	LId=k-1
38	dni	den	NOUN	NNIS3-----A---1	Animacy=Inan|Case=Dat|Gender=Masc|Number=Sing|Polarity=Pos	36	obl	_	_
39	zrušení	zrušení	NOUN	NNNS2-----A----	Case=Gen|Gender=Neut|Number=Sing|Polarity=Pos	38	nmod	_	_
40	bez	bez	ADP	RR--2----------	AdpType=Prep|Case=Gen	41	case	_	LId=bez-1
41	likvidace	likvidace	NOUN	NNFS2-----A----	Case=Gen|Gender=Fem|Number=Sing|Polarity=Pos	39	nmod	_	_
42	s	s	ADP	RR--7----------	AdpType=Prep|Case=Ins	44	case	_	LId=s-1
43	výjimkou	výjimka	NOUN	NNFS7-----A----	Case=Ins|Gender=Fem|Number=Sing|Polarity=Pos	42	fixed	_	_
44	přeměn	přeměna	NOUN	NNFP2-----A----	Case=Gen|Gender=Fem|Number=Plur|Polarity=Pos	39	nmod	_	_
45	společností	společnost	NOUN	NNFP2-----A----	Case=Gen|Gender=Fem|Number=Plur|Polarity=Pos	44	nmod	_	_
46	nebo	nebo	CCONJ	J^-------------	_	47	cc	_	_
47	družstev	družstvo	NOUN	NNNP2-----A----	Case=Gen|Gender=Neut|Number=Plur|Polarity=Pos	45	conj	_	SpaceAfter=No
48	,	,	PUNCT	Z:-------------	_	49	punct	_	_
49	e)	e)	X	X@-------------	_	12	conj	_	_
50	ke	k	ADP	RV--3----------	AdpType=Voc|Case=Dat	49	case	_	LId=k-1
51	dni	den	NOUN	NNIS3-----A---1	Animacy=Inan|Case=Dat|Gender=Masc|Number=Sing|Polarity=Pos	49	obl	_	_
52	předcházejícímu	předcházející	ADJ	AGNS3-----A----	Aspect=Imp|Case=Dat|Gender=Neut|Number=Sing|Polarity=Pos|Tense=Pres|VerbForm=Part|Voice=Act	51	amod	_	_
53	dni	den	NOUN	NNIS3-----A---1	Animacy=Inan|Case=Dat|Gender=Masc|Number=Sing|Polarity=Pos	52	obj	_	SpaceAfter=No
54	,	,	PUNCT	Z:-------------	_	56	punct	_	_
55	kterým	který	PRON	P4XP3----------	Case=Dat|Number=Plur|PronType=Int,Rel	56	advmod	_	_
56	nastanou	nastat	VERB	VB-P---3P-AA---	Mood=Ind|Number=Plur|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	53	acl	_	_
57	účinky	účinek	NOUN	NNIP1-----A----	Animacy=Inan|Case=Nom|Gender=Masc|Number=Plur|Polarity=Pos	56	nsubj	_	_
58	rozhodnutí	rozhodnutí	NOUN	NNNS2-----A----	Case=Gen|Gender=Neut|Number=Sing|Polarity=Pos	57	nmod	_	_
59	o	o	ADP	RR--6----------	AdpType=Prep|Case=Loc	60	case	_	LId=o-1
60	úpadku	úpadek	NOUN	NNIS6-----A----	Animacy=Inan|Case=Loc|Gender=Masc|Number=Sing|Polarity=Pos	58	nmod	_	_
61	nebo	nebo	CCONJ	J^-------------	_	64	cc	_	_
62	ke	k	ADP	RV--3----------	AdpType=Voc|Case=Dat	63	case	_	LId=k-1
63	kterému	který	PRON	P4ZS3----------	Case=Dat|Gender=Masc,Neut|Number=Sing|PronType=Int,Rel	64	advmod	_	_
64	nastanou	nastat	VERB	VB-P---3P-AA---	Mood=Ind|Number=Plur|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	56	conj	_	_
65	účinky	účinek	NOUN	NNIP1-----A----	Animacy=Inan|Case=Nom|Gender=Masc|Number=Plur|Polarity=Pos	64	nsubj	_	_
66	rozhodnutí	rozhodnutí	NOUN	NNNS2-----A----	Case=Gen|Gender=Neut|Number=Sing|Polarity=Pos	65	nmod	_	_
67	soudu	soud	NOUN	NNIS2-----A----	Animacy=Inan|Case=Gen|Gender=Masc|Number=Sing|Polarity=Pos	66	nmod	_	_
68	o	o	ADP	RR--6----------	AdpType=Prep|Case=Loc	69	case	_	LId=o-1
69	přeměně	přeměna	NOUN	NNFS6-----A----	Case=Loc|Gender=Fem|Number=Sing|Polarity=Pos	66	nmod	_	_
70	reorganizace	reorganizace	NOUN	NNFS2-----A----	Case=Gen|Gender=Fem|Number=Sing|Polarity=Pos	69	nmod	_	_
71	v	v	ADP	RR--4----------	AdpType=Prep|Case=Acc	72	case	_	LId=v-1
72	konkurs	konkurs	NOUN	NNIS4-----A----	Animacy=Inan|Case=Acc|Gender=Masc|Number=Sing|Polarity=Pos	69	nmod	_	SpaceAfter=No|LId=konkurs-1
73	,	,	PUNCT	Z:-------------	_	74	punct	_	_
74	f)	f)	X	X@-------------	_	12	conj	_	_
75	ke	k	ADP	RV--3----------	AdpType=Voc|Case=Dat	74	case	_	LId=k-1
76	dni	den	NOUN	NNIS3-----A---1	Animacy=Inan|Case=Dat|Gender=Masc|Number=Sing|Polarity=Pos	74	obl	_	SpaceAfter=No
77	,	,	PUNCT	Z:-------------	_	79	punct	_	_
78	kterým	který	PRON	P4XP3----------	Case=Dat|Number=Plur|PronType=Int,Rel	79	advmod	_	_
79	nastanou	nastat	VERB	VB-P---3P-AA---	Mood=Ind|Number=Plur|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	76	acl	_	_
80	účinky	účinek	NOUN	NNIP1-----A----	Animacy=Inan|Case=Nom|Gender=Masc|Number=Plur|Polarity=Pos	79	nsubj	_	_
81	zrušení	zrušení	NOUN	NNNS2-----A----	Case=Gen|Gender=Neut|Number=Sing|Polarity=Pos	80	nmod	_	_
82	konkursu	konkurs	NOUN	NNIS2-----A----	Animacy=Inan|Case=Gen|Gender=Masc|Number=Sing|Polarity=Pos	81	nmod	_	SpaceAfter=No|LId=konkurs-1
83	,	,	PUNCT	Z:-------------	_	84	punct	_	_
84	g)	g)	X	X@-------------	_	12	conj	_	_
85	ke	k	ADP	RV--3----------	AdpType=Voc|Case=Dat	84	case	_	LId=k-1
86	dni	den	NOUN	NNIS3-----A---1	Animacy=Inan|Case=Dat|Gender=Masc|Number=Sing|Polarity=Pos	84	obl	_	_
87	předcházejícímu	předcházející	ADJ	AGNS3-----A----	Aspect=Imp|Case=Dat|Gender=Neut|Number=Sing|Polarity=Pos|Tense=Pres|VerbForm=Part|Voice=Act	86	amod	_	_
88	dni	den	NOUN	NNIP4-----A---1	Animacy=Inan|Case=Acc|Gender=Masc|Number=Plur|Polarity=Pos	87	obj	_	SpaceAfter=No
89	,	,	PUNCT	Z:-------------	_	91	punct	_	_
90	kterým	který	PRON	P4ZS7----------	Case=Ins|Gender=Masc,Neut|Number=Sing|PronType=Int,Rel	91	advmod	_	_
91	nastanou	nastat	VERB	VB-P---3P-AA---	Mood=Ind|Number=Plur|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	88	acl	_	_
92	účinky	účinek	NOUN	NNIP1-----A----	Animacy=Inan|Case=Nom|Gender=Masc|Number=Plur|Polarity=Pos	91	nsubj	_	_
93	schválení	schválení	NOUN	NNNS2-----A----	Case=Gen|Gender=Neut|Number=Sing|Polarity=Pos	92	nmod	_	_
94	reorganizačního	reorganizační	ADJ	AAIS2----1A----	Animacy=Inan|Case=Gen|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	95	amod	_	_
95	plánu	plán	NOUN	NNIS2-----A----	Animacy=Inan|Case=Gen|Gender=Masc|Number=Sing|Polarity=Pos	93	nmod	_	SpaceAfter=No
96	,	,	PUNCT	Z:-------------	_	97	punct	_	_
97	h)	h)	X	X@-------------	_	12	conj	_	_
98	ke	k	ADP	RV--3----------	AdpType=Voc|Case=Dat	97	case	_	LId=k-1
99	dni	den	NOUN	NNIS3-----A---1	Animacy=Inan|Case=Dat|Gender=Masc|Number=Sing|Polarity=Pos	97	obl	_	SpaceAfter=No
100	,	,	PUNCT	Z:-------------	_	102	punct	_	_
101	kterým	který	PRON	P4XP3----------	Case=Dat|Number=Plur|PronType=Int,Rel	102	obj	_	_
102	nastanou	nastat	VERB	VB-P---3P-AA---	Mood=Ind|Number=Plur|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	99	acl	_	_
103	účinky	účinek	NOUN	NNIP1-----A----	Animacy=Inan|Case=Nom|Gender=Masc|Number=Plur|Polarity=Pos	102	nsubj	_	_
104	splnění	splnění	NOUN	NNNS2-----A----	Case=Gen|Gender=Neut|Number=Sing|Polarity=Pos	103	nmod	_	_
105	reorganizačního	reorganizační	ADJ	AAIS2----1A----	Animacy=Inan|Case=Gen|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	106	amod	_	_
106	plánu	plán	NOUN	NNIS2-----A----	Animacy=Inan|Case=Gen|Gender=Masc|Number=Sing|Polarity=Pos	104	nmod	_	SpaceAfter=No
107	,	,	PUNCT	Z:-------------	_	108	punct	_	_
108	i)	i)	X	X@-------------	_	12	conj	_	_
109	ke	k	ADP	RV--3----------	AdpType=Voc|Case=Dat	108	case	_	LId=k-1
110	dni	den	NOUN	NNIS3-----A---1	Animacy=Inan|Case=Dat|Gender=Masc|Number=Sing|Polarity=Pos	108	obl	_	SpaceAfter=No
111	,	,	PUNCT	Z:-------------	_	113	punct	_	_
112	kterým	který	PRON	P4XP3----------	Case=Dat|Number=Plur|PronType=Int,Rel	113	advmod	_	_
113	nastanou	nastat	VERB	VB-P---3P-AA---	Mood=Ind|Number=Plur|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	110	acl	_	_
114	účinky	účinek	NOUN	NNIP1-----A----	Animacy=Inan|Case=Nom|Gender=Masc|Number=Plur|Polarity=Pos	113	nsubj	_	_
115	splnění	splnění	NOUN	NNNS2-----A----	Case=Gen|Gender=Neut|Number=Sing|Polarity=Pos	114	nmod	_	_
116	plánu	plán	NOUN	NNIS2-----A----	Animacy=Inan|Case=Gen|Gender=Masc|Number=Sing|Polarity=Pos	117	nmod	_	_
117	oddlužení	oddlužení	NOUN	NNNS2-----A----	Case=Gen|Gender=Neut|Number=Sing|Polarity=Pos	115	nmod	_	SpaceAfter=No
118	,	,	PUNCT	Z:-------------	_	120	punct	_	_
119	nebo	nebo	CCONJ	J^-------------	_	120	cc	_	_
120	j)	j)	X	X@-------------	_	12	conj	_	_
121	ke	k	ADP	RV--3----------	AdpType=Voc|Case=Dat	120	case	_	LId=k-1
122	dni	den	NOUN	NNIS3-----A---1	Animacy=Inan|Case=Dat|Gender=Masc|Number=Sing|Polarity=Pos	120	obl	_	SpaceAfter=No
123	,	,	PUNCT	Z:-------------	_	126	punct	_	_
124	ke	k	ADP	RV--3----------	AdpType=Voc|Case=Dat	125	case	_	LId=k-1
125	kterému	který	PRON	P4ZS3----------	Case=Dat|Gender=Masc,Neut|Number=Sing|PronType=Int,Rel	126	advmod	_	_
126	stanoví	stanovit	VERB	VB-S---3P-AA---	Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	122	acl	_	_
127	povinnost	povinnost	NOUN	NNFS4-----A----	Case=Acc|Gender=Fem|Number=Sing|Polarity=Pos	126	obj	_	_
128	uzavřít	uzavřít	VERB	Vf--------A----	Polarity=Pos|VerbForm=Inf	127	acl	_	_
129	účetní	účetní	ADJ	AAFP4----1A----	Case=Acc|Degree=Pos|Gender=Fem|Number=Plur|Polarity=Pos	130	amod	_	LId=účetní-1
130	knihy	kniha	NOUN	NNFP4-----A----	Case=Acc|Gender=Fem|Number=Plur|Polarity=Pos	128	obj	_	_
131	nebo	nebo	CCONJ	J^-------------	_	132	cc	_	_
132	sestavit	sestavit	VERB	Vf--------A----	Polarity=Pos|VerbForm=Inf	128	conj	_	_
133	účetní	účetní	ADJ	AAFS4----1A----	Case=Acc|Degree=Pos|Gender=Fem|Number=Sing|Polarity=Pos	134	amod	_	LId=účetní-1
134	závěrku	závěrka	NOUN	NNFS4-----A----	Case=Acc|Gender=Fem|Number=Sing|Polarity=Pos	132	obj	_	_
135	zvláštní	zvláštní	ADJ	AAFS4----1A----	Case=Acc|Degree=Pos|Gender=Fem|Number=Sing|Polarity=Pos	137	amod	_	_
136	právní	právní	ADJ	AAIS1----1A----	Animacy=Inan|Case=Nom|Degree=Pos|Gender=Masc|Number=Sing|Polarity=Pos	137	amod	_	_
137	předpis	předpis	NOUN	NNIS1-----A----	Animacy=Inan|Case=Nom|Gender=Masc|Number=Sing|Polarity=Pos	126	nsubj	_	SpaceAfter=No
138	.	.	PUNCT	Z:-------------	_	9	punct	_	_

~~~


