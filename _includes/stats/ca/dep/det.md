

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Catalan)

This relation is universal.

64283 nodes (14%) are attached to their parents as `det`.

63295 instances of `det` (98%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.15288645520589.

The following 29 pairs of parts of speech are connected with `det`: [ca-pos/NOUN]()-[ca-pos/DET]() (52251; 81% instances), [ca-pos/PROPN]()-[ca-pos/DET]() (7892; 12% instances), [ca-pos/DET]()-[ca-pos/DET]() (1284; 2% instances), [ca-pos/NUM]()-[ca-pos/DET]() (873; 1% instances), [ca-pos/PRON]()-[ca-pos/DET]() (663; 1% instances), [ca-pos/ADJ]()-[ca-pos/DET]() (575; 1% instances), [ca-pos/VERB]()-[ca-pos/DET]() (481; 1% instances), [ca-pos/SYM]()-[ca-pos/DET]() (162; 0% instances), [ca-pos/ADV]()-[ca-pos/DET]() (23; 0% instances), [ca-pos/AUX]()-[ca-pos/DET]() (14; 0% instances), [ca-pos/AUX]()-[ca-pos/NOUN]() (13; 0% instances), [ca-pos/NOUN]()-[ca-pos/NUM]() (11; 0% instances), [ca-pos/VERB]()-[ca-pos/NOUN]() (8; 0% instances), [ca-pos/ADP]()-[ca-pos/DET]() (7; 0% instances), [ca-pos/AUX]()-[ca-pos/PROPN]() (4; 0% instances), [ca-pos/NOUN]()-[ca-pos/ADV]() (3; 0% instances), [ca-pos/PRON]()-[ca-pos/NOUN]() (3; 0% instances), [ca-pos/NOUN]()-[ca-pos/VERB]() (2; 0% instances), [ca-pos/PUNCT]()-[ca-pos/DET]() (2; 0% instances), [ca-pos/VERB]()-[ca-pos/PROPN]() (2; 0% instances), [ca-pos/X]()-[ca-pos/DET]() (2; 0% instances), [ca-pos/AUX]()-[ca-pos/ADJ]() (1; 0% instances), [ca-pos/AUX]()-[ca-pos/NUM]() (1; 0% instances), [ca-pos/AUX]()-[ca-pos/PRON]() (1; 0% instances), [ca-pos/CCONJ]()-[ca-pos/DET]() (1; 0% instances), [ca-pos/NOUN]()-[ca-pos/ADJ]() (1; 0% instances), [ca-pos/NOUN]()-[ca-pos/PRON]() (1; 0% instances), [ca-pos/NUM]()-[ca-pos/ADP]() (1; 0% instances), [ca-pos/SYM]()-[ca-pos/PUNCT]() (1; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 det	color:blue
1	D'	de	ADP	ADP	AdpType=Prep	3	case	_	SpaceAfter=No
2	aquestes	aquest	DET	DET	Gender=Fem|Number=Plur|PronType=Dem	3	det	_	_
3	activitats	activitat	NOUN	NOUN	Gender=Fem|Number=Plur	9	obl	_	SpaceAfter=No
4	,	,	PUNCT	PUNCT	PunctType=Comm	3	punct	_	_
5	algunes	algun	PRON	PRON	Gender=Fem|Number=Plur|PronType=Ind	9	nsubj	_	_
6	no	no	ADV	ADV	Polarity=Neg	9	advmod	_	_
7	s'	es	PRON	PRON	_	9	obj	_	SpaceAfter=No
8	han	haver	AUX	AUX	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	9	aux	_	_
9	obert	obrir	VERB	VERB	Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part	0	root	_	_
10	al	al	ADP	ADP	AdpType=Preppron|Gender=Masc|Number=Sing	11	case	_	_
11	públic	públic	NOUN	NOUN	Gender=Masc|Number=Sing	9	obj	_	SpaceAfter=No
12	.	.	PUNCT	PUNCT	PunctType=Peri	9	punct	_	_

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 11 10 det	color:blue
1	També	també	ADV	ADV	_	4	advmod	_	_
2	s'	es	PRON	PRON	_	4	obj	_	SpaceAfter=No
3	ha	haver	AUX	AUX	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	4	aux	_	_
4	fet	fer	VERB	VERB	Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part	0	root	_	_
5	una	un	NUM	NUM	Gender=Fem|Number=Sing|NumType=Card	6	nummod	_	_
6	ofrena	ofrena	NOUN	NOUN	Gender=Fem|Number=Sing	4	nsubj	_	_
7	simbòlica	simbòlic	ADJ	ADJ	Gender=Fem|Number=Sing	6	amod	_	_
8	a	a	ADP	ADP	AdpType=Prep	11	case	_	_
9	'	'	SYM	SYM	_	11	nmod	_	SpaceAfter=No
10	la	el	DET	DET	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	11	det	_	_
11	Moreneta	Moreneta	PROPN	PROPN	_	4	obj	_	SpaceAfter=No
12	'	'	SYM	SYM	_	11	nmod	_	SpaceAfter=No
13	.	.	PUNCT	PUNCT	PunctType=Peri	4	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 5 det	color:blue
1	Dues	dos	NUM	NUM	Gender=Fem|Number=Plur|NumType=Card	2	nummod	_	_
2	vegades	vegada	NOUN	NOUN	Gender=Fem|Number=Plur	0	root	_	_
3	en	en	ADP	ADP	AdpType=Prep	6	case	_	_
4	la	el	DET	DET	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	6	det	_	_
5	mateixa	mateix	DET	DET	Gender=Fem|Number=Sing|PronType=Ind	4	det	_	_
6	roca	roca	NOUN	NOUN	Gender=Fem|Number=Sing	2	nmod	_	SpaceAfter=No
7	.	.	PUNCT	PUNCT	PunctType=Peri	2	punct	_	_

~~~


