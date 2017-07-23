

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Bulgarian)

This relation is universal.

1560 nodes (1%) are attached to their parents as `flat`.

1560 instances of `flat` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.05897435897436.

The following 11 pairs of parts of speech are connected with `flat`: [bg-pos/PROPN]()-[bg-pos/PROPN]() (1477; 95% instances), [bg-pos/NUM]()-[bg-pos/NUM]() (45; 3% instances), [bg-pos/PROPN]()-[bg-pos/ADJ]() (12; 1% instances), [bg-pos/ADJ]()-[bg-pos/NOUN]() (10; 1% instances), [bg-pos/NOUN]()-[bg-pos/PROPN]() (4; 0% instances), [bg-pos/ADJ]()-[bg-pos/PROPN]() (3; 0% instances), [bg-pos/PROPN]()-[bg-pos/NOUN]() (3; 0% instances), [bg-pos/NOUN]()-[bg-pos/NOUN]() (2; 0% instances), [bg-pos/PROPN]()-[bg-pos/CCONJ]() (2; 0% instances), [bg-pos/NUM]()-[bg-pos/ADJ]() (1; 0% instances), [bg-pos/X]()-[bg-pos/X]() (1; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 flat	color:blue
1	Марин	марин	PROPN	Npmsi	Definite=Ind|Gender=Masc|Number=Sing	0	root	_	_
2	ПЕНКОВ	пенков	PROPN	Hmsi	Definite=Ind|Gender=Masc|Number=Sing	1	flat	_	_
3	(	(	PUNCT	punct	_	5	punct	_	SpaceAfter=No
4	23	23	NUM	Mc-pi	Definite=Ind|Number=Plur|NumType=Card	5	nummod	_	_
5	г.	година	NOUN	Ncfpi	Definite=Ind|Gender=Fem|Number=Plur	1	nmod	_	SpaceAfter=No
6	)	)	PUNCT	punct	_	5	punct	_	SpaceAfter=No
7	,	,	PUNCT	punct	_	8	punct	_	_
8	студент	студент	NOUN	Ncmsi	Definite=Ind|Gender=Masc|Number=Sing	1	nmod	_	SpaceAfter=No
9	,	,	PUNCT	punct	_	10	punct	_	_
10	София	софия	PROPN	Npfsi	Definite=Ind|Gender=Fem|Number=Sing	1	nmod	_	SpaceAfter=No
11	:	:	PUNCT	punct	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 8 flat	color:blue
1	Регистрират	регистрирам	VERB	Vpitf-r3p	Aspect=Imp|Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_
2	всички	всеки	DET	Pce-op	Case=Nom|Number=Plur|PronType=Tot	4	det	_	_
3	валутни	валутен	ADJ	A-pi	Definite=Ind|Degree=Pos|Number=Plur	4	amod	_	_
4	сделки	сделка	NOUN	Ncfpi	Definite=Ind|Gender=Fem|Number=Plur	1	obj	_	_
5	за	за	ADP	R	_	9	case	_	_
6	над	над	ADP	R	_	7	case	_	_
7	10	10	NUM	Mc-pi	Definite=Ind|Number=Plur|NumType=Card	9	nmod	_	_
8	000	000	NUM	Mc-pi	Definite=Ind|Number=Plur|NumType=Card	7	flat	_	_
9	лв.	лев	NOUN	Ncmt	Gender=Masc|Number=Count	4	nmod	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 8 flat	color:blue
1	Най-добрият	добър	ADJ	Amsf	Definite=Def|Degree=Sup|Gender=Masc|Number=Sing	2	amod	_	_
2	начин	начин	NOUN	Ncmsi	Definite=Ind|Gender=Masc|Number=Sing	6	nsubj	_	_
3	това	този	PRON	Pde-os-n	Case=Nom|Gender=Neut|Number=Sing|PronType=Dem	5	nsubj	_	_
4	да	да	AUX	Tx	_	5	aux	_	_
5	стане	стана	VERB	Vppif-r3s	Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	2	acl	_	_
6	е	съм	VERB	Vxitf-r3s	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_
7	Йоан-Павел	йоан-павел	PROPN	Npmsi	Definite=Ind|Gender=Masc|Number=Sing	10	nsubj	_	_
8	II	втори	ADJ	Momsi	Definite=Ind|Degree=Pos|Gender=Masc|Number=Sing|NumType=Ord	7	flat	_	_
9	да	да	AUX	Tx	_	10	aux	_	_
10	дойде	дойда	VERB	Vppif-r3s	Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	6	ccomp	_	_
11	тук	там	ADV	Pdl	PronType=Dem	10	obj	_	SpaceAfter=No
12	.	.	PUNCT	punct	_	6	punct	_	_

~~~


