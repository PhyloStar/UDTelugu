

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Croatian)

This relation is universal.

2742 nodes (1%) are attached to their parents as `appos`.

2711 instances of `appos` (99%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.41028446389497.

The following 45 pairs of parts of speech are connected with `appos`: [hr-pos/NOUN]()-[hr-pos/PROPN]() (1655; 60% instances), [hr-pos/NOUN]()-[hr-pos/NOUN]() (495; 18% instances), [hr-pos/PROPN]()-[hr-pos/NOUN]() (250; 9% instances), [hr-pos/NOUN]()-[hr-pos/ADP]() (77; 3% instances), [hr-pos/PROPN]()-[hr-pos/PROPN]() (74; 3% instances), [hr-pos/NOUN]()-[hr-pos/X]() (34; 1% instances), [hr-pos/NOUN]()-[hr-pos/ADJ]() (26; 1% instances), [hr-pos/PRON]()-[hr-pos/NOUN]() (17; 1% instances), [hr-pos/NOUN]()-[hr-pos/VERB]() (16; 1% instances), [hr-pos/ADP]()-[hr-pos/NOUN]() (12; 0% instances), [hr-pos/NOUN]()-[hr-pos/NUM]() (9; 0% instances), [hr-pos/ADJ]()-[hr-pos/PROPN]() (8; 0% instances), [hr-pos/NOUN]()-[hr-pos/ADV]() (5; 0% instances), [hr-pos/ADJ]()-[hr-pos/ADJ]() (4; 0% instances), [hr-pos/ADJ]()-[hr-pos/NOUN]() (4; 0% instances), [hr-pos/DET]()-[hr-pos/NOUN]() (4; 0% instances), [hr-pos/NOUN]()-[hr-pos/DET]() (4; 0% instances), [hr-pos/PROPN]()-[hr-pos/ADJ]() (4; 0% instances), [hr-pos/DET]()-[hr-pos/PRON]() (3; 0% instances), [hr-pos/NUM]()-[hr-pos/PROPN]() (3; 0% instances), [hr-pos/PRON]()-[hr-pos/PROPN]() (3; 0% instances), [hr-pos/VERB]()-[hr-pos/VERB]() (3; 0% instances), [hr-pos/ADJ]()-[hr-pos/VERB]() (2; 0% instances), [hr-pos/ADP]()-[hr-pos/ADP]() (2; 0% instances), [hr-pos/ADP]()-[hr-pos/PROPN]() (2; 0% instances), [hr-pos/ADV]()-[hr-pos/ADV]() (2; 0% instances), [hr-pos/NOUN]()-[hr-pos/PRON]() (2; 0% instances), [hr-pos/PROPN]()-[hr-pos/NUM]() (2; 0% instances), [hr-pos/VERB]()-[hr-pos/NOUN]() (2; 0% instances), [hr-pos/VERB]()-[hr-pos/PROPN]() (2; 0% instances), [hr-pos/X]()-[hr-pos/NOUN]() (2; 0% instances), [hr-pos/ADV]()-[hr-pos/PROPN]() (1; 0% instances), [hr-pos/DET]()-[hr-pos/ADJ]() (1; 0% instances), [hr-pos/DET]()-[hr-pos/DET]() (1; 0% instances), [hr-pos/DET]()-[hr-pos/PROPN]() (1; 0% instances), [hr-pos/NOUN]()-[hr-pos/AUX]() (1; 0% instances), [hr-pos/NOUN]()-[hr-pos/CCONJ]() (1; 0% instances), [hr-pos/NUM]()-[hr-pos/NOUN]() (1; 0% instances), [hr-pos/PROPN]()-[hr-pos/ADP]() (1; 0% instances), [hr-pos/PROPN]()-[hr-pos/AUX]() (1; 0% instances), [hr-pos/SCONJ]()-[hr-pos/NOUN]() (1; 0% instances), [hr-pos/VERB]()-[hr-pos/ADP]() (1; 0% instances), [hr-pos/X]()-[hr-pos/ADJ]() (1; 0% instances), [hr-pos/X]()-[hr-pos/VERB]() (1; 0% instances), [hr-pos/X]()-[hr-pos/X]() (1; 0% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 4 appos	color:blue
1	Slijede	slijediti	VERB	_	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
2	ga	on	PRON	_	Case=Acc|Gender=Masc|Number=Sing|Person=3|PronType=Prs	1	obj	_	_
3	Hipermarketi	hipermarket	NOUN	_	Case=Nom|Gender=Masc|Number=Plur	1	nsubj	_	_
4	Coop	Coop	PROPN	_	Case=Nom|Gender=Masc|Number=Sing	3	appos	_	_
5	sa	sa	ADP	_	Case=Ins	6	case	_	_
6	4,72	4,72	NUM	_	NumType=Card	4	nummod	_	_
7	i	i	CCONJ	_	_	8	cc	_	_
8	Metro	Metro	PROPN	_	Case=Nom|Gender=Masc|Number=Sing	4	conj	_	_
9	sa	sa	ADP	_	Case=Ins	10	case	_	_
10	4,19	4,19	NUM	_	NumType=Card	8	nummod	_	SpaceAfter=No
11	.	.	PUNCT	_	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 8 appos	color:blue
1	Takve	takav	DET	_	Case=Nom|Gender=Fem|Number=Plur|PronType=Dem	2	det	_	_
2	ideje	ideja	NOUN	_	Case=Nom|Gender=Fem|Number=Plur	3	nsubj	_	_
3	izazvale	izazvati	VERB	_	Gender=Fem|Number=Plur|Tense=Past|VerbForm=Part|Voice=Act	0	root	_	_
4	su	biti	AUX	_	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	3	aux	_	_
5	kritike	kritika	NOUN	_	Case=Acc|Gender=Fem|Number=Plur	3	obj	_	_
6	ostalih	ostao	ADJ	_	Case=Gen|Degree=Pos|Gender=Fem|Number=Plur	7	amod	_	_
7	zemalja	zemlja	NOUN	_	Case=Gen|Gender=Fem|Number=Plur	5	nmod	_	_
8	članica	članica	NOUN	_	Case=Gen|Gender=Fem|Number=Plur	7	appos	_	_
9	eurozone	eurozona	NOUN	_	Case=Gen|Gender=Fem|Number=Sing	7	nmod	_	SpaceAfter=No
10	.	.	PUNCT	_	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 appos	color:blue
1	EXIT	EXIT	PROPN	_	Case=Nom|Gender=Masc|Number=Sing	3	nsubj	_	_
2	festival	festival	NOUN	_	Case=Nom|Gender=Masc|Number=Sing	1	appos	_	_
3	uspješan	uspješan	ADJ	_	Case=Nom|Degree=Pos|Gender=Masc|Number=Sing	0	root	_	_
4	unatoč	unatoč	ADP	_	Case=Dat	5	case	_	_
5	kiši	kiša	NOUN	_	Case=Dat|Gender=Fem|Number=Sing	3	obl	_	_
6	i	i	CCONJ	_	_	7	cc	_	_
7	prijetnjama	prijetnja	NOUN	_	Case=Dat|Gender=Fem|Number=Plur	5	conj	_	_

~~~


