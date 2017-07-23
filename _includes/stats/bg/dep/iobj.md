

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Bulgarian)

This relation is universal.

3216 nodes (2%) are attached to their parents as `iobj`.

2602 instances of `iobj` (81%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.62344527363184.

The following 15 pairs of parts of speech are connected with `iobj`: [bg-pos/VERB]()-[bg-pos/NOUN]() (2204; 69% instances), [bg-pos/VERB]()-[bg-pos/PRON]() (630; 20% instances), [bg-pos/VERB]()-[bg-pos/PROPN]() (216; 7% instances), [bg-pos/VERB]()-[bg-pos/ADJ]() (54; 2% instances), [bg-pos/VERB]()-[bg-pos/DET]() (36; 1% instances), [bg-pos/VERB]()-[bg-pos/NUM]() (18; 1% instances), [bg-pos/ADJ]()-[bg-pos/PRON]() (16; 0% instances), [bg-pos/NOUN]()-[bg-pos/PRON]() (13; 0% instances), [bg-pos/ADV]()-[bg-pos/PRON]() (8; 0% instances), [bg-pos/ADJ]()-[bg-pos/NOUN]() (6; 0% instances), [bg-pos/VERB]()-[bg-pos/ADP]() (5; 0% instances), [bg-pos/VERB]()-[bg-pos/ADV]() (5; 0% instances), [bg-pos/DET]()-[bg-pos/PRON]() (2; 0% instances), [bg-pos/PRON]()-[bg-pos/PRON]() (2; 0% instances), [bg-pos/NOUN]()-[bg-pos/NOUN]() (1; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 2 iobj	color:blue
1	На	на	ADP	R	_	2	case	_	_
2	заека	заек	NOUN	Ncmsh	Definite=Def|Gender=Masc|Number=Sing	4	iobj	_	_
3	му	аз	PRON	Ppetds3m	Case=Dat|Gender=Masc|Number=Sing|Person=3|PronType=Prs	4	expl	_	_
4	омръзна	омръзне-ми	VERB	Vnpif-o3s	Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	_
5	да	да	AUX	Tx	_	6	aux	_	_
6	студува	студувам	VERB	Vpiif-r3s	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	4	csubj	_	SpaceAfter=No
7	.	.	PUNCT	punct	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 7 iobj	color:blue
1	Не	не	PART	Tn	Polarity=Neg	2	advmod	_	_
2	помня	помня	VERB	Vpitf-r1s	Aspect=Imp|Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_
3	да	да	AUX	Tx	_	5	aux	_	_
4	съм	съм	AUX	Vxitf-r1s	Aspect=Imp|Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin|Voice=Act	5	aux	_	_
5	ходил	ходя-(си)	VERB	Vpitcao-smi	Aspect=Imp|Definite=Ind|Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part|Voice=Act	2	ccomp	_	_
6	у	у	ADP	R	_	7	case	_	_
7	тях	аз	PRON	Ppelap3	Case=Acc|Number=Plur|Person=3|PronType=Prs	5	iobj	_	SpaceAfter=No
8	.	.	PUNCT	punct	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 5 iobj	color:blue
1	След	след	ADP	R	_	2	case	_	_
2	седмица	седмица	NOUN	Ncfsi	Definite=Ind|Gender=Fem|Number=Sing	3	obl	_	_
3	отиде	отида-(си)	VERB	Vppif-o3s	Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	_
4	у	у	ADP	R	_	5	case	_	_
5	Ганини	ганини	PROPN	H-pi	Definite=Ind|Number=Plur	3	iobj	_	SpaceAfter=No
6	.	.	PUNCT	punct	_	3	punct	_	_

~~~


