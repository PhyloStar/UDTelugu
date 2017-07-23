

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Hebrew)

This relation is a language-specific subtype of [compound]().

7985 nodes (5%) are attached to their parents as `compound:smixut`.

7985 instances of `compound:smixut` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.49906073888541.

The following 18 pairs of parts of speech are connected with `compound:smixut`: [he-pos/NOUN]()-[he-pos/NOUN]() (6720; 84% instances), [he-pos/NOUN]()-[he-pos/PROPN]() (831; 10% instances), [he-pos/NOUN]()-[he-pos/NUM]() (178; 2% instances), [he-pos/ADJ]()-[he-pos/NOUN]() (73; 1% instances), [he-pos/VERB]()-[he-pos/NOUN]() (68; 1% instances), [he-pos/NOUN]()-[he-pos/VERB]() (49; 1% instances), [he-pos/NOUN]()-[he-pos/PRON]() (16; 0% instances), [he-pos/NOUN]()-[he-pos/ADJ]() (10; 0% instances), [he-pos/NOUN]()-[he-pos/CCONJ]() (10; 0% instances), [he-pos/X]()-[he-pos/NOUN]() (8; 0% instances), [he-pos/NOUN]()-[he-pos/DET]() (7; 0% instances), [he-pos/NOUN]()-[he-pos/ADV]() (5; 0% instances), [he-pos/VERB]()-[he-pos/PROPN]() (4; 0% instances), [he-pos/NOUN]()-[he-pos/X]() (2; 0% instances), [he-pos/ADP]()-[he-pos/NOUN]() (1; 0% instances), [he-pos/DET]()-[he-pos/NOUN]() (1; 0% instances), [he-pos/NUM]()-[he-pos/NOUN]() (1; 0% instances), [he-pos/X]()-[he-pos/VERB]() (1; 0% instances).


~~~ conllu
# visual-style 16	bgColor:blue
# visual-style 16	fgColor:white
# visual-style 14	bgColor:blue
# visual-style 14	fgColor:white
# visual-style 14 16 compound:smixut	color:blue
1	ה	ה	DET	DET	PronType=Art	2	det:def	_	_
2	מוח	מוח	NOUN	NOUN	Gender=Masc|Number=Sing	3	nsubj	_	_
3	מתפלץ	התפלץ	VERB	VERB	Gender=Masc|HebBinyan=HITPAEL|Number=Sing|Person=1,2,3|VerbForm=Part	0	root	_	_
4	לא	לא	ADV	ADV	Polarity=Neg	5	advmod	_	_
5	רק	רק	ADV	ADV	_	6	advmod	_	_
6	מ	מ	ADP	ADP	_	8	case	_	_
7	ה	ה	DET	DET	PronType=Art	8	det:def	_	_
8	תופעה	תופעה	NOUN	NOUN	Gender=Fem|Number=Sing	3	obl	_	_
9	ה	ה	DET	DET	PronType=Art	10	det:def	_	_
10	מבישה	מביש	ADJ	ADJ	Gender=Fem|Number=Sing	8	amod	_	_
11	אלא	אלא	CCONJ	CCONJ	_	14	cc	_	_
12	גם	גם	ADV	ADV	_	13	advmod	_	_
13	מ	מ	ADP	ADP	_	14	case	_	_
14	דרכי	דרך	NOUN	NOUN	Definite=Cons|Gender=Fem|Number=Plur	8	conj	_	_
15	ה	ה	DET	DET	PronType=Art	16	det:def	_	_
16	הערמה	הערמה	NOUN	NOUN	Gender=Fem|Number=Sing	14	compound:smixut	_	_
17	.	_	PUNCT	PUNCT	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 9 compound:smixut	color:blue
1	זו	זו	PRON	PRON	Gender=Fem|Number=Sing|Person=3|PronType=Dem	4	nsubj	_	_
2	אחת	אחת	NUM	NUM	Definite=Cons|Gender=Fem|Number=Sing	4	nummod	_	_
3	ה	ה	DET	DET	PronType=Art	4	det:def	_	_
4	סיבות	סיבה	NOUN	NOUN	Gender=Fem|Number=Plur	0	root	_	_
5	ל	ל	ADP	ADP	_	6	case	_	_
6	כך	כך	PRON	PRON	Person=3|PronType=Dem	4	nmod	_	_
7	ש	ש	SCONJ	SCONJ	_	10	mark	_	_
8	מענקי	מענק	NOUN	NOUN	Definite=Cons|Gender=Masc|Number=Plur	10	nsubj	_	_
9	מקארתור	מקארתור	PROPN	PROPN	_	8	compound:smixut	_	_
10	מבוקשים	מבוקש	ADJ	ADJ	Gender=Masc|Number=Plur	6	acl:relcl	_	_
11	כל	כול	DET	DET	Definite=Cons	10	advmod	_	_
12	כך	כך	ADV	ADV	_	11	fixed	_	_
13	.	_	PUNCT	PUNCT	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 10 compound:smixut	color:blue
1	איובה	איובה	PROPN	PROPN	_	2	nsubj	_	_
2	שילמה	שילם	VERB	VERB	Gender=Fem|HebBinyan=PIEL|Number=Sing|Person=3|Tense=Past|Voice=Act	0	root	_	_
3	את	את	PART	PART	Case=Acc	5	case:acc	_	_
4	ה	ה	DET	DET	PronType=Art	5	det:def	_	_
5	מחיר	מחיר	NOUN	NOUN	Gender=Masc|Number=Sing	2	obj	_	_
6	עד	עד	ADP	ADP	_	7	case	_	_
7	אמצע	אמצע	NOUN	NOUN	Definite=Cons|Gender=Masc|Number=Sing	2	obl	_	_
8	שנות	שנה	NOUN	NOUN	Definite=Cons|Gender=Fem|Number=Plur	7	compound:smixut	_	_
9	ה	ה	DET	DET	PronType=Art	10	det:def	_	_
10	80	_	NUM	NUM	_	8	compound:smixut	_	_
11	.	_	PUNCT	PUNCT	_	2	punct	_	_

~~~


