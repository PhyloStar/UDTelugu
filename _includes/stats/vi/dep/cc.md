

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Vietnamese)

This relation is universal.

1224 nodes (4%) are attached to their parents as `cc`.

932 instances of `cc` (76%) are right-to-left (child precedes parent).
Average distance between parent and child is 3.02124183006536.

The following 15 pairs of parts of speech are connected with `cc`: [vi-pos/VERB]()-[vi-pos/CCONJ]() (638; 52% instances), [vi-pos/VERB]()-[vi-pos/SCONJ]() (224; 18% instances), [vi-pos/NOUN]()-[vi-pos/SCONJ]() (112; 9% instances), [vi-pos/NOUN]()-[vi-pos/CCONJ]() (108; 9% instances), [vi-pos/ADJ]()-[vi-pos/CCONJ]() (96; 8% instances), [vi-pos/ADJ]()-[vi-pos/SCONJ]() (32; 3% instances), [vi-pos/PROPN]()-[vi-pos/CCONJ]() (4; 0% instances), [vi-pos/PUNCT]()-[vi-pos/CCONJ]() (2; 0% instances), [vi-pos/X]()-[vi-pos/CCONJ]() (2; 0% instances), [vi-pos/ADP]()-[vi-pos/CCONJ]() (1; 0% instances), [vi-pos/ADP]()-[vi-pos/SCONJ]() (1; 0% instances), [vi-pos/CCONJ]()-[vi-pos/CCONJ]() (1; 0% instances), [vi-pos/NUM]()-[vi-pos/CCONJ]() (1; 0% instances), [vi-pos/PROPN]()-[vi-pos/SCONJ]() (1; 0% instances), [vi-pos/X]()-[vi-pos/SCONJ]() (1; 0% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 1 cc	color:blue
1	Và	Và	CCONJ	C	_	4	cc	_	_
2	tôi	tôi	PROPN	P	_	4	nsubj	_	_
3	được	được	VERB	V	_	4	aux:pass	_	_
4	cử	cử	VERB	V	_	0	root	_	_
5	sang	sang	VERB	V	_	4	xcomp	_	_
6	VN	VN	NOUN	Np	_	4	obj	_	_
7	để	để	ADP	E	_	8	case	_	_
8	giúp	giúp	VERB	V	_	4	mark	_	_
9	người	người	NOUN	N	_	8	obj	_	_
10	VN	VN	NOUN	Ny	_	9	compound	_	_
11	chống	chống	VERB	V	_	8	iobj	_	_
12	phát xít	phát xít	NOUN	N	_	11	obj	_	_
13	Nhật	Nhật	NOUN	Np	_	12	compound	_	SpaceAfter=No
14	.	.	PUNCT	.	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 4 cc	color:blue
1	Tôi	Tôi	PROPN	P	_	3	nsubj	_	_
2	bị	bị	VERB	V	_	3	aux:pass	_	_
3	bắt	bắt	VERB	V	_	0	root	_	_
4	và	và	SCONJ	CC	_	6	cc	_	_
5	tòa án	tòa án	NOUN	N	_	6	nsubj	_	_
6	xử	xử	VERB	V	_	3	conj	_	_
7	5	5	NUM	M	NumType=Card	8	nummod	_	_
8	năm	năm	NOUN	N	_	6	obj	_	_
9	tù đày	tù đày	VERB	V	_	8	xcomp	_	SpaceAfter=No
10	"	"	PUNCT	"	_	3	punct	_	SpaceAfter=No
11	.	.	PUNCT	.	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 8 cc	color:blue
1	có	có	VERB	V	_	5	obl	_	_
2	bữa	bữa	NOUN	N	_	1	obj	_	_
3	mẹ	mẹ	NOUN	N	_	5	nsubj	_	_
4	Tùng	Tùng	NOUN	Np	_	3	compound	_	_
5	mời	mời	VERB	V	_	0	root	_	_
6	cả	cả	PROPN	P	_	7	det	_	_
7	thầy giáo	thầy giáo	NOUN	N	_	5	obj	_	_
8	và	và	SCONJ	CC	_	7	cc	_	_
9	hai	hai	NUM	M	NumType=Card	7	nummod	_	_
10	thằng	thằng	PROPN	P	_	9	det	_	_
11	cùng	cùng	ADJ	A	_	5	iobj	_	_
12	ăn	ăn	VERB	V	_	11	xcomp	_	_
13	tối	tối	NOUN	N	_	11	obj	_	SpaceAfter=No
14	.	.	PUNCT	.	_	5	punct	_	_

~~~


