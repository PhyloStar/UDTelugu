

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Chinese)

This relation is a language-specific subtype of [nsubj]().

245 nodes (0%) are attached to their parents as `nsubj:pass`.

245 instances of `nsubj:pass` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 5.8.

The following 7 pairs of parts of speech are connected with `nsubj:pass`: [zh-pos/VERB]()-[zh-pos/NOUN]() (134; 55% instances), [zh-pos/VERB]()-[zh-pos/PROPN]() (61; 25% instances), [zh-pos/VERB]()-[zh-pos/PART]() (24; 10% instances), [zh-pos/VERB]()-[zh-pos/PRON]() (22; 9% instances), [zh-pos/VERB]()-[zh-pos/ADJ]() (2; 1% instances), [zh-pos/ADJ]()-[zh-pos/NOUN]() (1; 0% instances), [zh-pos/VERB]()-[zh-pos/NUM]() (1; 0% instances).


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 16	bgColor:blue
# visual-style 16	fgColor:white
# visual-style 16 10 nsubj:pass	color:blue
1	市內	市內	NOUN	NN	_	4	nsubj	_	SpaceAfter=No
2	後來	後來	NOUN	NN	_	4	nmod:tmod	_	SpaceAfter=No
3	也	也	ADV	RB	_	4	mark	_	SpaceAfter=No
4	鋪設	鋪設	VERB	VV	_	16	dep	_	SpaceAfter=No
5	了	了	PART	AS	Aspect=Perf	4	case:aspect	_	SpaceAfter=No
6	有軌	有軌	NOUN	NN	_	8	nmod	_	SpaceAfter=No
7	電車	電車	NOUN	NN	_	8	nmod	_	SpaceAfter=No
8	系統	系統	NOUN	NN	_	4	obj	_	SpaceAfter=No
9	,	,	PUNCT	,	_	16	punct	_	SpaceAfter=No
10	地段	地段	NOUN	NN	_	16	nsubj:pass	_	SpaceAfter=No
11	亦	亦	ADV	RB	_	16	mark	_	SpaceAfter=No
12	被	被	VERB	BB	Voice=Pass	16	aux:pass	_	SpaceAfter=No
13	投機	投機	VERB	VV	_	14	case:suff	_	SpaceAfter=No
14	者	者	PART	SFN	_	16	nsubj	_	SpaceAfter=No
15	所	所	ADV	RB	_	16	mark	_	SpaceAfter=No
16	覬覦	覬覦	VERB	VV	_	0	root	_	SpaceAfter=No
17	.	.	PUNCT	.	_	16	punct	_	SpaceAfter=No

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 12 4 nsubj:pass	color:blue
1	1355	1355	NUM	CD	NumType=Card	2	nummod	_	SpaceAfter=No
2	年	年	NOUN	NNB	_	12	nmod:tmod	_	SpaceAfter=No
3	,	,	PUNCT	,	_	12	punct	_	SpaceAfter=No
4	勃蘭登堡	勃蘭登堡	PROPN	NNP	_	12	nsubj:pass	_	SpaceAfter=No
5	被	被	VERB	BB	Voice=Pass	12	aux:pass	_	SpaceAfter=No
6	神聖	神聖	ADJ	JJ	_	8	amod	_	SpaceAfter=No
7	羅馬	羅馬	PROPN	NNP	_	8	nmod	_	SpaceAfter=No
8	帝國	帝國	NOUN	NN	_	9	nmod	_	SpaceAfter=No
9	皇帝	皇帝	NOUN	NN	_	11	appos	_	SpaceAfter=No
10	查理	查理	PROPN	NNP	_	11	nmod	_	SpaceAfter=No
11	四世	四世	PROPN	NNP	_	12	nsubj	_	SpaceAfter=No
12	升	升	VERB	VV	_	0	root	_	SpaceAfter=No
13	為	為	VERB	VC	_	12	mark	_	SpaceAfter=No
14	選侯	選侯	VERB	VV	_	15	case:suff	_	SpaceAfter=No
15	國	國	PART	SFN	_	12	obj	_	SpaceAfter=No
16	.	.	PUNCT	.	_	12	punct	_	SpaceAfter=No

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 4 nsubj:pass	color:blue
1	數百萬	數百萬	NUM	CD	NumType=Card	4	det	_	SpaceAfter=No
2	的	的	PART	DEC	Case=Gen	1	case:dec	_	SpaceAfter=No
3	巧克力	巧克力	NOUN	NN	_	4	case:suff	_	SpaceAfter=No
4	棒	棒	PART	SFN	_	6	nsubj:pass	_	SpaceAfter=No
5	被	被	VERB	BB	Voice=Pass	6	aux:pass	_	SpaceAfter=No
6	撤下	撤下	VERB	VV	_	18	dep	_	SpaceAfter=No
7	櫃檯	櫃檯	NOUN	NN	_	6	obj	_	SpaceAfter=No
8	,	,	PUNCT	,	_	18	punct	_	SpaceAfter=No
9	而	而	ADV	RB	_	12	mark	_	SpaceAfter=No
10	瑪氏	瑪氏	PROPN	NNP	_	12	nsubj	_	SpaceAfter=No
11	則	則	ADV	RB	_	12	mark	_	SpaceAfter=No
12	中斷	中斷	VERB	VV	_	18	dep	_	SpaceAfter=No
13	了	了	PART	AS	Aspect=Perf	12	case:aspect	_	SpaceAfter=No
14	生產	生產	NOUN	NN	_	12	obj	_	SpaceAfter=No
15	,	,	PUNCT	,	_	18	punct	_	SpaceAfter=No
16	公司	公司	NOUN	NN	_	17	nmod	_	SpaceAfter=No
17	損失	損失	NOUN	NN	_	18	nsubj	_	SpaceAfter=No
18	達	達	VERB	VV	_	0	root	_	SpaceAfter=No
19	四百五十萬	四百五十萬	NUM	CD	NumType=Card	21	nummod	_	SpaceAfter=No
20	美	美	PROPN	NNP	_	21	nmod	_	SpaceAfter=No
21	元	元	NOUN	NNB	_	18	obj	_	SpaceAfter=No
22	.	.	PUNCT	.	_	18	punct	_	SpaceAfter=No

~~~


