

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Chinese)

This relation is a language-specific subtype of [acl]().

1609 nodes (1%) are attached to their parents as `acl:relcl`.

1605 instances of `acl:relcl` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 4.5052827843381.

The following 22 pairs of parts of speech are connected with `acl:relcl`: [zh-pos/NOUN]()-[zh-pos/VERB]() (1207; 75% instances), [zh-pos/PART]()-[zh-pos/VERB]() (167; 10% instances), [zh-pos/NOUN]()-[zh-pos/ADJ]() (124; 8% instances), [zh-pos/PROPN]()-[zh-pos/VERB]() (47; 3% instances), [zh-pos/PART]()-[zh-pos/ADJ]() (11; 1% instances), [zh-pos/NOUN]()-[zh-pos/NOUN]() (9; 1% instances), [zh-pos/X]()-[zh-pos/VERB]() (8; 0% instances), [zh-pos/NOUN]()-[zh-pos/PART]() (7; 0% instances), [zh-pos/VERB]()-[zh-pos/VERB]() (6; 0% instances), [zh-pos/NOUN]()-[zh-pos/ADP]() (5; 0% instances), [zh-pos/PROPN]()-[zh-pos/ADJ]() (3; 0% instances), [zh-pos/PROPN]()-[zh-pos/NOUN]() (3; 0% instances), [zh-pos/PRON]()-[zh-pos/VERB]() (2; 0% instances), [zh-pos/VERB]()-[zh-pos/ADJ]() (2; 0% instances), [zh-pos/NOUN]()-[zh-pos/AUX]() (1; 0% instances), [zh-pos/NOUN]()-[zh-pos/PROPN]() (1; 0% instances), [zh-pos/NUM]()-[zh-pos/VERB]() (1; 0% instances), [zh-pos/PART]()-[zh-pos/NOUN]() (1; 0% instances), [zh-pos/PROPN]()-[zh-pos/PART]() (1; 0% instances), [zh-pos/VERB]()-[zh-pos/ADP]() (1; 0% instances), [zh-pos/VERB]()-[zh-pos/PART]() (1; 0% instances), [zh-pos/X]()-[zh-pos/ADJ]() (1; 0% instances).


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 15	bgColor:blue
# visual-style 15	fgColor:white
# visual-style 15 9 acl:relcl	color:blue
1	五	五	NUM	CD	NumType=Card	2	nummod	_	SpaceAfter=No
2	月	月	NOUN	NNB	_	4	clf	_	SpaceAfter=No
3	二十一	二十一	NUM	CD	NumType=Card	4	nummod	_	SpaceAfter=No
4	日	日	NOUN	NNB	_	8	nmod:tmod	_	SpaceAfter=No
5	,	,	PUNCT	,	_	8	punct	_	SpaceAfter=No
6	努爾哈赤	努爾哈赤	PROPN	NNP	_	8	nsubj	_	SpaceAfter=No
7	出城	出城	VERB	VV	_	8	acl	_	SpaceAfter=No
8	迎接	迎接	VERB	VV	_	0	root	_	SpaceAfter=No
9	前來	前來	VERB	VV	_	15	acl:relcl	_	SpaceAfter=No
10	瀋陽	瀋陽	PROPN	NNP	_	9	obj	_	SpaceAfter=No
11	的	的	PART	DEC	_	9	mark:relcl	_	SpaceAfter=No
12	科爾沁	科爾沁	PROPN	NNP	_	13	case:suff	_	SpaceAfter=No
13	部	部	PART	SFN	_	15	nmod	_	SpaceAfter=No
14	奧巴	奧巴	PROPN	NNP	_	15	nmod	_	SpaceAfter=No
15	貝勒	貝勒	NOUN	NN	_	8	obj	_	SpaceAfter=No
16	.	.	PUNCT	.	_	8	punct	_	SpaceAfter=No

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 12 8 acl:relcl	color:blue
1	當	當	ADP	IN	_	6	case	_	SpaceAfter=No
2	《	《	PUNCT	(	_	3	punct	_	SpaceAfter=No
3	Game	Game	X	FW	_	6	nsubj	_	_
4	Informer	Informer	X	FW	_	3	flat:foreign	_	SpaceAfter=No
5	》	》	PUNCT	)	_	3	punct	_	SpaceAfter=No
6	提到	提到	VERB	VV	_	15	ccomp	_	SpaceAfter=No
7	遊戲	遊戲	NOUN	NN	_	8	nsubj	_	SpaceAfter=No
8	在	在	VERB	VV	_	12	acl:relcl	_	SpaceAfter=No
9	日本	日本	PROPN	NNP	_	8	obj	_	SpaceAfter=No
10	的	的	PART	DEC	_	8	mark:relcl	_	SpaceAfter=No
11	知名	知名	ADJ	JJ	_	12	case:suff	_	SpaceAfter=No
12	度	度	PART	SFN	_	6	obj	_	SpaceAfter=No
13	時	時	ADP	IN	_	6	mark	_	SpaceAfter=No
14	甚至	甚至	ADV	RB	_	15	mark	_	SpaceAfter=No
15	說	說	VERB	VV	_	0	root	_	SpaceAfter=No
16	「	「	PUNCT	``	_	19	punct	_	SpaceAfter=No
17	四百萬	四百萬	NUM	CD	NumType=Card	19	nummod	_	SpaceAfter=No
18	日本	日本	PROPN	NNP	_	19	case:suff	_	SpaceAfter=No
19	人	人	PART	SFN	_	21	nsubj	_	SpaceAfter=No
20	可能	可能	AUX	MD	_	21	aux	_	SpaceAfter=No
21	錯	錯	ADJ	JJ	_	15	ccomp	_	SpaceAfter=No
22	了	了	X	UH	_	21	discourse	_	SpaceAfter=No
23	」	」	PUNCT	''	_	21	punct	_	SpaceAfter=No
24	.	.	PUNCT	.	_	15	punct	_	SpaceAfter=No

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 8 acl:relcl	color:blue
1	印度	印度	PROPN	NNP	_	10	nsubj	_	SpaceAfter=No
2	是	是	AUX	VC	_	10	cop	_	SpaceAfter=No
3	世界	世界	NOUN	NN	_	8	advmod	_	SpaceAfter=No
4	上	上	ADP	IN	_	3	acl	_	SpaceAfter=No
5	產婦	產婦	NOUN	NN	_	7	nmod	_	SpaceAfter=No
6	死亡	死亡	VERB	VV	_	7	case:suff	_	SpaceAfter=No
7	率	率	PART	SFN	_	8	nsubj	_	SpaceAfter=No
8	最高	最高	ADJ	JJ	_	10	acl:relcl	_	SpaceAfter=No
9	的	的	PART	DEC	_	8	mark:relcl	_	SpaceAfter=No
10	國家	國家	NOUN	NN	_	20	dep	_	SpaceAfter=No
11	,	,	PUNCT	,	_	20	punct	_	SpaceAfter=No
12	這	這	PRON	PRD	_	20	nsubj	_	SpaceAfter=No
13	和	和	ADP	IN	_	18	case	_	SpaceAfter=No
14	印度	印度	PROPN	NNP	_	16	nmod	_	SpaceAfter=No
15	代孕	代孕	NOUN	NN	_	16	nmod	_	SpaceAfter=No
16	產業	產業	NOUN	NN	_	18	det	_	SpaceAfter=No
17	的	的	PART	DEC	Case=Gen	16	case:dec	_	SpaceAfter=No
18	發展	發展	NOUN	NN	_	20	obl	_	SpaceAfter=No
19	不	不	ADV	RB	Polarity=Neg	20	advmod	_	SpaceAfter=No
20	無	無	VERB	VV	_	0	root	_	SpaceAfter=No
21	關係	關係	NOUN	NN	_	20	obj	_	SpaceAfter=No
22	.	.	PUNCT	.	_	20	punct	_	SpaceAfter=No

~~~


