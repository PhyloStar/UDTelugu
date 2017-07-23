

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Chinese)

This relation is universal.
There are 1 language-specific subtypes of `acl`: [acl:relcl]().

4951 nodes (4%) are attached to their parents as `acl`.

3439 instances of `acl` (69%) are right-to-left (child precedes parent).
Average distance between parent and child is 6.32963037770147.

The following 43 pairs of parts of speech are connected with `acl`: [zh-pos/VERB]()-[zh-pos/VERB]() (2912; 59% instances), [zh-pos/NOUN]()-[zh-pos/ADP]() (859; 17% instances), [zh-pos/NOUN]()-[zh-pos/NOUN]() (325; 7% instances), [zh-pos/VERB]()-[zh-pos/NOUN]() (152; 3% instances), [zh-pos/PART]()-[zh-pos/ADP]() (108; 2% instances), [zh-pos/PART]()-[zh-pos/NOUN]() (97; 2% instances), [zh-pos/NOUN]()-[zh-pos/VERB]() (90; 2% instances), [zh-pos/VERB]()-[zh-pos/ADJ]() (90; 2% instances), [zh-pos/PROPN]()-[zh-pos/NOUN]() (85; 2% instances), [zh-pos/VERB]()-[zh-pos/PART]() (40; 1% instances), [zh-pos/PART]()-[zh-pos/VERB]() (35; 1% instances), [zh-pos/PROPN]()-[zh-pos/ADP]() (31; 1% instances), [zh-pos/ADJ]()-[zh-pos/VERB]() (22; 0% instances), [zh-pos/NUM]()-[zh-pos/VERB]() (12; 0% instances), [zh-pos/PRON]()-[zh-pos/ADP]() (9; 0% instances), [zh-pos/VERB]()-[zh-pos/ADP]() (8; 0% instances), [zh-pos/NOUN]()-[zh-pos/NUM]() (7; 0% instances), [zh-pos/X]()-[zh-pos/ADP]() (7; 0% instances), [zh-pos/NUM]()-[zh-pos/ADP]() (6; 0% instances), [zh-pos/VERB]()-[zh-pos/NUM]() (6; 0% instances), [zh-pos/ADJ]()-[zh-pos/ADJ]() (5; 0% instances), [zh-pos/NOUN]()-[zh-pos/ADJ]() (5; 0% instances), [zh-pos/NOUN]()-[zh-pos/PART]() (5; 0% instances), [zh-pos/PART]()-[zh-pos/PART]() (5; 0% instances), [zh-pos/VERB]()-[zh-pos/ADV]() (4; 0% instances), [zh-pos/X]()-[zh-pos/NOUN]() (4; 0% instances), [zh-pos/NUM]()-[zh-pos/NOUN]() (3; 0% instances), [zh-pos/ADJ]()-[zh-pos/NOUN]() (2; 0% instances), [zh-pos/NUM]()-[zh-pos/ADJ]() (2; 0% instances), [zh-pos/PROPN]()-[zh-pos/VERB]() (2; 0% instances), [zh-pos/NOUN]()-[zh-pos/ADV]() (1; 0% instances), [zh-pos/NOUN]()-[zh-pos/DET]() (1; 0% instances), [zh-pos/NOUN]()-[zh-pos/X]() (1; 0% instances), [zh-pos/NUM]()-[zh-pos/PART]() (1; 0% instances), [zh-pos/PART]()-[zh-pos/ADJ]() (1; 0% instances), [zh-pos/PART]()-[zh-pos/X]() (1; 0% instances), [zh-pos/PRON]()-[zh-pos/NOUN]() (1; 0% instances), [zh-pos/PRON]()-[zh-pos/VERB]() (1; 0% instances), [zh-pos/SYM]()-[zh-pos/ADP]() (1; 0% instances), [zh-pos/SYM]()-[zh-pos/NOUN]() (1; 0% instances), [zh-pos/VERB]()-[zh-pos/PROPN]() (1; 0% instances), [zh-pos/VERB]()-[zh-pos/X]() (1; 0% instances), [zh-pos/X]()-[zh-pos/NUM]() (1; 0% instances).


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 7 acl	color:blue
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
# visual-style 14	bgColor:blue
# visual-style 14	fgColor:white
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 13 14 acl	color:blue
1	但是	但是	ADV	RB	_	9	mark	_	SpaceAfter=No
2	迪士尼	迪士尼	PROPN	NNP	_	5	det	_	SpaceAfter=No
3	的	的	PART	DEC	Case=Gen	2	case:dec	_	SpaceAfter=No
4	公主	公主	NOUN	NN	_	5	case:suff	_	SpaceAfter=No
5	們	們	PART	SFN	Number=Plur	9	nsubj	_	SpaceAfter=No
6	不會	不會	AUX	MD	_	9	aux	_	SpaceAfter=No
7	都	都	ADV	RB	_	9	mark	_	SpaceAfter=No
8	太	太	ADV	RB	_	9	advmod	_	SpaceAfter=No
9	侷限	侷限	VERB	VV	_	0	root	_	SpaceAfter=No
10	於	於	VERB	VV	_	9	mark	_	SpaceAfter=No
11	一	一	NUM	CD	NumType=Card	12	nummod	_	SpaceAfter=No
12	個	個	NOUN	NNB	_	13	clf	_	SpaceAfter=No
13	範圍	範圍	NOUN	NN	_	9	obj	_	SpaceAfter=No
14	之內	之內	ADP	IN	_	13	acl	_	SpaceAfter=No
15	了	了	X	UH	_	9	discourse	_	SpaceAfter=No
16	嗎	嗎	X	UH	Mood=Inter	9	discourse	_	SpaceAfter=No
17	?	?	PUNCT	.	_	9	punct	_	SpaceAfter=No

~~~


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 11 acl	color:blue
1	在	在	VERB	VV	_	12	acl	_	SpaceAfter=No
2	平原	平原	NOUN	NN	_	1	obj	_	SpaceAfter=No
3	、	、	PUNCT	EC	_	4	punct	_	SpaceAfter=No
4	塔	塔	NOUN	NN	_	2	conj	_	SpaceAfter=No
5	、	、	PUNCT	EC	_	6	punct	_	SpaceAfter=No
6	洞窟	洞窟	NOUN	NN	_	2	conj	_	SpaceAfter=No
7	、	、	PUNCT	EC	_	8	punct	_	SpaceAfter=No
8	海	海	NOUN	NN	_	2	conj	_	SpaceAfter=No
9	或	或	CCONJ	CC	_	10	cc	_	SpaceAfter=No
10	迷宮	迷宮	NOUN	NN	_	2	conj	_	SpaceAfter=No
11	中	中	NOUN	NN	_	2	acl	_	SpaceAfter=No
12	移動	移動	VERB	VV	_	23	acl	_	SpaceAfter=No
13	時	時	ADP	IN	_	12	mark	_	SpaceAfter=No
14	,	,	PUNCT	,	_	23	punct	_	SpaceAfter=No
15	玩家	玩家	NOUN	NN	_	23	nsubj	_	SpaceAfter=No
16	將	將	ADV	RB	_	23	advmod	_	SpaceAfter=No
17	會	會	AUX	MD	_	23	aux	_	SpaceAfter=No
18	和	和	ADP	IN	_	22	case	_	SpaceAfter=No
19	隨機	隨機	ADV	RB	_	20	advmod	_	SpaceAfter=No
20	遇到	遇到	VERB	VV	_	22	acl:relcl	_	SpaceAfter=No
21	的	的	PART	DEC	_	20	mark:relcl	_	SpaceAfter=No
22	敵人	敵人	NOUN	NN	_	23	obl	_	SpaceAfter=No
23	作戰	作戰	VERB	VV	_	0	root	_	SpaceAfter=No
24	.	.	PUNCT	.	_	23	punct	_	SpaceAfter=No

~~~


