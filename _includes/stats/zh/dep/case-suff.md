

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Chinese)

This relation is a language-specific subtype of [case]().
There are also 3 other language-specific subtypes of `case`: [case:aspect](), [case:dec](), [case:pref]().

4973 nodes (4%) are attached to their parents as `case:suff`.

4972 instances of `case:suff` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.02232053086668.

The following 17 pairs of parts of speech are connected with `case:suff`: [zh-pos/PART]()-[zh-pos/PROPN]() (1779; 36% instances), [zh-pos/PART]()-[zh-pos/NOUN]() (1732; 35% instances), [zh-pos/PART]()-[zh-pos/VERB]() (1115; 22% instances), [zh-pos/PART]()-[zh-pos/ADJ]() (144; 3% instances), [zh-pos/PART]()-[zh-pos/PART]() (127; 3% instances), [zh-pos/PART]()-[zh-pos/X]() (34; 1% instances), [zh-pos/NOUN]()-[zh-pos/NOUN]() (11; 0% instances), [zh-pos/NOUN]()-[zh-pos/PROPN]() (10; 0% instances), [zh-pos/PART]()-[zh-pos/NUM]() (4; 0% instances), [zh-pos/PROPN]()-[zh-pos/PROPN]() (4; 0% instances), [zh-pos/NOUN]()-[zh-pos/NUM]() (3; 0% instances), [zh-pos/NOUN]()-[zh-pos/VERB]() (3; 0% instances), [zh-pos/PART]()-[zh-pos/PRON]() (2; 0% instances), [zh-pos/VERB]()-[zh-pos/NOUN]() (2; 0% instances), [zh-pos/NOUN]()-[zh-pos/ADJ]() (1; 0% instances), [zh-pos/PROPN]()-[zh-pos/NOUN]() (1; 0% instances), [zh-pos/VERB]()-[zh-pos/PART]() (1; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 case:suff	color:blue
1	隨後	隨後	ADV	RB	_	8	advmod	_	SpaceAfter=No
2	愛斯基摩	愛斯基摩	PROPN	NNP	_	3	case:suff	_	SpaceAfter=No
3	人	人	PART	SFN	_	8	nsubj	_	SpaceAfter=No
4	和	和	CCONJ	CC	_	6	cc	_	SpaceAfter=No
5	維京	維京	PROPN	NNP	_	6	case:suff	_	SpaceAfter=No
6	人	人	PART	SFN	_	3	conj	_	SpaceAfter=No
7	相繼	相繼	ADV	RB	_	8	advmod	_	SpaceAfter=No
8	定居	定居	VERB	VV	_	0	root	_	SpaceAfter=No
9	於	於	ADP	IN	_	10	case	_	SpaceAfter=No
10	此	此	PRON	PRD	_	8	obl	_	SpaceAfter=No
11	.	.	PUNCT	.	_	8	punct	_	SpaceAfter=No

~~~


~~~ conllu
# visual-style 16	bgColor:blue
# visual-style 16	fgColor:white
# visual-style 17	bgColor:blue
# visual-style 17	fgColor:white
# visual-style 17 16 case:suff	color:blue
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
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 case:suff	color:blue
1	大	大	ADV	RB	_	2	advmod	_	SpaceAfter=No
2	多數	多數	ADJ	JJ	_	6	det	_	SpaceAfter=No
3	的	的	PART	DEC	Case=Gen	2	case:dec	_	SpaceAfter=No
4	加長	加長	VERB	VV	_	5	case:suff	_	SpaceAfter=No
5	型	型	PART	SFN	_	6	nmod	_	SpaceAfter=No
6	禮車	禮車	NOUN	NN	_	11	nsubj	_	SpaceAfter=No
7	則是	則是	AUX	VC	_	11	cop	_	SpaceAfter=No
8	租車	租車	NOUN	NN	_	9	nmod	_	SpaceAfter=No
9	公司	公司	NOUN	NN	_	11	det	_	SpaceAfter=No
10	的	的	PART	DEC	Case=Gen	9	case:dec	_	SpaceAfter=No
11	財產	財產	NOUN	NN	_	0	root	_	SpaceAfter=No
12	.	.	PUNCT	.	_	11	punct	_	SpaceAfter=No

~~~


