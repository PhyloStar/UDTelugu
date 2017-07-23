

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Romanian)

This relation is universal.

66 nodes (0%) are attached to their parents as `orphan`.

37 instances of `orphan` (56%) are right-to-left (child precedes parent).
Average distance between parent and child is 3.92424242424242.

The following 17 pairs of parts of speech are connected with `orphan`: [ro-pos/NOUN]()-[ro-pos/NOUN]() (29; 44% instances), [ro-pos/NOUN]()-[ro-pos/NUM]() (6; 9% instances), [ro-pos/PROPN]()-[ro-pos/NOUN]() (5; 8% instances), [ro-pos/DET]()-[ro-pos/NOUN]() (3; 5% instances), [ro-pos/NOUN]()-[ro-pos/PRON]() (3; 5% instances), [ro-pos/NOUN]()-[ro-pos/PROPN]() (3; 5% instances), [ro-pos/PRON]()-[ro-pos/NOUN]() (3; 5% instances), [ro-pos/NOUN]()-[ro-pos/ADP]() (2; 3% instances), [ro-pos/NOUN]()-[ro-pos/ADV]() (2; 3% instances), [ro-pos/NOUN]()-[ro-pos/VERB]() (2; 3% instances), [ro-pos/PRON]()-[ro-pos/PROPN]() (2; 3% instances), [ro-pos/ADJ]()-[ro-pos/ADP]() (1; 2% instances), [ro-pos/ADV]()-[ro-pos/ADV]() (1; 2% instances), [ro-pos/NOUN]()-[ro-pos/ADJ]() (1; 2% instances), [ro-pos/PART]()-[ro-pos/NOUN]() (1; 2% instances), [ro-pos/PRON]()-[ro-pos/PRON]() (1; 2% instances), [ro-pos/PROPN]()-[ro-pos/DET]() (1; 2% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 8 orphan	color:blue
1	Din	din	ADP	Spsa	AdpType=Prep|Case=Acc	2	case	_	_
2	slove	slovă	NOUN	Ncfp-n	Definite=Ind|Gender=Fem|Number=Plur	4	obl	_	_
3	am	avea	AUX	Va--1	Person=1	4	aux	_	_
4	ales	alege	VERB	Vmp--sm	Gender=Masc|Number=Sing|VerbForm=Part	0	root	_	_
5	micile	mic	ADJ	Afpfpry	Case=Acc,Nom|Definite=Def|Degree=Pos|Gender=Fem|Number=Plur	4	obj	_	_
6	Și	și	CCONJ	Crssp	Polarity=Pos	9	cc	_	_
7	din	din	ADP	Spsa	AdpType=Prep|Case=Acc	8	case	_	_
8	înțelesuri	înțeles	NOUN	Ncfp-n	Definite=Ind|Gender=Fem|Number=Plur	9	orphan	_	orig_deprel=obl
9	furnicile	furnică	NOUN	Ncfpry	Case=Acc,Nom|Definite=Def|Gender=Fem|Number=Plur	4	conj	_	orig_deprel=obj|SpaceAfter=No
10	.	.	PUNCT	PERIOD	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 24	bgColor:blue
# visual-style 24	fgColor:white
# visual-style 16	bgColor:blue
# visual-style 16	fgColor:white
# visual-style 16 24 orphan	color:blue
1	Rochia	rochie	NOUN	Ncfsry	Case=Acc,Nom|Definite=Def|Gender=Fem|Number=Sing	5	nsubj	_	_
2	miresei	mireasă	NOUN	Ncfsoy	Case=Dat,Gen|Definite=Def|Gender=Fem|Number=Sing	1	nmod	_	_
3	și	și	CCONJ	Crssp	Polarity=Pos	4	cc	_	_
4	vălul	văl	NOUN	Ncmsry	Case=Acc,Nom|Definite=Def|Gender=Masc|Number=Sing	1	conj	_	_
5	costau	costa	VERB	Vmii3p	Mood=Ind|Number=Plur|Person=3|Tense=Imp|VerbForm=Fin	0	root	_	_
6	doar	doar	ADV	Rgp	Degree=Pos	7	advmod	_	_
7	ý10	ý10	NUM	M	_	5	nummod	_	SpaceAfter=No
8	,	,	PUNCT	COMMA	_	5	punct	_	ToDo=punct-in-coord
9	rochia	rochie	NOUN	Ncfsry	Case=Acc,Nom|Definite=Def|Gender=Fem|Number=Sing	16	orphan	_	orig_deprel=nsubj
10	domnișoarei	domnișoară	NOUN	Ncfsoy	Case=Dat,Gen|Definite=Def|Gender=Fem|Number=Sing	9	nmod	_	_
11	de	de	ADP	Spsa	AdpType=Prep|Case=Acc	12	case	_	_
12	onoare	onoare	NOUN	Ncfsrn	Case=Acc,Nom|Definite=Ind|Gender=Fem|Number=Sing	10	nmod	_	_
13	ý5	ý5	NUM	M	_	16	orphan	_	orig_deprel=nummod|SpaceAfter=No
14	,	,	PUNCT	COMMA	_	16	punct	_	_
15	iar	iar	ADV	Rc	_	16	cc	_	_
16	redingota	redingotă	NOUN	Ncfsry	Case=Acc,Nom|Definite=Def|Gender=Fem|Number=Sing	5	conj	_	orig_deprel=nsubj
17	și	și	CCONJ	Crssp	Polarity=Pos	18	cc	_	_
18	pantalonii	pantalon	NOUN	Ncmpry	Case=Acc,Nom|Definite=Def|Gender=Masc|Number=Plur	16	conj	_	_
19	mirelui	mire	NOUN	Ncmsoy	Case=Dat,Gen|Definite=Def|Gender=Masc|Number=Sing	16	nmod	_	SpaceAfter=No
20	,	,	PUNCT	COMMA	_	22	punct	_	_
21	plus	plus	ADV	Rgp	Degree=Pos	22	advmod	_	_
22	smochingul	smoching	NOUN	Ncmsry	Case=Acc,Nom|Definite=Def|Gender=Masc|Number=Sing	16	nmod	_	SpaceAfter=No
23	,	,	PUNCT	COMMA	_	22	punct	_	_
24	ý15	ý15	NUM	M	_	16	orphan	_	orig_deprel=nummod|SpaceAfter=No
25	.	.	PUNCT	PERIOD	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 8 orphan	color:blue
1	Cranston	Cranston	PROPN	Np	_	2	nsubj	_	_
2	poartă	purta	VERB	Vmip3	Mood=Ind|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
3	costum	costum	NOUN	Ncms-n	Definite=Ind|Gender=Masc|Number=Sing	2	obj	_	_
4	în	în	ADP	Spsa	AdpType=Prep|Case=Acc	5	case	_	_
5	dungi	dungă	NOUN	Ncfp-n	Definite=Ind|Gender=Fem|Number=Plur	3	nmod:pmod	_	SpaceAfter=No
6	,	,	PUNCT	COMMA	_	7	punct	_	_
7	Crombie	Crombie	PROPN	Np	_	2	conj	_	orig_deprel=nsubj
8	pardesiu	pardesiu	NOUN	Ncms-n	Definite=Ind|Gender=Masc|Number=Sing	7	orphan	_	orig_deprel=obj
9	și	și	CCONJ	Crssp	Polarity=Pos	10	cc	_	_
10	pantofi	pantof	NOUN	Ncmp-n	Definite=Ind|Gender=Masc|Number=Plur	8	conj	_	_
11	negri	negru	ADJ	Afpmp-n	Definite=Ind|Degree=Pos|Gender=Masc|Number=Plur	10	amod	_	_
12	strălucitori	strălucitor	ADJ	Afpmp-n	Definite=Ind|Degree=Pos|Gender=Masc|Number=Plur	10	amod	_	SpaceAfter=No
13	.	.	PUNCT	PERIOD	_	2	punct	_	_

~~~


