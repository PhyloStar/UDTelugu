

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Hebrew)

This relation is universal.

1556 nodes (1%) are attached to their parents as `appos`.

1551 instances of `appos` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 4.18251928020566.

The following 38 pairs of parts of speech are connected with `appos`: [he-pos/NOUN]()-[he-pos/PROPN]() (723; 46% instances), [he-pos/NOUN]()-[he-pos/NOUN]() (405; 26% instances), [he-pos/PROPN]()-[he-pos/NOUN]() (147; 9% instances), [he-pos/NOUN]()-[he-pos/VERB]() (69; 4% instances), [he-pos/PROPN]()-[he-pos/PROPN]() (32; 2% instances), [he-pos/NOUN]()-[he-pos/NUM]() (31; 2% instances), [he-pos/NOUN]()-[he-pos/ADJ]() (26; 2% instances), [he-pos/PROPN]()-[he-pos/NUM]() (19; 1% instances), [he-pos/NOUN]()-[he-pos/PRON]() (11; 1% instances), [he-pos/NOUN]()-[he-pos/CCONJ]() (10; 1% instances), [he-pos/VERB]()-[he-pos/PROPN]() (10; 1% instances), [he-pos/NOUN]()-[he-pos/ADV]() (9; 1% instances), [he-pos/NUM]()-[he-pos/NOUN]() (8; 1% instances), [he-pos/ADJ]()-[he-pos/PROPN]() (6; 0% instances), [he-pos/NUM]()-[he-pos/NUM]() (5; 0% instances), [he-pos/PROPN]()-[he-pos/ADJ]() (5; 0% instances), [he-pos/PROPN]()-[he-pos/VERB]() (5; 0% instances), [he-pos/VERB]()-[he-pos/NOUN]() (5; 0% instances), [he-pos/NOUN]()-[he-pos/AUX]() (3; 0% instances), [he-pos/NOUN]()-[he-pos/PUNCT]() (3; 0% instances), [he-pos/PRON]()-[he-pos/PROPN]() (3; 0% instances), [he-pos/ADJ]()-[he-pos/NOUN]() (2; 0% instances), [he-pos/ADV]()-[he-pos/NOUN]() (2; 0% instances), [he-pos/PRON]()-[he-pos/NOUN]() (2; 0% instances), [he-pos/X]()-[he-pos/PROPN]() (2; 0% instances), [he-pos/ADJ]()-[he-pos/NUM]() (1; 0% instances), [he-pos/ADP]()-[he-pos/NOUN]() (1; 0% instances), [he-pos/NOUN]()-[he-pos/ADP]() (1; 0% instances), [he-pos/NOUN]()-[he-pos/DET]() (1; 0% instances), [he-pos/NOUN]()-[he-pos/SCONJ]() (1; 0% instances), [he-pos/NOUN]()-[he-pos/X]() (1; 0% instances), [he-pos/NUM]()-[he-pos/VERB]() (1; 0% instances), [he-pos/PRON]()-[he-pos/CCONJ]() (1; 0% instances), [he-pos/PROPN]()-[he-pos/PRON]() (1; 0% instances), [he-pos/PROPN]()-[he-pos/SCONJ]() (1; 0% instances), [he-pos/VERB]()-[he-pos/ADJ]() (1; 0% instances), [he-pos/VERB]()-[he-pos/CCONJ]() (1; 0% instances), [he-pos/VERB]()-[he-pos/VERB]() (1; 0% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 4 appos	color:blue
1	בני	בן	NOUN	NOUN	Definite=Cons|Gender=Masc|Number=Plur	5	nsubj	_	_
2	ה	ה	DET	DET	PronType=Art	3	det:def	_	_
3	זוג	זוג	NOUN	NOUN	Gender=Masc|Number=Sing	1	compound:smixut	_	_
4	גרוסבורד	גרוסבורד	PROPN	PROPN	_	1	appos	_	_
5	תוכננו	תוכנן	VERB	VERB	Gender=Fem,Masc|HebBinyan=PUAL|Number=Plur|Person=3|Tense=Past|Voice=Pass	0	root	_	_
6	לשוב	שב	VERB	VERB	HebBinyan=PAAL|VerbForm=Inf|Voice=Act	5	xcomp	_	_
7	היום	היום	ADV	ADV	_	6	advmod:phrase	_	_
8	אחרי	אחרי	ADP	ADP	_	11	case	_	_
9	-	_	PUNCT	PUNCT	_	11	punct	_	_
10	ה	ה	DET	DET	PronType=Art	11	det:def	_	_
11	צהריים	צהריים	NOUN	NOUN	Gender=Masc|Number=Plur	7	advmod	_	_
12	ל	ל	ADP	ADP	_	13	case	_	_
13	ישראל	ישראל	PROPN	PROPN	_	6	obl	_	_
14	.	_	PUNCT	PUNCT	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 12 appos	color:blue
1	לא	לא	ADV	ADV	Polarity=Neg	2	advmod	_	_
2	נהרגו	נהרג	VERB	VERB	Gender=Fem,Masc|HebBinyan=NIFAL|Number=Plur|Person=3|Tense=Past|Voice=Mid	0	root	_	_
3	"	_	PUNCT	PUNCT	_	4	punct	_	_
4	נזירות	נזירה	NOUN	NOUN	Gender=Fem|Number=Plur	2	nsubj	_	_
5	"	_	PUNCT	PUNCT	_	4	punct	_	_
6	,	_	PUNCT	PUNCT	_	4	punct	_	_
7	אלא	אלא	CCONJ	CCONJ	_	8	cc	_	_
8	נשים	איש	NOUN	NOUN	Gender=Fem|Number=Plur	4	conj	_	_
9	ערביות	ערבי	ADJ	ADJ	Gender=Fem|Number=Plur	8	amod	_	_
10	,	_	PUNCT	PUNCT	_	8	punct	_	_
11	כנראה	כנראה	ADV	ADV	_	12	det	_	_
12	משרתות	משרת	NOUN	NOUN	Gender=Fem|Number=Plur	8	appos	_	_
13	ב	ב	ADP	ADP	_	15	case	_	_
14	ה_	ה	DET	DET	PronType=Art	15	det:def	_	_
15	מנזר	מנזר	NOUN	NOUN	Gender=Masc|Number=Sing	12	nmod	_	_
16	.	_	PUNCT	PUNCT	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 8 appos	color:blue
1	על	על	ADP	ADP	_	3	case	_	_
2	ה	ה	DET	DET	PronType=Art	3	det:def	_	_
3	חתום	חתום	NOUN	NOUN	Gender=Masc|Number=Sing	0	root	_	_
4	נגה	נגה	PROPN	PROPN	_	3	nsubj	_	_
5	ענתבי	ענתבי	PROPN	PROPN	_	4	flat:name	_	_
6	,	_	PUNCT	PUNCT	_	4	punct	_	_
7	ה	ה	DET	DET	PronType=Art	8	det:def	_	_
8	ממונה	ממונה	NOUN	NOUN	Gender=Fem|Number=Sing	4	appos	_	_
9	על	על	ADP	ADP	_	10	case	_	_
10	נוסח	נוסח	NOUN	NOUN	Definite=Cons|Gender=Masc|Number=Sing	8	nmod	_	_
11	ה	ה	DET	DET	PronType=Art	12	det:def	_	_
12	חוק	חוק	NOUN	NOUN	Gender=Masc|Number=Sing	10	compound:smixut	_	_
13	ו	ו	CCONJ	CCONJ	_	14	cc	_	_
14	רשומות	רשומות	NOUN	NOUN	Gender=Fem|Number=Plur	10	conj	_	_
15	.	_	PUNCT	PUNCT	_	3	punct	_	_

~~~


