

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Danish)

This relation is universal.

320 nodes (0%) are attached to their parents as `appos`.

314 instances of `appos` (98%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.628125.

The following 22 pairs of parts of speech are connected with `appos`: [da-pos/NOUN]()-[da-pos/PROPN]() (193; 60% instances), [da-pos/NOUN]()-[da-pos/NOUN]() (55; 17% instances), [da-pos/PROPN]()-[da-pos/NOUN]() (18; 6% instances), [da-pos/PROPN]()-[da-pos/PROPN]() (17; 5% instances), [da-pos/PRON]()-[da-pos/PROPN]() (7; 2% instances), [da-pos/NOUN]()-[da-pos/X]() (5; 2% instances), [da-pos/NOUN]()-[da-pos/ADJ]() (4; 1% instances), [da-pos/PROPN]()-[da-pos/PRON]() (3; 1% instances), [da-pos/X]()-[da-pos/NOUN]() (3; 1% instances), [da-pos/PRON]()-[da-pos/NOUN]() (2; 1% instances), [da-pos/X]()-[da-pos/PROPN]() (2; 1% instances), [da-pos/ADJ]()-[da-pos/NOUN]() (1; 0% instances), [da-pos/ADP]()-[da-pos/ADP]() (1; 0% instances), [da-pos/ADV]()-[da-pos/ADV]() (1; 0% instances), [da-pos/NOUN]()-[da-pos/ADV]() (1; 0% instances), [da-pos/NOUN]()-[da-pos/NUM]() (1; 0% instances), [da-pos/NOUN]()-[da-pos/VERB]() (1; 0% instances), [da-pos/NUM]()-[da-pos/NUM]() (1; 0% instances), [da-pos/PRON]()-[da-pos/PRON]() (1; 0% instances), [da-pos/PRON]()-[da-pos/VERB]() (1; 0% instances), [da-pos/PROPN]()-[da-pos/VERB]() (1; 0% instances), [da-pos/VERB]()-[da-pos/NOUN]() (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 5 appos	color:blue
1	Endelig	endelig	ADV	_	_	2	advmod	_	_
2	er	være	VERB	_	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_
3	også	også	ADV	_	_	2	advmod	_	_
4	inspektionsskibet	inspektionsskib	NOUN	_	Definite=Def|Gender=Neut|Number=Sing	2	nsubj	_	_
5	Fylla	Fylla	PROPN	_	_	4	appos	_	_
6	til	til	ADP	_	AdpType=Prep	7	case	_	_
7	salg	salg	NOUN	_	Definite=Ind|Gender=Neut|Number=Sing	2	obl	_	_
8	.	.	PUNCT	_	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 appos	color:blue
1	Kun	kun	ADV	_	_	2	advmod	_	_
2	Ugemagasinet	ugemagasin	NOUN	_	Definite=Def|Gender=Neut|Number=Sing	4	nmod:poss	_	_
3	SØNDAG's	søndag	NOUN	_	Case=Gen|Definite=Ind|Gender=Com|Number=Sing	2	appos	_	_
4	læger	læge	NOUN	_	Definite=Ind|Gender=Com|Number=Plur	6	nsubj	_	_
5	må	måtte	AUX	_	Mood=Ind|Tense=Pres|VerbForm=Fin|Voice=Act	6	aux	_	_
6	åbne	åbne	VERB	_	VerbForm=Inf|Voice=Act	0	root	_	_
7	Deres	Deres	DET	_	Person=2|Polite=Form|Poss=Yes|PronType=Prs	8	det	_	_
8	brev	brev	NOUN	_	Definite=Ind|Gender=Neut|Number=Sing	6	obj	_	_
9	.	.	PUNCT	_	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 9 appos	color:blue
1	Vi	vi	PRON	_	Case=Nom|Gender=Com|Number=Plur|Person=1|PronType=Prs	2	nsubj	_	_
2	gik	gå	VERB	_	Mood=Ind|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	_
3	ind	ind	ADV	_	_	2	obl:loc	_	_
4	i	i	ADP	_	AdpType=Prep	5	case	_	_
5	Coctail	Coctail	PROPN	_	_	3	obl	_	_
6	,	,	PUNCT	_	_	5	punct	_	_
7	Odenses	Odense	PROPN	_	Case=Gen	9	nmod:poss	_	_
8	smarteste	smart	ADJ	_	Definite=Def|Degree=Sup	9	amod	_	_
9	modeforretning	modeforretning	NOUN	_	Definite=Ind|Gender=Com|Number=Sing	5	appos	_	_
10	.	.	PUNCT	_	_	2	punct	_	_

~~~


