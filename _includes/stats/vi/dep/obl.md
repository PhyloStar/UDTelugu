

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Vietnamese)

This relation is universal.

1023 nodes (3%) are attached to their parents as `obl`.

624 instances of `obl` (61%) are left-to-right (parent precedes child).
Average distance between parent and child is 4.12218963831867.

The following 6 pairs of parts of speech are connected with `obl`: [vi-pos/VERB]()-[vi-pos/NOUN]() (848; 83% instances), [vi-pos/VERB]()-[vi-pos/PROPN]() (73; 7% instances), [vi-pos/VERB]()-[vi-pos/ADP]() (40; 4% instances), [vi-pos/VERB]()-[vi-pos/VERB]() (36; 4% instances), [vi-pos/VERB]()-[vi-pos/ADJ]() (21; 2% instances), [vi-pos/VERB]()-[vi-pos/X]() (5; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 5 obl	color:blue
1	Tôi	Tôi	PROPN	P	_	2	nsubj	_	_
2	sinh	sinh	VERB	V	_	0	root	_	_
3	ra	ra	X	R	_	2	advmod	_	_
4	trong	trong	ADP	E	_	5	case	_	_
5	gia đình	gia đình	NOUN	N	_	2	obl	_	_
6	nghèo	nghèo	ADJ	A	_	5	amod	_	SpaceAfter=No
7	.	.	PUNCT	.	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 10 obl	color:blue
1	mẹ	mẹ	NOUN	N	_	3	nsubj	_	_
2	Tùng	Tùng	NOUN	Np	_	1	compound	_	_
3	chấp nhận	chấp nhận	VERB	V	_	0	root	_	_
4	mặc cả	mặc cả	NOUN	N	_	3	obj	_	_
5	của	của	ADP	E	_	6	case	_	_
6	con trai	con trai	NOUN	N	_	4	nmod	_	_
7	là	là	CCONJ	C	_	3	cc	_	_
8	mua	mua	VERB	V	_	3	obj	_	_
9	cho	cho	ADP	E	_	10	case	_	_
10	nó	nó	PROPN	P	_	8	obl	_	_
11	một	một	NUM	M	NumType=Card	12	nummod	_	_
12	chiếc	chiếc	NOUN	Nc	_	8	obj	_	_
13	@	@	PUNCT	@	_	12	punct	_	SpaceAfter=No
14	.	.	PUNCT	.	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 1 obl	color:blue
1	trong	trong	ADP	E	_	9	obl	_	_
2	thời gian	thời gian	NOUN	N	_	1	nmod	_	_
3	chờ	chờ	VERB	V	_	2	xcomp	_	_
4	mẹ	mẹ	NOUN	N	_	3	obj	_	_
5	sang tên	sang tên	VERB	V	_	3	iobj	_	SpaceAfter=No
6	,	,	PUNCT	,	_	9	punct	_	_
7	Tùng	Tùng	NOUN	Np	_	9	nsubj	_	_
8	vẫn	vẫn	X	R	_	9	advmod	_	_
9	học	học	VERB	V	_	0	root	_	_
10	khá	khá	X	R	_	11	advmod	_	_
11	tử tế	tử tế	ADJ	A	_	9	xcomp	_	SpaceAfter=No
12	.	.	PUNCT	.	_	9	punct	_	_

~~~


