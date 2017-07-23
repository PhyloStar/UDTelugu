

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Persian)

This relation is universal.
There are 1 language-specific subtypes of `cc`: [cc:preconj]().

6901 nodes (5%) are attached to their parents as `cc`.

6804 instances of `cc` (99%) are right-to-left (child precedes parent).
Average distance between parent and child is 3.51325894797855.

The following 16 pairs of parts of speech are connected with `cc`: [fa-pos/NOUN]()-[fa-pos/CCONJ]() (3666; 53% instances), [fa-pos/VERB]()-[fa-pos/CCONJ]() (1918; 28% instances), [fa-pos/ADJ]()-[fa-pos/CCONJ]() (1074; 16% instances), [fa-pos/NUM]()-[fa-pos/CCONJ]() (86; 1% instances), [fa-pos/ADV]()-[fa-pos/CCONJ]() (76; 1% instances), [fa-pos/PRON]()-[fa-pos/CCONJ]() (57; 1% instances), [fa-pos/ADP]()-[fa-pos/CCONJ]() (4; 0% instances), [fa-pos/CCONJ]()-[fa-pos/CCONJ]() (4; 0% instances), [fa-pos/AUX]()-[fa-pos/CCONJ]() (3; 0% instances), [fa-pos/INTJ]()-[fa-pos/CCONJ]() (3; 0% instances), [fa-pos/PUNCT]()-[fa-pos/CCONJ]() (3; 0% instances), [fa-pos/X]()-[fa-pos/CCONJ]() (3; 0% instances), [fa-pos/DET]()-[fa-pos/CCONJ]() (1; 0% instances), [fa-pos/SCONJ]()-[fa-pos/CCONJ]() (1; 0% instances), [fa-pos/VERB]()-[fa-pos/VERB]() (1; 0% instances), [fa-pos/VERB]()-[fa-pos/X]() (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 cc	color:blue
1	ادامه	ادامه	NOUN	N_SING	Number=Sing	10	nsubj	_	_
2	این	این	DET	DET	_	3	det	_	_
3	وضعیت	وضعیت	NOUN	N_SING	Number=Sing	1	nmod:poss	_	_
4	موج‌آفرینی	_	NOUN	N_SING	Number=Sing	3	nmod:poss	_	_
5	و	و	CCONJ	CON	_	6	cc	_	_
6	بحران‌سازی	بحران‌سازی	NOUN	N_SING	Number=Sing	4	conj	_	_
7	به	به	ADP	P	_	8	case	_	_
8	صلاح	_	NOUN	N_SING	Number=Sing	10	obl	_	_
9	کشور	کشور	NOUN	N_SING	Number=Sing	8	nmod:poss	_	_
10	نیست	هست	VERB	V_PRS	Number=Sing|Person=3|Polarity=Neg|Tense=Pres	0	root	_	SpaceAfter=No
11	.	.	PUNCT	DELM	_	10	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 1 cc	color:blue
1	اما	اما	CCONJ	CON	_	8	cc	_	_
2	اکثریت	اکثریت	NOUN	N_SING	Number=Sing	8	nsubj	_	_
3	مردم	مردم	NOUN	N_SING	Number=Sing	2	nmod:poss	_	SpaceAfter=No
4	،	،	PUNCT	DELM	_	2	punct	_	_
5	بویژه	بویژه	ADV	ADV	_	6	advmod	_	_
6	بنی‌هاشم	_	NOUN	N_SING	Number=Sing	2	appos	_	_
7	مقاومت	مقاومت	NOUN	N_SING	Number=Sing	8	compound:lvc	_	_
8	می‌کنند	کرد#کن	VERB	V_PRS	Number=Plur|Person=3|Tense=Pres	0	root	_	SpaceAfter=No
9	.	.	PUNCT	DELM	_	8	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 1 cc	color:blue
1	و	و	CCONJ	CON	_	6	cc	_	_
2	تو	تو	PRON	PRO	Number=Sing|Person=2|PronType=Prs	6	nsubj	_	_
3	به	به	ADP	P	_	4	case	_	_
4	خود	خود	PRON	PRO	Number=Sing|Person=3|PronType=Prs|Reflex=Yes	6	nmod	_	_
5	ت	تو	PRON	PRO	Number=Sing|Person=2|PronType=Prs	4	nmod:poss	_	_
6	بیناتر	_	ADJ	ADJ	Degree=Pos	0	root	_	_
7	ی	هست	AUX	V_PRS	Number=Sing|Person=2|Tense=Pres	6	cop	_	_
8	!	!	PUNCT	DELM	_	6	punct	_	_

~~~


