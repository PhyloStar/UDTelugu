

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Chinese)

This relation is a language-specific subtype of [mark]().
There are also 2 other language-specific subtypes of `mark`: [mark:advb](), [mark:relcl]().

23 nodes (0%) are attached to their parents as `mark:comp`.

18 instances of `mark:comp` (78%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.56521739130435.

The following 2 pairs of parts of speech are connected with `mark:comp`: [zh-pos/ADJ]()-[zh-pos/PART]() (18; 78% instances), [zh-pos/VERB]()-[zh-pos/PART]() (5; 22% instances).


~~~ conllu
# visual-style 21	bgColor:blue
# visual-style 21	fgColor:white
# visual-style 22	bgColor:blue
# visual-style 22	fgColor:white
# visual-style 22 21 mark:comp	color:blue
1	北極	北極	PROPN	NNP	_	3	nmod	_	SpaceAfter=No
2	土著	土著	NOUN	NN	_	3	nmod	_	SpaceAfter=No
3	民族	民族	NOUN	NN	_	8	nsubj	_	SpaceAfter=No
4	一直	一直	ADV	RB	_	8	advmod	_	SpaceAfter=No
5	與	與	ADP	IN	_	6	case	_	SpaceAfter=No
6	外界	外界	NOUN	NN	_	8	nmod	_	SpaceAfter=No
7	接觸	接觸	AUX	VV	_	8	cop	_	SpaceAfter=No
8	甚少	甚少	ADJ	JJ	_	19	dep	_	SpaceAfter=No
9	,	,	PUNCT	,	_	19	punct	_	SpaceAfter=No
10	直到	直到	ADP	IN	_	11	case	_	SpaceAfter=No
11	現代	現代	NOUN	NN	_	19	obl	_	SpaceAfter=No
12	,	,	PUNCT	,	_	19	punct	_	SpaceAfter=No
13	與	與	ADP	IN	_	17	det	_	SpaceAfter=No
14	其他	其他	DET	DT	_	15	det	_	SpaceAfter=No
15	地區	地區	NOUN	NN	_	13	nmod	_	SpaceAfter=No
16	的	的	PART	DEC	Case=Gen	13	case:dec	_	SpaceAfter=No
17	交流	交流	NOUN	NN	_	19	nsubj	_	SpaceAfter=No
18	才	才	ADV	RB	_	19	mark	_	SpaceAfter=No
19	開始	開始	VERB	VV	_	0	root	_	SpaceAfter=No
20	變	變	AUX	VV	_	22	cop	_	SpaceAfter=No
21	得	得	PART	DEV	_	22	mark:comp	_	SpaceAfter=No
22	頻繁	頻繁	ADJ	JJ	_	19	xcomp	_	SpaceAfter=No
23	.	.	PUNCT	.	_	19	punct	_	SpaceAfter=No

~~~


~~~ conllu
# visual-style 20	bgColor:blue
# visual-style 20	fgColor:white
# visual-style 19	bgColor:blue
# visual-style 19	fgColor:white
# visual-style 19 20 mark:comp	color:blue
1	司馬	司馬	PROPN	NNP	_	2	nmod	_	SpaceAfter=No
2	遹	遹	PROPN	NNP	_	7	nsubj	_	SpaceAfter=No
3	更	更	ADV	RB	_	7	advmod	_	SpaceAfter=No
4	諷刺	諷刺	VERB	VV	_	7	acl	_	SpaceAfter=No
5	杜	杜	PROPN	NNP	_	6	nmod	_	SpaceAfter=No
6	錫	錫	PROPN	NNP	_	4	obj	_	SpaceAfter=No
7	說	說	VERB	VV	_	0	root	_	SpaceAfter=No
8	:	:	PUNCT	:	_	7	punct	_	SpaceAfter=No
9	「	「	PUNCT	``	_	19	punct	_	SpaceAfter=No
10	你	你	PRON	PRP	Person=2	19	nsubj	_	SpaceAfter=No
11	這麼	這麼	ADV	RB	_	12	advmod	_	SpaceAfter=No
12	喜歡	喜歡	VERB	VV	_	19	acl	_	SpaceAfter=No
13	責怪	責怪	VERB	VV	_	12	xcomp	_	SpaceAfter=No
14	別人	別人	NOUN	NN	_	13	obj	_	SpaceAfter=No
15	,	,	PUNCT	,	_	19	punct	_	SpaceAfter=No
16	為	為	ADP	IN	_	17	case	_	SpaceAfter=No
17	甚麼	甚麼	PRON	WP	_	19	obl	_	SpaceAfter=No
18	會	會	AUX	MD	_	19	aux	_	SpaceAfter=No
19	淪落	淪落	VERB	VV	_	7	ccomp	_	SpaceAfter=No
20	得	得	PART	DEV	_	19	mark:comp	_	SpaceAfter=No
21	如此	如此	VERB	VV	_	22	acl	_	SpaceAfter=No
22	自作自受	自作自受	VERB	VV	_	24	acl:relcl	_	SpaceAfter=No
23	的	的	PART	DEC	_	22	mark:relcl	_	SpaceAfter=No
24	境地	境地	NOUN	NN	_	19	obj	_	SpaceAfter=No
25	啊	啊	X	UH	Mood=Inter	19	discourse	_	SpaceAfter=No
26	?	?	PUNCT	.	_	19	punct	_	SpaceAfter=No
27	」	」	PUNCT	''	_	19	punct	_	SpaceAfter=No

~~~


