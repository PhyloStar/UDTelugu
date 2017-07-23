

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Vietnamese)

This relation is universal.

282 nodes (1%) are attached to their parents as `cop`.

282 instances of `cop` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.45035460992908.

The following 7 pairs of parts of speech are connected with `cop`: [vi-pos/NOUN]()-[vi-pos/AUX]() (210; 74% instances), [vi-pos/VERB]()-[vi-pos/AUX]() (38; 13% instances), [vi-pos/PROPN]()-[vi-pos/AUX]() (15; 5% instances), [vi-pos/ADJ]()-[vi-pos/AUX]() (14; 5% instances), [vi-pos/ADJ]()-[vi-pos/CCONJ]() (2; 1% instances), [vi-pos/PUNCT]()-[vi-pos/AUX]() (2; 1% instances), [vi-pos/CCONJ]()-[vi-pos/AUX]() (1; 0% instances).


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 3 2 cop	color:blue
1	Đó	Đó	PROPN	P	_	3	nsubj	_	_
2	là	là	AUX	V	_	3	cop	_	_
3	cuộc	cuộc	NOUN	N	_	0	root	_	_
4	chiến tranh	chiến tranh	NOUN	N	_	3	compound	_	_
5	phi nghĩa	phi nghĩa	ADJ	A	_	3	amod	_	SpaceAfter=No
6	.	.	PUNCT	.	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 cop	color:blue
1	Thọ	Thọ	NOUN	Np	_	2	nsubj	_	_
2	khẳng định	khẳng định	VERB	V	_	0	root	_	_
3	đây	đây	PROPN	P	_	6	nsubj	_	_
4	không thể	không thể	X	R	Polarity=Neg	6	advmod	_	_
5	là	là	AUX	V	_	6	cop	_	_
6	nhầm	nhầm	VERB	V	_	2	ccomp	_	_
7	số	số	NOUN	N	_	6	obj	_	_
8	được	được	X	R	_	6	advmod	_	SpaceAfter=No
9	.	.	PUNCT	.	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 cop	color:blue
1	con người	con người	NOUN	N	_	4	nsubj	_	_
2	này	này	PROPN	P	_	1	det	_	_
3	là	là	AUX	V	_	4	cop	_	_
4	ai	ai	PROPN	P	_	0	root	_	SpaceAfter=No
5	?	?	PUNCT	?	_	4	punct	_	_

~~~


