

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Persian)

This relation is universal.

418 nodes (0%) are attached to their parents as `xcomp`.

396 instances of `xcomp` (95%) are right-to-left (child precedes parent).
Average distance between parent and child is 4.33971291866029.

The following 13 pairs of parts of speech are connected with `xcomp`: [fa-pos/VERB]()-[fa-pos/ADJ]() (233; 56% instances), [fa-pos/VERB]()-[fa-pos/NOUN]() (93; 22% instances), [fa-pos/NOUN]()-[fa-pos/ADJ]() (40; 10% instances), [fa-pos/ADJ]()-[fa-pos/ADJ]() (31; 7% instances), [fa-pos/VERB]()-[fa-pos/VERB]() (9; 2% instances), [fa-pos/VERB]()-[fa-pos/NUM]() (3; 1% instances), [fa-pos/PRON]()-[fa-pos/ADJ]() (2; 0% instances), [fa-pos/VERB]()-[fa-pos/ADV]() (2; 0% instances), [fa-pos/ADJ]()-[fa-pos/NOUN]() (1; 0% instances), [fa-pos/ADV]()-[fa-pos/ADJ]() (1; 0% instances), [fa-pos/NOUN]()-[fa-pos/VERB]() (1; 0% instances), [fa-pos/VERB]()-[fa-pos/ADP]() (1; 0% instances), [fa-pos/VERB]()-[fa-pos/PRON]() (1; 0% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 8 xcomp	color:blue
1	از	از	ADP	P	_	2	case	_	_
2	تو	تو	PRON	PRO	Number=Sing|Person=2|PronType=Prs	4	obl	_	_
3	خبری	_	NOUN	N_SING	Number=Sing	4	nsubj	_	_
4	رسیده	رسید#رس	VERB	V_PP	Number=Sing|Person=3|VerbForm=Part	0	root	_	_
5	که	که	SCONJ	CON	_	9	mark	_	_
6	آن	آن	PRON	PRO	Number=Sing|PronType=Dem	9	obj	_	_
7	را	را	PART	CLITIC	_	6	case	_	_
8	ناخوشایند	ناخوشایند	ADJ	ADJ	Degree=Pos	9	xcomp	_	_
9	می‌شمرم	_	VERB	V_PRS	Number=Sing|Person=1|Tense=Pres	4	ccomp	_	SpaceAfter=No
10	.	.	PUNCT	DELM	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 6 xcomp	color:blue
1	مادر	مادر	NOUN	N_SING	Number=Sing	0	root	_	SpaceAfter=No
2	:	:	PUNCT	DELM	_	1	punct	_	_
3	تو	تو	ADP	P	_	4	case	_	_
4	سایه	سایه	NOUN	N_SING	Number=Sing	5	obl	_	_
5	برو	رفت#رو	VERB	V_IMP	Mood=Imp|Number=Sing|Person=2	1	parataxis	_	_
6	تشنه‌	تشنه	NOUN	N_SING	Number=Sing	8	xcomp	_	_
7	ت	تو	PRON	PRO	Number=Sing|Person=2|PronType=Prs	6	nsubj:nc	_	_
8	نشه	_	VERB	V_SUB	Mood=Sub	5	ccomp	_	SpaceAfter=No
9	.	.	PUNCT	DELM	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 2 xcomp	color:blue
1	ما	ما	PRON	PRO	Number=Plur|Person=1|PronType=Prs	7	nsubj	_	_
2	بهتر	به	ADJ	ADJ_CMPR	Degree=Cmp	7	xcomp	_	_
3	و	و	CCONJ	CON	_	4	cc	_	_
4	بیشتر	بیش	ADJ	ADJ_CMPR	Degree=Cmp	2	conj	_	_
5	از	از	ADP	P	_	6	case	_	_
6	قبل	قبل	ADV	ADV_TIME	Case=Tem	4	advcl	_	_
7	متوجه	متوجه	NOUN	N_SING	Number=Sing	0	root	_	_
8	این	این	DET	DET	_	9	det	_	_
9	محور	محور	NOUN	N_SING	Number=Sing	7	nmod:poss	_	_
10	مهم	مهم	ADJ	ADJ	Degree=Pos	9	amod	_	_
11	شده‌ایم	_	AUX	V_PP	Number=Plur|Person=1|VerbForm=Part	7	cop	_	SpaceAfter=No
12	.	.	PUNCT	DELM	_	7	punct	_	_

~~~


