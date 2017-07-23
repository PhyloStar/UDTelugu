

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Persian)

This relation is universal.

3505 nodes (3%) are attached to their parents as `obj`.

3444 instances of `obj` (98%) are right-to-left (child precedes parent).
Average distance between parent and child is 5.82082738944365.

The following 23 pairs of parts of speech are connected with `obj`: [fa-pos/VERB]()-[fa-pos/NOUN]() (2950; 84% instances), [fa-pos/VERB]()-[fa-pos/PRON]() (300; 9% instances), [fa-pos/ADJ]()-[fa-pos/NOUN]() (70; 2% instances), [fa-pos/NOUN]()-[fa-pos/NOUN]() (62; 2% instances), [fa-pos/VERB]()-[fa-pos/ADV]() (37; 1% instances), [fa-pos/VERB]()-[fa-pos/ADJ]() (36; 1% instances), [fa-pos/AUX]()-[fa-pos/NOUN]() (8; 0% instances), [fa-pos/VERB]()-[fa-pos/NUM]() (8; 0% instances), [fa-pos/NOUN]()-[fa-pos/PRON]() (6; 0% instances), [fa-pos/VERB]()-[fa-pos/DET]() (6; 0% instances), [fa-pos/NOUN]()-[fa-pos/ADJ]() (4; 0% instances), [fa-pos/ADP]()-[fa-pos/NOUN]() (3; 0% instances), [fa-pos/ADJ]()-[fa-pos/ADJ]() (2; 0% instances), [fa-pos/ADJ]()-[fa-pos/PRON]() (2; 0% instances), [fa-pos/ADV]()-[fa-pos/NOUN]() (2; 0% instances), [fa-pos/VERB]()-[fa-pos/VERB]() (2; 0% instances), [fa-pos/AUX]()-[fa-pos/ADJ]() (1; 0% instances), [fa-pos/NOUN]()-[fa-pos/ADP]() (1; 0% instances), [fa-pos/NOUN]()-[fa-pos/NUM]() (1; 0% instances), [fa-pos/NOUN]()-[fa-pos/PART]() (1; 0% instances), [fa-pos/PUNCT]()-[fa-pos/NOUN]() (1; 0% instances), [fa-pos/VERB]()-[fa-pos/INTJ]() (1; 0% instances), [fa-pos/VERB]()-[fa-pos/X]() (1; 0% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 1 obj	color:blue
1	خواسته‌های	خواسته	NOUN	N_PL	Number=Plur	7	obj	_	_
2	مردم	مردم	NOUN	N_SING	Number=Sing	1	nmod:poss	_	_
3	را	را	PART	CLITIC	_	1	case	_	_
4	به	به	ADP	P	_	5	case	_	_
5	گوش	گوش	NOUN	N_SING	Number=Sing	7	obl	_	_
6	حکومت	حکومت	NOUN	N_SING	Number=Sing	5	nmod:poss	_	_
7	می‌رسانند	_	VERB	V_PRS	Number=Plur|Person=3|Tense=Pres	0	root	_	SpaceAfter=No
8	.	.	PUNCT	DELM	_	7	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 2 obj	color:blue
1	هرگاه	_	ADV	ADV_TIME	Case=Tem	5	advmod	_	_
2	او	او	PRON	PRO	Number=Sing|Person=3|PronType=Prs	5	obj	_	_
3	را	را	PART	CLITIC	_	2	case	_	_
4	یاد	یاد	NOUN	N_SING	Number=Sing	5	compound:lvc	_	_
5	می‌کنم	_	VERB	V_PRS	Number=Sing|Person=1|Tense=Pres	0	root	_	SpaceAfter=No
6	،	،	PUNCT	DELM	_	5	punct	_	_
7	بر	بر	ADP	P	_	9	case	_	_
8	آن	آن	DET	DET	_	9	det	_	_
9	محبت	_	NOUN	N_SING	Number=Sing	12	obl	_	_
10	و	و	CCONJ	CON	_	11	cc	_	_
11	دوستی	دوستی	NOUN	N_SING	Number=Sing	9	conj	_	_
12	افزوده	افزوده	VERB	V_PP	Number=Sing|Person=3|VerbForm=Part	5	ccomp	_	_
13	می‌شود	کرد#کن	VERB	V_PRS	Number=Sing|Person=3|Tense=Pres	12	aux:pass	_	SpaceAfter=No
14	.	.	PUNCT	DELM	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 obj	color:blue
1	امارت	امارت	NOUN	N_SING	Number=Sing	6	nsubj	_	_
2	بر	بر	ADP	P	_	3	case	_	_
3	اعتبار	اعتبار	NOUN	N_SING	Number=Sing	6	nmod	_	_
4	یزید	یزید	NOUN	N_SING	Number=Sing	3	nmod:poss	_	_
5	چیزی	چیز	NOUN	N_SING	Number=Sing	6	obj	_	_
6	نیفزوده	_	ADJ	ADJ_INO	Number=Sing|Person=3|Polarity=Neg|VerbForm=Part	0	root	_	_
7	است	است	AUX	V_PRS	Number=Sing|Person=3|Tense=Pres	6	cop	_	SpaceAfter=No
8	.	.	PUNCT	DELM	_	6	punct	_	_

~~~


