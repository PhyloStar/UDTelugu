

--------------------------------------------------------------------------------

## Treebank Statistics (UD_German)

This relation is a language-specific subtype of [aux]().

3390 nodes (1%) are attached to their parents as `aux:pass`.

2243 instances of `aux:pass` (66%) are right-to-left (child precedes parent).
Average distance between parent and child is 5.62654867256637.

The following 6 pairs of parts of speech are connected with `aux:pass`: [de-pos/VERB]()-[de-pos/AUX]() (3377; 100% instances), [de-pos/NOUN]()-[de-pos/AUX]() (4; 0% instances), [de-pos/VERB]()-[de-pos/VERB]() (4; 0% instances), [de-pos/ADJ]()-[de-pos/AUX]() (3; 0% instances), [de-pos/VERB]()-[de-pos/NOUN]() (1; 0% instances), [de-pos/X]()-[de-pos/AUX]() (1; 0% instances).


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 7 aux:pass	color:blue
1	Dieses	dies	PRON	PDAT	Case=Nom|Gender=Neut|Number=Sing|PronType=Dem	2	det	_	_
2	Video	Video	NOUN	NN	Case=Nom|Gender=Neut|Number=Sing	6	nsubj:pass	_	_
3	konnte	können	AUX	VMFIN	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	6	aux	_	_
4	angeblich	angeblich	ADV	ADJD	_	5	advmod	_	_
5	nicht	nicht	PART	PTKNEG	Polarity=Neg	6	advmod	_	_
6	storniert	stornieren	VERB	VVPP	VerbForm=Part	0	root	_	_
7	werden	werden	AUX	VAINF	VerbForm=Inf	6	aux:pass	_	SpaceAfter=No
8	.	.	PUNCT	$.	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 aux:pass	color:blue
1	Des	der	DET	ART	Definite=Def|PronType=Art	2	det	_	_
2	Weiteren	Weiteren	NOUN	NN	_	0	root	_	_
3	ist	sein	AUX	VAFIN	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	2	aux:pass	_	_
4	hier	hier	ADV	ADV	_	2	advmod	_	_
5	die	der	DET	ART	Case=Nom|Definite=Def|Gender=Fem|Number=Sing|PronType=Art	6	det	_	_
6	Musikschulverwaltung	Musikschulverwaltung	NOUN	NN	Case=Nom|Gender=Fem|Number=Sing	2	nsubj:pass	_	SpaceAfter=No
7	,	,	PUNCT	$,	_	9	punct	_	_
8	die	der	DET	ART	Definite=Def|PronType=Art	9	det	_	_
9	Stadtbücherei	Stadtbücherei	NOUN	NN	_	6	conj	_	_
10	und	und	CCONJ	KON	_	12	cc	_	_
11	das	der	DET	ART	Definite=Def|PronType=Art	12	det	_	_
12	Kämmereiamt	Kämmereiamt	NOUN	NN	_	6	conj	_	_
13	zusammen	zusammen	ADV	ADV	_	2	advmod	_	_
14	mit	mit	ADP	APPR	_	16	case	_	_
15	der	der	DET	ART	Case=Dat|Definite=Def|Gender=Fem|Number=Sing|PronType=Art	16	det	_	_
16	Stadtkasse	Stadtkasse	NOUN	NN	Case=Dat|Gender=Fem|Number=Sing	13	nmod	_	_
17	untergebracht	unterbringen	VERB	VVPP	VerbForm=Part	2	fixed	_	SpaceAfter=No
18	.	.	PUNCT	$.	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 7 aux:pass	color:blue
1	Er	er	PRON	PPER	Case=Nom|Gender=Masc|Number=Sing|Person=3|PronType=Prs	2	nsubj	_	_
2	kommandiert	kommandieren	VERB	VVFIN	Number=Sing|Person=3|VerbForm=Fin	0	root	_	_
3	Merlin	Merlin	PROPN	NE	Case=Acc|Number=Sing	2	obj	_	_
4	gerne	gerne	ADV	ADV	_	2	advmod	_	_
5	herum	herum	ADV	PTKVZ	_	2	compound:prt	_	_
6	und	und	CCONJ	KON	_	10	cc	_	_
7	ist	sein	VERB	VAFIN	Mood=Ind|Tense=Pres|VerbForm=Fin	10	aux:pass	_	_
8	leicht	leicht	ADJ	ADJD	Degree=Pos	10	advmod	_	_
9	zu	zu	PART	PTKZU	_	10	mark	_	_
10	provozieren	provozieren	VERB	VVINF	VerbForm=Inf	2	conj	_	SpaceAfter=No
11	.	.	PUNCT	$.	_	2	punct	_	_

~~~


