

--------------------------------------------------------------------------------

## Treebank Statistics (UD_German)

This relation is universal.

1372 nodes (0%) are attached to their parents as `advcl`.

965 instances of `advcl` (70%) are left-to-right (parent precedes child).
Average distance between parent and child is 11.850583090379.

The following 30 pairs of parts of speech are connected with `advcl`: [de-pos/VERB]()-[de-pos/VERB]() (993; 72% instances), [de-pos/ADJ]()-[de-pos/VERB]() (92; 7% instances), [de-pos/NOUN]()-[de-pos/VERB]() (84; 6% instances), [de-pos/VERB]()-[de-pos/ADJ]() (83; 6% instances), [de-pos/VERB]()-[de-pos/NOUN]() (29; 2% instances), [de-pos/ADJ]()-[de-pos/ADJ]() (15; 1% instances), [de-pos/PROPN]()-[de-pos/VERB]() (14; 1% instances), [de-pos/ADV]()-[de-pos/VERB]() (7; 1% instances), [de-pos/PRON]()-[de-pos/VERB]() (7; 1% instances), [de-pos/ADP]()-[de-pos/VERB]() (5; 0% instances), [de-pos/AUX]()-[de-pos/VERB]() (5; 0% instances), [de-pos/NOUN]()-[de-pos/ADJ]() (5; 0% instances), [de-pos/ADJ]()-[de-pos/NOUN]() (4; 0% instances), [de-pos/NOUN]()-[de-pos/NOUN]() (4; 0% instances), [de-pos/NUM]()-[de-pos/VERB]() (4; 0% instances), [de-pos/VERB]()-[de-pos/ADV]() (3; 0% instances), [de-pos/PART]()-[de-pos/VERB]() (2; 0% instances), [de-pos/PROPN]()-[de-pos/ADJ]() (2; 0% instances), [de-pos/VERB]()-[de-pos/CCONJ]() (2; 0% instances), [de-pos/VERB]()-[de-pos/PRON]() (2; 0% instances), [de-pos/ADV]()-[de-pos/NOUN]() (1; 0% instances), [de-pos/CCONJ]()-[de-pos/VERB]() (1; 0% instances), [de-pos/NUM]()-[de-pos/PROPN]() (1; 0% instances), [de-pos/PRON]()-[de-pos/NOUN]() (1; 0% instances), [de-pos/PROPN]()-[de-pos/PROPN]() (1; 0% instances), [de-pos/VERB]()-[de-pos/ADP]() (1; 0% instances), [de-pos/VERB]()-[de-pos/PART]() (1; 0% instances), [de-pos/VERB]()-[de-pos/PROPN]() (1; 0% instances), [de-pos/VERB]()-[de-pos/X]() (1; 0% instances), [de-pos/X]()-[de-pos/ADJ]() (1; 0% instances).


~~~ conllu
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 13 advcl	color:blue
1	Also	also	ADV	ADV	_	3	advmod	_	_
2	ich	ich	PRON	PPER	Case=Nom|Number=Sing|Person=1|PronType=Prs	3	nsubj	_	_
3	bin	sein	VERB	VAFIN	Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	0	root	_	_
4	öfter	öfter	ADV	ADV	_	3	advmod	_	_
5	hier	hier	ADV	ADV	_	3	advmod	_	SpaceAfter=No
6	,	,	PUNCT	$,	_	3	punct	_	_
7	da	da	SCONJ	KOUS	_	13	mark	_	_
8	es	es	PRON	PPER	Case=Nom|Gender=Neut|Number=Sing|Person=3|PronType=Prs	13	nsubj	_	_
9	mir	ich	PRON	PRF	Case=Dat|Number=Sing|Person=1|PronType=Prs|Reflex=Yes	13	iobj	_	_
10	hier	hier	ADV	ADV	_	13	advmod	_	_
11	sehr	sehr	ADV	ADV	_	12	advmod	_	_
12	gut	gut	ADV	ADJD	_	13	advmod	_	_
13	gefällt	fällen	VERB	VVPP	VerbForm=Part	3	advcl	_	SpaceAfter=No
14	!	!	PUNCT	$.	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 5 advcl	color:blue
1	Wenn	wenn	SCONJ	KOUS	_	5	mark	_	_
2	es	es	PRON	PPER	Case=Nom|Gender=Neut|Number=Sing|Person=3|PronType=Prs	5	nsubj	_	_
3	um	um	ADP	APPR	_	4	case	_	_
4	Beratung	Beratung	NOUN	NN	Case=Acc|Gender=Fem|Number=Sing	5	obl	_	_
5	geht	gehen	VERB	VVFIN	Number=Sing|Person=3|VerbForm=Fin	10	advcl	_	SpaceAfter=No
6	,	,	PUNCT	$,	_	10	punct	_	_
7	dann	dann	ADV	ADV	_	10	advmod	_	_
8	ist	sein	VERB	VAFIN	Mood=Ind|Person=3|Tense=Pres|VerbForm=Fin	10	cop	_	_
9	der	der	PRON	PDS	Case=Nom|PronType=Dem	10	nsubj	_	_
10	super	super	ADJ	ADJD	Degree=Pos	0	root	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 8 advcl	color:blue
1	Die	der	DET	ART	Case=Nom|Definite=Def|Number=Plur|PronType=Art	2	det	_	_
2	Schreine	Schrein	NOUN	NN	Case=Nom|Number=Plur	13	nsubj:pass	_	SpaceAfter=No
3	,	,	PUNCT	$,	_	2	punct	_	_
4	die	der	PRON	ART	Case=Nom|PronType=Dem	8	nsubj:pass	_	_
5	Vishnu	Vishnu	PROPN	NN	Case=Dat|Number=Sing	8	iobj	_	_
6	und	und	CCONJ	KON	_	7	cc	_	_
7	Brahma	Brahma	PROPN	NN	_	5	conj	_	_
8	gewidmet	widmen	VERB	VVPP	VerbForm=Part	2	advcl	_	_
9	sind	sein	AUX	VAFIN	Mood=Ind|Person=3|Tense=Pres|VerbForm=Fin	8	aux:pass	_	SpaceAfter=No
10	,	,	PUNCT	$,	_	8	punct	_	_
11	können	können	AUX	VMFIN	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	13	aux	_	_
12	wieder	wieder	ADV	ADV	_	13	advmod	_	_
13	betreten	betreten	VERB	VVPP	VerbForm=Part	0	root	_	_
14	werden	werden	AUX	VAINF	VerbForm=Inf	13	aux:pass	_	SpaceAfter=No
15	.	.	PUNCT	$.	_	13	punct	_	_

~~~


