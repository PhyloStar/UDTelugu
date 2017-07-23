

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Chinese)

This relation is universal.

1973 nodes (2%) are attached to their parents as `ccomp`.

1682 instances of `ccomp` (85%) are left-to-right (parent precedes child).
Average distance between parent and child is 7.99493157627978.

The following 27 pairs of parts of speech are connected with `ccomp`: [zh-pos/VERB]()-[zh-pos/VERB]() (1512; 77% instances), [zh-pos/VERB]()-[zh-pos/NOUN]() (177; 9% instances), [zh-pos/VERB]()-[zh-pos/ADJ]() (145; 7% instances), [zh-pos/ADP]()-[zh-pos/VERB]() (34; 2% instances), [zh-pos/VERB]()-[zh-pos/PART]() (30; 2% instances), [zh-pos/ADJ]()-[zh-pos/VERB]() (13; 1% instances), [zh-pos/NOUN]()-[zh-pos/VERB]() (13; 1% instances), [zh-pos/VERB]()-[zh-pos/PROPN]() (10; 1% instances), [zh-pos/ADV]()-[zh-pos/VERB]() (5; 0% instances), [zh-pos/VERB]()-[zh-pos/NUM]() (5; 0% instances), [zh-pos/ADJ]()-[zh-pos/ADJ]() (4; 0% instances), [zh-pos/ADJ]()-[zh-pos/NOUN]() (3; 0% instances), [zh-pos/NOUN]()-[zh-pos/NOUN]() (3; 0% instances), [zh-pos/ADP]()-[zh-pos/NOUN]() (2; 0% instances), [zh-pos/PART]()-[zh-pos/VERB]() (2; 0% instances), [zh-pos/VERB]()-[zh-pos/ADP]() (2; 0% instances), [zh-pos/VERB]()-[zh-pos/ADV]() (2; 0% instances), [zh-pos/VERB]()-[zh-pos/AUX]() (2; 0% instances), [zh-pos/ADP]()-[zh-pos/PART]() (1; 0% instances), [zh-pos/ADV]()-[zh-pos/ADJ]() (1; 0% instances), [zh-pos/ADV]()-[zh-pos/NOUN]() (1; 0% instances), [zh-pos/NOUN]()-[zh-pos/ADJ]() (1; 0% instances), [zh-pos/PRON]()-[zh-pos/ADJ]() (1; 0% instances), [zh-pos/PROPN]()-[zh-pos/VERB]() (1; 0% instances), [zh-pos/PUNCT]()-[zh-pos/NOUN]() (1; 0% instances), [zh-pos/PUNCT]()-[zh-pos/VERB]() (1; 0% instances), [zh-pos/VERB]()-[zh-pos/X]() (1; 0% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 6 ccomp	color:blue
1	這種	這種	DET	DT	_	2	det	_	SpaceAfter=No
2	車輛	車輛	NOUN	NN	_	10	nsubj	_	SpaceAfter=No
3	如果	如果	ADP	IN	_	4	case	_	SpaceAfter=No
4	歸	歸	VERB	VV	_	10	xcomp	_	SpaceAfter=No
5	私人	私人	NOUN	NN	_	6	nsubj	_	SpaceAfter=No
6	擁有	擁有	VERB	VV	_	4	ccomp	_	SpaceAfter=No
7	,	,	PUNCT	,	_	10	punct	_	SpaceAfter=No
8	多半	多半	ADV	RB	_	10	advmod	_	SpaceAfter=No
9	會	會	AUX	MD	_	10	aux	_	SpaceAfter=No
10	設置	設置	VERB	VV	_	0	root	_	SpaceAfter=No
11	昂貴	昂貴	ADJ	JJ	_	14	amod	_	SpaceAfter=No
12	的	的	PART	DEC	_	11	mark:relcl	_	SpaceAfter=No
13	音頻	音頻	NOUN	NN	_	14	nmod	_	SpaceAfter=No
14	設備	設備	NOUN	NN	_	10	obj	_	SpaceAfter=No
15	、	、	PUNCT	EC	_	17	punct	_	SpaceAfter=No
16	電視	電視	NOUN	NN	_	17	case:suff	_	SpaceAfter=No
17	機	機	PART	SFN	_	14	conj	_	SpaceAfter=No
18	、	、	PUNCT	EC	_	20	punct	_	SpaceAfter=No
19	影碟	影碟	NOUN	NN	_	20	case:suff	_	SpaceAfter=No
20	機	機	PART	SFN	_	14	conj	_	SpaceAfter=No
21	,	,	PUNCT	,	_	23	punct	_	SpaceAfter=No
22	以及	以及	CCONJ	CC	_	23	cc	_	SpaceAfter=No
23	吧台	吧台	NOUN	NN	_	14	conj	_	SpaceAfter=No
24	和	和	CCONJ	CC	_	25	cc	_	SpaceAfter=No
25	冰箱	冰箱	NOUN	NN	_	23	conj	_	SpaceAfter=No
26	.	.	PUNCT	.	_	10	punct	_	SpaceAfter=No

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 8 ccomp	color:blue
1	朝鮮	朝鮮	PROPN	NNP	_	12	nsubj	_	SpaceAfter=No
2	雖然	雖然	ADP	IN	_	3	case	_	SpaceAfter=No
3	認為	認為	VERB	VV	_	12	xcomp	_	SpaceAfter=No
4	渤海	渤海	PROPN	NNP	_	5	case:suff	_	SpaceAfter=No
5	國	國	PART	SFN	_	8	nsubj	_	SpaceAfter=No
6	是	是	AUX	VC	_	8	cop	_	SpaceAfter=No
7	本國	本國	NOUN	NN	_	8	nmod	_	SpaceAfter=No
8	歷史	歷史	NOUN	NN	_	3	ccomp	_	SpaceAfter=No
9	,	,	PUNCT	,	_	12	punct	_	SpaceAfter=No
10	但	但	ADV	RB	_	12	mark	_	SpaceAfter=No
11	不	不	ADV	RB	Polarity=Neg	12	advmod	_	SpaceAfter=No
12	使用	使用	VERB	VV	_	0	root	_	SpaceAfter=No
13	「	「	PUNCT	``	_	15	punct	_	SpaceAfter=No
14	南北國	南北國	NOUN	NN	_	15	nmod	_	SpaceAfter=No
15	時代	時代	NOUN	NN	_	12	obj	_	SpaceAfter=No
16	」	」	PUNCT	''	_	15	punct	_	SpaceAfter=No
17	這	這	DET	DT	_	18	det	_	SpaceAfter=No
18	個	個	NOUN	NNB	_	19	clf	_	SpaceAfter=No
19	詞匯	詞匯	NOUN	NN	_	15	appos	_	SpaceAfter=No
20	.	.	PUNCT	.	_	12	punct	_	SpaceAfter=No

~~~


~~~ conllu
# visual-style 21	bgColor:blue
# visual-style 21	fgColor:white
# visual-style 15	bgColor:blue
# visual-style 15	fgColor:white
# visual-style 15 21 ccomp	color:blue
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


