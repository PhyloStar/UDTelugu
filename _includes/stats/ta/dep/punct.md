

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Tamil)

This relation is universal.

1000 nodes (10%) are attached to their parents as `punct`.

645 instances of `punct` (65%) are left-to-right (parent precedes child).
Average distance between parent and child is 3.643.

The following 8 pairs of parts of speech are connected with `punct`: [ta-pos/VERB]()-[ta-pos/PUNCT]() (711; 71% instances), [ta-pos/NOUN]()-[ta-pos/PUNCT]() (157; 16% instances), [ta-pos/PROPN]()-[ta-pos/PUNCT]() (77; 8% instances), [ta-pos/AUX]()-[ta-pos/PUNCT]() (18; 2% instances), [ta-pos/NUM]()-[ta-pos/PUNCT]() (16; 2% instances), [ta-pos/PART]()-[ta-pos/PUNCT]() (8; 1% instances), [ta-pos/ADJ]()-[ta-pos/PUNCT]() (7; 1% instances), [ta-pos/PRON]()-[ta-pos/PUNCT]() (6; 1% instances).


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 4 punct	color:blue
1	அவர்	அவர்	PRON	RpN-3SH--	Case=Nom|Gender=Com|Number=Sing|Person=3|Polite=Form|PronType=Prs	2	nsubj	_	Translit=avar|LTranslit=avar
2	பேசியத்	பேசு	VERB	VzND3SNAA	Case=Nom|Gender=Neut|Number=Sing|Person=3|Polarity=Pos|Tense=Past|VerbForm=Ger|Voice=Act	0	root	_	Translit=pēciyat|LTranslit=pēcu
3	ஆவது	ஆவது	PART	Tl-------	_	2	advmod:emph	_	Translit=āvatu|LTranslit=āvatu
4	:	:	PUNCT	Z:-------	PunctType=Comm	2	punct	_	SpaceAfter=No|Translit=:|LTranslit=:
5	.	.	PUNCT	Z#-------	PunctType=Peri	2	punct	_	Translit=.|LTranslit=.

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 8 punct	color:blue
1	இது	இது	PRON	RpN-3SN--	Case=Nom|Gender=Neut|Number=Sing|Person=3|PronType=Prs	2	nmod	_	Translit=itu|LTranslit=itu
2	தொடர்பாக	தொடர்பு	ADV	AA-------	_	6	advmod	_	SpaceAfter=No|Translit=toṭarpāka|LTranslit=toṭarpu
3	,	,	PUNCT	Z:-------	PunctType=Comm	6	punct	_	Translit=,|LTranslit=,
4	அவர்	அவர்	PRON	RpN-3SH--	Case=Nom|Gender=Com|Number=Sing|Person=3|Polite=Form|PronType=Prs	6	nsubj	_	Translit=avar|LTranslit=avar
5	புதன்கிழமை	புதன்கிழமை	NOUN	NNN-3SN--	Case=Nom|Gender=Neut|Number=Sing|Person=3	6	obl	_	Translit=putankilamai|LTranslit=putankilamai
6	வெளியிட்ட	வெளியிடு	ADJ	Jd-D----A	Polarity=Pos|Tense=Past|VerbForm=Part	7	amod	_	Translit=veḷiyiṭṭa|LTranslit=veḷiyiṭu
7	அறிக்கை	அறிக்கை	NOUN	NNN-3SN--	Case=Nom|Gender=Neut|Number=Sing|Person=3	0	root	_	SpaceAfter=No|Translit=arikkai|LTranslit=arikkai
8	:	:	PUNCT	Z:-------	PunctType=Comm	7	punct	_	SpaceAfter=No|Translit=:|LTranslit=:
9	.	.	PUNCT	Z#-------	PunctType=Peri	7	punct	_	Translit=.|LTranslit=.

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 7 punct	color:blue
1	இந்த	இந்த	DET	DD-------	_	3	det	_	Translit=inta|LTranslit=inta
2	இரு	இரு	NUM	Ux-------	NumType=Card	3	nummod	_	Translit=iru|LTranslit=iru
3	இடங்களுக்கு	இடம்	PROPN	NED-3PN--	Case=Dat|Gender=Neut|Number=Plur|Person=3	12	obl	_	Translit=iṭaṅkaḷukku|LTranslit=iṭam
4	கனடா	கனடா	PROPN	NEN-3SN--	Case=Nom|Gender=Neut|Number=Sing|Person=3	9	nmod	_	SpaceAfter=No|Translit=kanaṭā|LTranslit=kanaṭā
5	,	,	PUNCT	Z:-------	PunctType=Comm	6	punct	_	Translit=,|LTranslit=,
6	ஜெர்மனி	ஜெர்மனி	PROPN	NEN-3SN--	Case=Nom|Gender=Neut|Number=Sing|Person=3	4	conj	_	SpaceAfter=No|Translit=jermani|LTranslit=jermani
7	,	,	PUNCT	Z:-------	PunctType=Comm	8	punct	_	Translit=,|LTranslit=,
8	போர்ச்சுக்கல்	போர்ச்சுக்கல்	PROPN	NEN-3SN--	Case=Nom|Gender=Neut|Number=Sing|Person=3	4	conj	_	Translit=pōrccukkal|LTranslit=pōrccukkal
9	ஆகிய	ஆகு	ADJ	Jd-D----A	Polarity=Pos|Tense=Past|VerbForm=Part	11	amod	_	Translit=ākiya|LTranslit=āku
10	3	3	NUM	U=-------	NumForm=Digit	11	nummod	_	Translit=3|LTranslit=3
11	நாடுகள்	நாடு	NOUN	NNN-3PN--	Case=Nom|Gender=Neut|Number=Plur|Person=3	12	nsubj	_	Translit=nāṭukaḷ|LTranslit=nāṭu
12	போட்டியிடுகின்றன	போட்டியிடு	VERB	Vr-P3PNAA	Gender=Neut|Mood=Ind|Number=Plur|Person=3|Polarity=Pos|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	SpaceAfter=No|Translit=pōṭṭiyiṭukinrana|LTranslit=pōṭṭiyiṭu
13	.	.	PUNCT	Z#-------	PunctType=Peri	12	punct	_	Translit=.|LTranslit=.

~~~


