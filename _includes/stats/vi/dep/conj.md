

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Vietnamese)

This relation is universal.

1131 nodes (4%) are attached to their parents as `conj`.

1131 instances of `conj` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 4.50839964633068.

The following 28 pairs of parts of speech are connected with `conj`: [vi-pos/VERB]()-[vi-pos/VERB]() (504; 45% instances), [vi-pos/NOUN]()-[vi-pos/NOUN]() (367; 32% instances), [vi-pos/ADJ]()-[vi-pos/ADJ]() (69; 6% instances), [vi-pos/NOUN]()-[vi-pos/VERB]() (63; 6% instances), [vi-pos/ADJ]()-[vi-pos/VERB]() (30; 3% instances), [vi-pos/NOUN]()-[vi-pos/NUM]() (19; 2% instances), [vi-pos/VERB]()-[vi-pos/ADJ]() (17; 2% instances), [vi-pos/NOUN]()-[vi-pos/SCONJ]() (10; 1% instances), [vi-pos/NOUN]()-[vi-pos/ADJ]() (7; 1% instances), [vi-pos/NUM]()-[vi-pos/NOUN]() (7; 1% instances), [vi-pos/VERB]()-[vi-pos/NOUN]() (7; 1% instances), [vi-pos/NOUN]()-[vi-pos/PROPN]() (5; 0% instances), [vi-pos/NOUN]()-[vi-pos/CCONJ]() (4; 0% instances), [vi-pos/PROPN]()-[vi-pos/VERB]() (3; 0% instances), [vi-pos/ADJ]()-[vi-pos/X]() (2; 0% instances), [vi-pos/CCONJ]()-[vi-pos/X]() (2; 0% instances), [vi-pos/NOUN]()-[vi-pos/X]() (2; 0% instances), [vi-pos/VERB]()-[vi-pos/X]() (2; 0% instances), [vi-pos/X]()-[vi-pos/VERB]() (2; 0% instances), [vi-pos/ADJ]()-[vi-pos/NOUN]() (1; 0% instances), [vi-pos/ADP]()-[vi-pos/ADJ]() (1; 0% instances), [vi-pos/ADP]()-[vi-pos/VERB]() (1; 0% instances), [vi-pos/CCONJ]()-[vi-pos/ADJ]() (1; 0% instances), [vi-pos/CCONJ]()-[vi-pos/VERB]() (1; 0% instances), [vi-pos/INTJ]()-[vi-pos/NOUN]() (1; 0% instances), [vi-pos/PROPN]()-[vi-pos/ADJ]() (1; 0% instances), [vi-pos/PROPN]()-[vi-pos/NOUN]() (1; 0% instances), [vi-pos/PUNCT]()-[vi-pos/VERB]() (1; 0% instances).


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 6 conj	color:blue
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
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 11 conj	color:blue
1	Một	Một	NUM	M	NumType=Card	2	nummod	_	_
2	hôm	hôm	NOUN	N	_	4	obl	_	_
3	tôi	tôi	PROPN	P	_	4	nsubj	_	_
4	biết	biết	VERB	V	_	0	root	_	_
5	có	có	VERB	V	_	4	xcomp	_	_
6	đoàn	đoàn	NOUN	Nc	_	7	compound	_	_
7	tàu	tàu	NOUN	N	_	5	obj	_	_
8	chở	chở	VERB	V	_	7	xcomp	_	_
9	vũ khí	vũ khí	NOUN	N	_	8	obj	_	SpaceAfter=No
10	,	,	PUNCT	,	_	11	punct	_	_
11	xe tăng	xe tăng	NOUN	N	_	9	conj	_	_
12	sang	sang	ADP	E	_	13	case	_	_
13	VN	VN	NOUN	Ny	_	8	obl	_	SpaceAfter=No
14	.	.	PUNCT	.	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 12 conj	color:blue
1	Hải	Hải	NOUN	Np	_	2	nsubj	_	_
2	cho	cho	VERB	V	_	0	root	_	_
3	Tùng	Tùng	NOUN	Np	_	2	obj	_	_
4	thấy	thấy	VERB	V	_	2	iobj	_	_
5	Tùng	Tùng	NOUN	Np	_	9	nsubj	_	_
6	cũng	cũng	X	R	_	9	advmod	_	_
7	là	là	AUX	V	_	9	cop	_	_
8	một	một	NUM	M	NumType=Card	9	nummod	_	_
9	thanh niên	thanh niên	NOUN	N	_	4	ccomp	_	_
10	bản lĩnh	bản lĩnh	ADJ	A	_	9	amod	_	_
11	và	và	SCONJ	CC	_	12	cc	_	_
12	tử tế	tử tế	ADJ	A	_	10	conj	_	SpaceAfter=No
13	.	.	PUNCT	.	_	2	punct	_	_

~~~


