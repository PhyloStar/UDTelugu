

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Lithuanian)

This relation is universal.

371 nodes (7%) are attached to their parents as `conj`.

371 instances of `conj` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 5.94339622641509.

The following 23 pairs of parts of speech are connected with `conj`: [lt-pos/NOUN]()-[lt-pos/NOUN]() (132; 36% instances), [lt-pos/VERB]()-[lt-pos/VERB]() (98; 26% instances), [lt-pos/ADJ]()-[lt-pos/ADJ]() (31; 8% instances), [lt-pos/PROPN]()-[lt-pos/PROPN]() (20; 5% instances), [lt-pos/NOUN]()-[lt-pos/PROPN]() (16; 4% instances), [lt-pos/ADJ]()-[lt-pos/VERB]() (15; 4% instances), [lt-pos/VERB]()-[lt-pos/ADJ]() (8; 2% instances), [lt-pos/ADJ]()-[lt-pos/NOUN]() (7; 2% instances), [lt-pos/PROPN]()-[lt-pos/NOUN]() (7; 2% instances), [lt-pos/VERB]()-[lt-pos/NOUN]() (7; 2% instances), [lt-pos/NOUN]()-[lt-pos/ADJ]() (6; 2% instances), [lt-pos/NOUN]()-[lt-pos/VERB]() (6; 2% instances), [lt-pos/ADV]()-[lt-pos/ADV]() (5; 1% instances), [lt-pos/VERB]()-[lt-pos/ADV]() (4; 1% instances), [lt-pos/ADV]()-[lt-pos/ADJ]() (1; 0% instances), [lt-pos/ADV]()-[lt-pos/NOUN]() (1; 0% instances), [lt-pos/AUX]()-[lt-pos/NOUN]() (1; 0% instances), [lt-pos/DET]()-[lt-pos/DET]() (1; 0% instances), [lt-pos/NOUN]()-[lt-pos/ADV]() (1; 0% instances), [lt-pos/NOUN]()-[lt-pos/PRON]() (1; 0% instances), [lt-pos/PRON]()-[lt-pos/DET]() (1; 0% instances), [lt-pos/PRON]()-[lt-pos/NOUN]() (1; 0% instances), [lt-pos/VERB]()-[lt-pos/PROPN]() (1; 0% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 3 conj	color:blue
1	Tėvynę	tėvynė	NOUN	NN	Case=Acc|Gender=Fem|Number=Sing	7	obj	_	En=homeland|SpaceAfter=No
2	,	,	PUNCT	PUNCT	_	3	punct	_	En=,
3	tautą	tauta	NOUN	NN	Case=Acc|Gender=Fem|Number=Sing	1	conj	_	En=nation
4	ir	ir	CCONJ	CC	_	5	cc	_	En=and
5	lietuvybę	lietuvybė	NOUN	NN	Case=Acc|Gender=Fem|Number=Sing	1	conj	_	En=Lithuanianism
6	dera	derėti	VERB	VBC	Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Reflex=No|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	En=need
7	mylėti	mylėti	VERB	VB	Polarity=Pos|Reflex=No|VerbForm=Inf|Voice=Act	6	xcomp	_	En=love|SpaceAfter=No
8	.	.	PUNCT	PUNCT	_	6	punct	_	En=.

~~~


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 9 conj	color:blue
1	Taip	taip	PART	UH	_	0	root	_	En=so
2	nėra	būti	AUX	VBC	Mood=Ind|Number=Sing|Person=3|Polarity=Neg|Reflex=No|Tense=Pres|VerbForm=Fin|Voice=Act	1	cop	_	En=be|SpaceAfter=No
3	:	:	PUNCT	PUNCT	_	6	punct	_	En=:
4	mes	mes	PRON	PRP	Case=Nom|Number=Plur|Person=1	6	nsubj	_	En=we
5	tik	tik	ADV	RB	Degree=Pos	6	advmod	_	En=only
6	draudžiame	drausti	VERB	VBC	Mood=Ind|Number=Plur|Person=1|Polarity=Pos|Reflex=No|Tense=Pres|VerbForm=Fin|Voice=Act	1	parataxis	_	En=friend
7	drausti	drausti	VERB	VB	Polarity=Pos|Reflex=No|VerbForm=Inf|Voice=Act	6	xcomp	_	En=friend|SpaceAfter=No
8	,	,	PUNCT	PUNCT	_	9	punct	_	En=,
9	draudžiame	drausti	VERB	VBC	Mood=Ind|Number=Plur|Person=1|Polarity=Pos|Reflex=No|Tense=Pres|VerbForm=Fin|Voice=Act	6	conj	_	En=friend
10	prievartauti	prievartauti	VERB	VB	Polarity=Pos|Reflex=No|VerbForm=Inf|Voice=Act	9	xcomp	_	En=coerce|SpaceAfter=No
11	.	.	PUNCT	PUNCT	_	1	punct	_	En=.

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 10 conj	color:blue
1	Tų	tų	DET	PRP$	Case=Gen|Definite=Ind|Gender=Masc|Number=Plur	2	det	_	En=that
2	laikų	laikas	NOUN	NN	Case=Gen|Gender=Masc|Number=Plur	3	nmod	_	En=time
3	entuziazmas	entuziazmas	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing	5	nsubj	_	En=enthusiasm
4	buvo	būti	AUX	VBC	Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Reflex=No|Tense=Past|VerbForm=Fin|Voice=Act	5	cop	_	En=be
5	gražus	gražus	ADJ	JJL	Case=Nom|Definite=Ind|Degree=Pos|Gender=Masc|Number=Sing	0	root	_	En=beautiful|SpaceAfter=No
6	,	,	PUNCT	PUNCT	_	10	punct	_	En=,
7	o	o	CCONJ	CC	_	10	cc	_	En=and
8	sudėtos	sudėti	VERB	VBNL	Case=Gen|Definite=Ind|Gender=Fem|Number=Sing|Polarity=Pos|Reflex=No|Tense=Past|VerbForm=Part|Voice=Pass	9	amod	_	En=additional
9	aukos	auka	NOUN	NN	Case=Gen|Gender=Fem|Number=Sing	10	nsubj	_	En=victim
10	vertos	vertas	ADJ	JJL	Case=Gen|Definite=Ind|Degree=Pos|Gender=Fem|Number=Sing	5	conj	_	En=worth
11	didelės	didelis	ADJ	JJL	Case=Gen|Definite=Ind|Degree=Pos|Gender=Fem|Number=Sing	12	amod	_	En=big
12	pagarbos	pagarba	NOUN	NN	Case=Gen|Gender=Fem|Number=Sing	10	obj	_	En=respect|SpaceAfter=No
13	.	.	PUNCT	PUNCT	_	5	punct	_	En=.

~~~


