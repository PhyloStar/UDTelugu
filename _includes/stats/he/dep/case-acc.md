

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Hebrew)

This relation is a language-specific subtype of [case]().
There are also 1 other language-specific subtypes of `case`: [case:gen]().

1831 nodes (1%) are attached to their parents as `case:acc`.

1831 instances of `case:acc` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.45057345712725.

The following 9 pairs of parts of speech are connected with `case:acc`: [he-pos/NOUN]()-[he-pos/PART]() (1340; 73% instances), [he-pos/PRON]()-[he-pos/PART]() (283; 15% instances), [he-pos/PROPN]()-[he-pos/PART]() (163; 9% instances), [he-pos/VERB]()-[he-pos/PART]() (23; 1% instances), [he-pos/ADV]()-[he-pos/PART]() (11; 1% instances), [he-pos/ADJ]()-[he-pos/PART]() (4; 0% instances), [he-pos/NUM]()-[he-pos/PART]() (4; 0% instances), [he-pos/DET]()-[he-pos/PART]() (2; 0% instances), [he-pos/ADP]()-[he-pos/PART]() (1; 0% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 3 case:acc	color:blue
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


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 6 case:acc	color:blue
1	בית	בית	NOUN	NOUN	Definite=Cons|Gender=Masc|Number=Sing	5	nsubj	_	_
2	משפט	משפט	NOUN	NOUN	Gender=Masc|Number=Sing	1	compound:smixut	_	_
3	ב	ב	ADP	ADP	_	4	case	_	_
4	ליון	ליון	PROPN	PROPN	_	1	nmod	_	_
5	דן	דן	VERB	VERB	Gender=Masc|HebBinyan=PAAL|Number=Sing|Person=3|Tense=Past|Voice=Act	0	root	_	_
6	את_	את	PART	PART	Case=Acc	7	case:acc	_	_
7	_הוא	הוא	PRON	PRON	Gender=Masc|Number=Sing|Person=3|PronType=Prs	5	obj	_	_
8	ל	ל	ADP	ADP	_	10	case	_	_
9	ה_	ה	DET	DET	PronType=Art	10	det:def	_	_
10	מוות	מוות	NOUN	NOUN	Gender=Masc|Number=Sing	5	iobj	_	_
11	שלא	שלא	ADV	ADV	_	12	advmod	_	_
12	ב	ב	ADP	ADP	_	13	case	_	_
13	פנים_	פנים	NOUN	NOUN	Definite=Def|Gender=Fem,Masc|Number=Plur	5	obl	_	_
14	_של_	של	ADP	ADP	_	15	case:gen	_	_
15	_הוא	הוא	PRON	PRON	Case=Gen|Gender=Masc|Number=Sing|Person=3|PronType=Prs	13	nmod:poss	_	_
16	.	_	PUNCT	PUNCT	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 case:acc	color:blue
1	קחו	לקח	VERB	VERB	Gender=Fem,Masc|HebBinyan=PAAL|Mood=Imp|Number=Plur|Person=2|Voice=Act	0	root	_	_
2	למשל	למשל	CCONJ	CCONJ	_	1	advmod	_	_
3	את	את	PART	PART	Case=Acc	4	case:acc	_	_
4	מריה	מריה	PROPN	PROPN	_	1	obj	_	_
5	ואראלה	ואראלה	PROPN	PROPN	_	4	flat:name	_	_
6	.	_	PUNCT	PUNCT	_	1	punct	_	_

~~~


