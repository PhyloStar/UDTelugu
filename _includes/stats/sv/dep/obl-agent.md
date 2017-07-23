

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Swedish)

This relation is a language-specific subtype of [obl]().

167 nodes (0%) are attached to their parents as `obl:agent`.

155 instances of `obl:agent` (93%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.43712574850299.

The following 9 pairs of parts of speech are connected with `obl:agent`: [sv-pos/VERB]()-[sv-pos/NOUN]() (113; 68% instances), [sv-pos/ADJ]()-[sv-pos/NOUN]() (25; 15% instances), [sv-pos/ADJ]()-[sv-pos/PROPN]() (8; 5% instances), [sv-pos/VERB]()-[sv-pos/PROPN]() (8; 5% instances), [sv-pos/VERB]()-[sv-pos/PRON]() (5; 3% instances), [sv-pos/VERB]()-[sv-pos/ADJ]() (3; 2% instances), [sv-pos/ADJ]()-[sv-pos/PRON]() (2; 1% instances), [sv-pos/NOUN]()-[sv-pos/NOUN]() (2; 1% instances), [sv-pos/ADJ]()-[sv-pos/ADJ]() (1; 1% instances).


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 9 obl:agent	color:blue
1	Börjar	börja	VERB	VB|PRS|AKT	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_
2	hennes	hon	DET	PS|UTR/NEU|SIN/PLU|DEF	Definite=Def|Poss=Yes|PronType=Prs	3	nmod:poss	_	_
3	jobb	jobb	NOUN	NN|NEU|SIN|IND|NOM	Case=Nom|Definite=Ind|Gender=Neut|Number=Sing	1	nsubj	_	_
4	att	att	PART	IE	_	5	mark	_	_
5	delas	dela	VERB	VB|INF|SFO	VerbForm=Inf|Voice=Pass	1	xcomp	_	_
6	av	av	ADP	PP	_	9	case	_	_
7	den	en	DET	DT|UTR|SIN|DEF	Definite=Def|Gender=Com|Number=Sing|PronType=Art	9	det	_	_
8	moderne	modern	ADJ	JJ|POS|MAS|SIN|DEF|NOM	Case=Nom|Definite=Def|Degree=Pos|Gender=Masc|Number=Sing	9	amod	_	_
9	mannen	man	NOUN	NN|UTR|SIN|DEF|NOM	Case=Nom|Definite=Def|Gender=Com|Number=Sing	5	obl:agent	_	SpaceAfter=No
10	?	?	PUNCT	MAD	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 5 obl:agent	color:blue
1	Han	han	PRON	PN|UTR|SIN|DEF|SUB	Case=Nom|Definite=Def|Gender=Com|Number=Sing|PronType=Prs	2	nsubj	_	_
2	anför	anföra	VERB	VB|PRS|AKT	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_
3	en	man	DET	DT|UTR|SIN|IND	Definite=Ind|Gender=Com|Number=Sing|PronType=Art	8	det	_	_
4	av	av	ADP	PP	_	5	case	_	_
5	regeringen	regering	NOUN	NN|UTR|SIN|DEF|NOM	Case=Nom|Definite=Def|Gender=Com|Number=Sing	7	obl:agent	_	_
6	särskilt	särskilt	ADV	AB	_	7	advmod	_	_
7	utsedd	utse	ADJ	PC|PRF|UTR|SIN|IND|NOM	Case=Nom|Definite=Ind|Gender=Com|Number=Sing|Tense=Past|VerbForm=Part	8	amod	_	_
8	innertrio	innertrio	NOUN	NN|UTR|SIN|IND|NOM	Case=Nom|Definite=Ind|Gender=Com|Number=Sing	2	obj	_	SpaceAfter=No
9	.	.	PUNCT	MAD	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 8 obl:agent	color:blue
1	Här	här	ADV	AB	_	2	advmod	_	_
2	anges	ange	VERB	VB|PRS|SFO	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Pass	0	root	_	_
3	de	en	DET	DT|UTR/NEU|PLU|DEF	Definite=Def|Number=Plur|PronType=Art	4	det	_	_
4	priser	pris	NOUN	NN|NEU|PLU|IND|NOM	Case=Nom|Definite=Ind|Gender=Neut|Number=Plur	2	nsubj:pass	_	_
5	som	som	PRON	HP|-|-|-	PronType=Rel	6	nsubj:pass	_	_
6	tas	ta	VERB	VB|PRS|SFO	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Pass	4	acl:relcl	_	_
7	av	av	ADP	PP	_	8	case	_	_
8	Domus	Domus	PROPN	PM|NOM	Case=Nom	6	obl:agent	_	_
9	i	i	ADP	PP	_	10	case	_	_
10	Stockholm	Stockholm	PROPN	PM|NOM	Case=Nom	6	obl	_	SpaceAfter=No
11	.	.	PUNCT	MAD	_	2	punct	_	_

~~~




--------------------------------------------------------------------------------

## Treebank Statistics (UD_Swedish-LinES)

This relation is a language-specific subtype of [obl]().

57 nodes (0%) are attached to their parents as `obl:agent`.

56 instances of `obl:agent` (98%) are left-to-right (parent precedes child).
Average distance between parent and child is 4.28070175438596.

The following 5 pairs of parts of speech are connected with `obl:agent`: [sv-pos/VERB]()-[sv-pos/NOUN]() (46; 81% instances), [sv-pos/VERB]()-[sv-pos/PRON]() (4; 7% instances), [sv-pos/VERB]()-[sv-pos/PROPN]() (4; 7% instances), [sv-pos/VERB]()-[sv-pos/ADJ]() (2; 4% instances), [sv-pos/VERB]()-[sv-pos/VERB]() (1; 2% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 5 obl:agent	color:blue
1	Mat	_	NOUN	SG-IND-NOM	_	2	nsubj:pass	_	_
2	tillreddes	_	VERB	PAST-PASS	_	0	root	_	_
3	av	_	ADP	_	_	5	case	_	_
4	många	_	ADJ	POS-PL-IND	_	5	amod	_	_
5	händer	_	NOUN	PL-IND-NOM	_	2	obl:agent	_	SpaceAfter=No
6	.	_	PUNCT	Period	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 5 obl:agent	color:blue
1	Detta	_	PRON	DEM-SG	_	2	nsubj:pass	_	_
2	bekräftades	_	VERB	PAST-PASS	_	0	root	_	_
3	också	_	ADV	_	_	2	advmod	_	_
4	av	_	ADP	_	_	5	case	_	_
5	Virginia	_	PROPN	SG-NOM	_	2	obl:agent	_	_
6	Stillman	_	PROPN	SG-NOM	_	5	flat	_	SpaceAfter=No
7	,	_	PUNCT	Comma	_	2	punct	_	_
8	som	_	SCONJ	REL	_	10	mark	_	_
9	Quinn	_	PROPN	SG-NOM	_	10	nsubj	_	_
10	ringde	_	VERB	PAST-ACT	_	5	acl:relcl	_	_
11	till	_	ADP	_	_	10	obl	_	_
12	varje	_	DET	TOT-SG-IND	_	13	det	_	_
13	kväll	_	NOUN	SG-IND-NOM	_	10	obl	_	_
14	när	_	SCONJ	REL	_	16	mark	_	_
15	han	_	PRON	PERS-P3SG-NOM	_	16	nsubj	_	_
16	kom	_	VERB	PAST-ACT	_	13	acl:relcl	_	_
17	hem	_	ADV	_	_	16	advmod	_	_
18	till	_	ADP	_	_	19	case	_	_
19	sig	_	PRON	RFL-ACC	_	16	obl	_	SpaceAfter=No
20	.	_	PUNCT	Period	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 18	bgColor:blue
# visual-style 18	fgColor:white
# visual-style 16	bgColor:blue
# visual-style 16	fgColor:white
# visual-style 16 18 obl:agent	color:blue
1	Jag	_	PRON	PERS-P1SG-NOM	_	2	nsubj	_	_
2	hoppas	_	VERB	PRES-DPO	_	0	root	_	_
3	att	_	SCONJ	_	_	9	mark	_	_
4	den	_	DET	SG-DEF	_	5	det	_	_
5	kärlek	_	NOUN	SG-IND-NOM	_	9	nsubj	_	_
6	de	_	PRON	PERS-P3PL-NOM	_	7	nsubj	_	_
7	skänker	_	VERB	PRES-ACT	_	5	acl:relcl	_	_
8	oss	_	PRON	PERS-P1PL-ACC	_	7	obj	_	_
9	är	_	VERB	PRES-ACT	_	2	ccomp	_	_
10	av	_	ADV	_	_	9	advmod	_	_
11	bättre	_	ADJ	CMP	_	12	amod	_	_
12	kvalitet	_	NOUN	SG-IND-NOM	_	9	obl	_	_
13	än	_	ADP	CMP	_	14	case	_	_
14	den	_	PRON	PERS-P3SG	_	12	nmod	_	_
15	de	_	PRON	PERS-P3PL-NOM	_	16	nsubj	_	_
16	får	_	VERB	PRES-ACT	_	14	acl:relcl	_	_
17	av	_	ADP	_	_	18	case	_	_
18	oss	_	PRON	PERS-P1PL-ACC	_	16	obl:agent	_	SpaceAfter=No
19	,	_	PUNCT	Comma	_	23	punct	_	_
20	för	_	SCONJ	_	_	23	mark	_	_
21	vår	_	PRON	P1PL-GEN-SG	_	22	nmod:poss	_	_
22	egen	_	ADJ	POS-SG-IND	_	23	nsubj	_	_
23	är	_	VERB	PRES-ACT	_	9	advcl	_	_
24	av	_	ADP	_	_	30	case	_	_
25	en	_	DET	SG-IND	_	30	det	_	_
26	mycket	_	ADV	_	_	27	advmod	_	_
27	lågklassig	_	ADJ	POS-SG-IND	_	30	amod	_	_
28	uppåtsipprande	_	ADJ	NDE	_	30	amod	_	_
29	växtsaftsliknande	_	ADJ	NDE	_	30	amod	_	_
30	sort	_	NOUN	SG-IND-NOM	_	23	obl	_	_
31	som	_	SCONJ	REL	_	34	mark	_	_
32	är	_	AUX	PRES-ACT	_	34	cop	_	_
33	lika	_	ADV	CMP	_	34	advmod	_	_
34	kortlivad	_	ADJ	POS-SG-IND	_	30	acl:relcl	_	_
35	som	_	ADP	_	_	36	case	_	_
36	spontan	_	ADJ	POS-SG-IND	_	34	amod	_	SpaceAfter=No
37	.	_	PUNCT	Period	_	2	punct	_	_

~~~


