

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Persian)

This relation is universal.

3763 nodes (3%) are attached to their parents as `mark`.

3758 instances of `mark` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 7.40924794047303.

The following 24 pairs of parts of speech are connected with `mark`: [fa-pos/VERB]()-[fa-pos/SCONJ]() (2394; 64% instances), [fa-pos/NOUN]()-[fa-pos/SCONJ]() (578; 15% instances), [fa-pos/ADJ]()-[fa-pos/SCONJ]() (537; 14% instances), [fa-pos/VERB]()-[fa-pos/ADP]() (103; 3% instances), [fa-pos/VERB]()-[fa-pos/ADV]() (32; 1% instances), [fa-pos/NOUN]()-[fa-pos/ADP]() (24; 1% instances), [fa-pos/ADV]()-[fa-pos/SCONJ]() (18; 0% instances), [fa-pos/ADJ]()-[fa-pos/ADP]() (14; 0% instances), [fa-pos/VERB]()-[fa-pos/DET]() (10; 0% instances), [fa-pos/NOUN]()-[fa-pos/ADV]() (8; 0% instances), [fa-pos/AUX]()-[fa-pos/SCONJ]() (7; 0% instances), [fa-pos/NUM]()-[fa-pos/SCONJ]() (7; 0% instances), [fa-pos/ADJ]()-[fa-pos/ADV]() (6; 0% instances), [fa-pos/VERB]()-[fa-pos/PRON]() (5; 0% instances), [fa-pos/ADJ]()-[fa-pos/DET]() (4; 0% instances), [fa-pos/NOUN]()-[fa-pos/DET]() (4; 0% instances), [fa-pos/PRON]()-[fa-pos/SCONJ]() (4; 0% instances), [fa-pos/VERB]()-[fa-pos/NOUN]() (2; 0% instances), [fa-pos/ADJ]()-[fa-pos/PRON]() (1; 0% instances), [fa-pos/ADP]()-[fa-pos/SCONJ]() (1; 0% instances), [fa-pos/ADV]()-[fa-pos/ADP]() (1; 0% instances), [fa-pos/NOUN]()-[fa-pos/ADJ]() (1; 0% instances), [fa-pos/PUNCT]()-[fa-pos/SCONJ]() (1; 0% instances), [fa-pos/VERB]()-[fa-pos/ADJ]() (1; 0% instances).


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 15	bgColor:blue
# visual-style 15	fgColor:white
# visual-style 15 7 mark	color:blue
1	معاویه	معاویه	NOUN	N_SING	Number=Sing	2	nsubj	_	_
2	گفت	گفت#گو	VERB	V_PA	Number=Sing|Person=3|Tense=Past	0	root	_	SpaceAfter=No
3	:	:	PUNCT	DELM	_	2	punct	_	_
4	من	من	PRON	PRO	Number=Sing|Person=1|PronType=Prs	6	nsubj	_	_
5	تصمیم	تصمیم	NOUN	N_SING	Number=Sing	6	compound:lvc	_	_
6	دارم	داشت#دار	VERB	V_PRS	Number=Sing|Person=1|Tense=Pres	2	ccomp	_	_
7	که	که	SCONJ	CON	_	15	mark	_	_
8	نام	نام	NOUN	N_SING	Number=Sing	15	obj	_	_
9	و	و	CCONJ	CON	_	10	cc	_	_
10	یاد	یاد	NOUN	N_SING	Number=Sing	8	conj	_	_
11	او	او	PRON	PRO	Number=Sing|Person=3|PronType=Prs	10	nmod:poss	_	_
12	را	را	PART	CLITIC	_	8	case	_	_
13	از	از	ADP	P	_	15	case	_	_
14	بین	بین	ADP	P	_	13	fixed	_	_
15	ببرم	_	VERB	V_SUB	Mood=Sub|Number=Sing|Person=1|Tense=Pres	6	ccomp	_	SpaceAfter=No
16	.	.	PUNCT	DELM	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 mark	color:blue
1	در	در	ADP	P	_	2	case	_	_
2	نامه	نامه	NOUN	N_SING	Number=Sing	4	obl	_	_
3	ات	_	PRON	PRO	Number=Sing|Person=2|PronType=Prs	2	nmod:poss	_	_
4	نوشته‌ای	نوشت#نویس	VERB	V_PP	Number=Sing|Person=2|VerbForm=Part	0	root	_	_
5	که	که	SCONJ	CON	_	6	mark	_	_
6	متوجه	متوجه	NOUN	N_SING	Number=Sing	4	ccomp	_	_
7	خود	خود	PRON	PRO	Number=Sing|Person=3|PronType=Prs|Reflex=Yes	6	nmod:poss	_	_
8	ت	تو	PRON	PRO	Number=Sing|Person=2|PronType=Prs	7	nmod:poss	_	_
9	و	و	CCONJ	CON	_	10	cc	_	_
10	دین	دین	NOUN	N_SING	Number=Sing	7	conj	_	_
11	ت	تو	PRON	PRO	Number=Sing|Person=2|PronType=Prs	10	nmod:poss	_	_
12	و	و	CCONJ	CON	_	13	cc	_	_
13	امت	امت	NOUN	N_SING	Number=Sing	10	conj	_	_
14	محمد	محمد	NOUN	N_SING	Number=Sing	13	nmod:poss	_	SpaceAfter=No
15	)	)	PUNCT	DELM	_	14	punct	_	_
16	ص	ص	NOUN	N_SING	Number=Sing	14	dep	_	_
17	(	(	PUNCT	DELM	_	14	punct	_	SpaceAfter=No
18	باش	بود#باش	AUX	V_IMP	Mood=Imp|Number=Sing|Person=2	6	cop	_	SpaceAfter=No
19	.	.	PUNCT	DELM	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 6 mark	color:blue
1	در	در	ADP	P	_	2	case	_	_
2	مورد	مورد	NOUN	N_SING	Number=Sing	5	obl	_	_
3	عبدالله‌بن‌زبیر	عبدالله‌بن‌زبیر	NOUN	N_SING	Number=Sing	2	nmod:poss	_	_
4	سفارش	_	NOUN	N_SING	Number=Sing	5	compound:lvc	_	_
5	می‌کند	کرد#کن	VERB	V_PRS	Number=Sing|Person=3|Tense=Pres	0	root	_	_
6	که	که	SCONJ	CON	_	8	mark	_	_
7	کاملاً	کاملاً	ADV	ADV	_	8	advmod	_	_
8	مواظب	مواظب	ADJ	ADJ	Degree=Pos	5	ccomp	_	_
9	او	او	PRON	PRO	Number=Sing|Person=3|PronType=Prs	8	nmod:poss	_	_
10	باش	بود#باش	AUX	V_IMP	Mood=Imp|Number=Sing|Person=2	8	cop	_	SpaceAfter=No
11	.	.	PUNCT	DELM	_	5	punct	_	_

~~~


