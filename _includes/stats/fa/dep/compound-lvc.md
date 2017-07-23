

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Persian)

This relation is a language-specific subtype of [compound]().
There are also 1 other language-specific subtypes of `compound`: [compound:prt]().

4947 nodes (4%) are attached to their parents as `compound:lvc`.

4938 instances of `compound:lvc` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.09803921568627.

The following 18 pairs of parts of speech are connected with `compound:lvc`: [fa-pos/VERB]()-[fa-pos/NOUN]() (4084; 83% instances), [fa-pos/VERB]()-[fa-pos/ADJ]() (479; 10% instances), [fa-pos/NOUN]()-[fa-pos/NOUN]() (194; 4% instances), [fa-pos/NOUN]()-[fa-pos/ADJ]() (127; 3% instances), [fa-pos/ADJ]()-[fa-pos/NOUN]() (22; 0% instances), [fa-pos/VERB]()-[fa-pos/PRON]() (12; 0% instances), [fa-pos/AUX]()-[fa-pos/NOUN]() (6; 0% instances), [fa-pos/NOUN]()-[fa-pos/PRON]() (5; 0% instances), [fa-pos/AUX]()-[fa-pos/ADJ]() (4; 0% instances), [fa-pos/VERB]()-[fa-pos/ADV]() (4; 0% instances), [fa-pos/VERB]()-[fa-pos/ADP]() (2; 0% instances), [fa-pos/VERB]()-[fa-pos/CCONJ]() (2; 0% instances), [fa-pos/ADP]()-[fa-pos/ADJ]() (1; 0% instances), [fa-pos/ADP]()-[fa-pos/NOUN]() (1; 0% instances), [fa-pos/NOUN]()-[fa-pos/CCONJ]() (1; 0% instances), [fa-pos/NOUN]()-[fa-pos/VERB]() (1; 0% instances), [fa-pos/VERB]()-[fa-pos/SCONJ]() (1; 0% instances), [fa-pos/VERB]()-[fa-pos/VERB]() (1; 0% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 compound:lvc	color:blue
1	تقاضاهای	تقاضا	NOUN	N_PL	Number=Plur	5	obj	_	_
2	مردم	مردم	NOUN	N_SING	Number=Sing	1	nmod:poss	_	_
3	را	را	PART	CLITIC	_	1	case	_	_
4	تعدیل	تعدیل	NOUN	N_SING	Number=Sing	5	compound:lvc	_	_
5	می‌کنند	کرد#کن	VERB	V_PRS	Number=Plur|Person=3|Tense=Pres	0	root	_	SpaceAfter=No
6	.	.	PUNCT	DELM	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 11 10 compound:lvc	color:blue
1	در	در	ADP	P	_	2	case	_	_
2	برخورد	برخورد	NOUN	N_SING	Number=Sing	11	obl	_	_
3	با	با	ADP	P	_	5	case	_	_
4	این	این	DET	DET	_	5	det	_	_
5	بحران‌آفرینی	_	NOUN	N_SING	Number=Sing	2	nmod	_	_
6	تنها	تنها	ADV	ADV	_	11	advmod	_	_
7	نمی‌توان	توان	AUX	V_AUX	_	11	aux	_	_
8	به	به	ADP	P	_	9	case	_	_
9	تحلیل	تحلیل	NOUN	N_SING	Number=Sing	11	obl	_	_
10	بسنده	بسنده	ADJ	ADJ	Degree=Pos	11	compound:lvc	_	_
11	کرد	کرد#کن	VERB	V_PA	Number=Sing|Person=3|Tense=Past	0	root	_	SpaceAfter=No
12	.	.	PUNCT	DELM	_	11	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 compound:lvc	color:blue
1	صدای	صدا	NOUN	N_SING	Number=Sing	10	nsubj	_	_
2	دست	دست	NOUN	N_SING	Number=Sing	3	compound:lvc	_	_
3	زدن	زدن	NOUN	N_SING	Number=Sing	1	nmod:poss	_	_
4	بچه‌ها	بچه	NOUN	N_PL	Number=Plur	3	nmod:poss	_	SpaceAfter=No
5	،	،	PUNCT	DELM	_	10	punct	_	_
6	احمد	احمد	NOUN	N_SING	Number=Sing	10	obj	_	_
7	را	را	PART	CLITIC	_	6	case	_	_
8	به	به	ADP	P	_	9	case	_	_
9	خود	خود	PRON	PRO	Number=Sing|Person=3|PronType=Prs|Reflex=Yes	10	obl	_	_
10	می‌آورد	آورد#آور	VERB	V_PRS	Number=Sing|Person=3|Tense=Pres	0	root	_	SpaceAfter=No
11	.	.	PUNCT	DELM	_	10	punct	_	_

~~~


