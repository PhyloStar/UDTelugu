

--------------------------------------------------------------------------------

## Treebank Statistics (UD_English-ESL)

This relation is universal.

1052 nodes (1%) are attached to their parents as `neg`.

1003 instances of `neg` (95%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.34220532319392.

The following 21 pairs of parts of speech are connected with `neg`: [en-pos/VERB]()-[en-pos/PART]() (565; 54% instances), [en-pos/ADJ]()-[en-pos/PART]() (148; 14% instances), [en-pos/VERB]()-[en-pos/ADV]() (93; 9% instances), [en-pos/NOUN]()-[en-pos/PART]() (79; 8% instances), [en-pos/NOUN]()-[en-pos/DET]() (75; 7% instances), [en-pos/ADV]()-[en-pos/PART]() (26; 2% instances), [en-pos/ADV]()-[en-pos/ADV]() (15; 1% instances), [en-pos/ADJ]()-[en-pos/ADV]() (11; 1% instances), [en-pos/NOUN]()-[en-pos/ADV]() (8; 1% instances), [en-pos/PRON]()-[en-pos/PART]() (8; 1% instances), [en-pos/PROPN]()-[en-pos/PART]() (8; 1% instances), [en-pos/AUX]()-[en-pos/PART]() (4; 0% instances), [en-pos/ADV]()-[en-pos/DET]() (2; 0% instances), [en-pos/DET]()-[en-pos/PART]() (2; 0% instances), [en-pos/PROPN]()-[en-pos/ADV]() (2; 0% instances), [en-pos/ADP]()-[en-pos/PART]() (1; 0% instances), [en-pos/NUM]()-[en-pos/ADV]() (1; 0% instances), [en-pos/NUM]()-[en-pos/DET]() (1; 0% instances), [en-pos/NUM]()-[en-pos/PART]() (1; 0% instances), [en-pos/PRON]()-[en-pos/ADV]() (1; 0% instances), [en-pos/VERB]()-[en-pos/DET]() (1; 0% instances).


~~~ conllu
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 12	bgColor:blue
# visual-style 12	fgColor:white
# visual-style 12 13 neg	color:blue
1	_	_	PRON	EX	_	2	expl	_	_
2	_	_	VERB	VBZ	_	0	root	_	_
3	_	_	DET	DT	_	5	det	_	_
4	_	_	ADJ	JJ	_	5	amod	_	_
5	_	_	NOUN	NN	_	2	nsubj	_	_
6	_	_	PART	TO	_	7	mark	_	_
7	_	_	VERB	VB	_	5	acl	_	_
8	_	_	ADV	RB	_	7	advmod	_	_
9	_	_	SCONJ	IN	_	12	mark	_	_
10	_	_	DET	DT	_	11	det	_	_
11	_	_	NOUN	NNS	_	12	nsubj	_	_
12	_	_	VERB	VBP	_	2	advcl	_	_
13	_	_	PART	RB	_	12	neg	_	_
14	_	_	VERB	VB	_	12	xcomp	_	_
15	_	_	PRON	NN	_	14	dobj	_	_
16	_	_	PUNCT	.	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 4 neg	color:blue
1	_	_	DET	PRP$	_	2	nmod:poss	_	_
2	_	_	NOUN	NNS	_	5	nsubj	_	_
3	_	_	VERB	VBD	_	5	cop	_	_
4	_	_	PART	RB	_	5	neg	_	_
5	_	_	ADJ	JJ	_	0	root	_	_
6	_	_	ADV	RB	_	5	advmod	_	_
7	_	_	PART	TO	_	8	mark	_	_
8	_	_	VERB	VB	_	6	xcomp	_	_
9	_	_	DET	PRP$	_	10	nmod:poss	_	_
10	_	_	NOUN	NN	_	8	dobj	_	_
11	_	_	ADP	IN	_	13	case	_	_
12	_	_	NOUN	NN	_	13	compound	_	_
13	_	_	NOUN	NN	_	10	nmod	_	_
14	_	_	PUNCT	,	_	5	punct	_	_
15	_	_	CONJ	CC	_	5	cc	_	_
16	_	_	DET	DT	_	18	det	_	_
17	_	_	NOUN	NN	_	18	compound	_	_
18	_	_	NOUN	NN	_	20	nsubj	_	_
19	_	_	VERB	VBD	_	20	cop	_	_
20	_	_	ADJ	JJ	_	5	conj	_	_
21	_	_	PUNCT	.	_	5	punct	_	_

~~~


~~~ conllu
# visual-style 13	bgColor:blue
# visual-style 13	fgColor:white
# visual-style 14	bgColor:blue
# visual-style 14	fgColor:white
# visual-style 14 13 neg	color:blue
1	_	_	ADV	RB	_	8	advmod	_	_
2	_	_	ADP	IN	_	4	case	_	_
3	_	_	DET	DT	_	4	det	_	_
4	_	_	NOUN	NN	_	8	nmod	_	_
5	_	_	PRON	PRP	_	8	expl	_	_
6	_	_	VERB	VBZ	_	8	cop	_	_
7	_	_	PART	RB	_	8	neg	_	_
8	_	_	VERB	VBN	_	0	root	_	_
9	_	_	PART	TO	_	10	mark	_	_
10	_	_	VERB	VBG	_	8	xcomp	_	_
11	_	_	ADP	IN	_	15	case	_	_
12	_	_	DET	DT	_	15	det	_	_
13	_	_	ADV	RB	_	14	neg	_	_
14	_	_	VERB	VBG	_	15	compound	_	_
15	_	_	NOUN	NN	_	10	nmod	_	_
16	_	_	CONJ	CC	_	15	cc	_	_
17	_	_	ADP	IN	_	19	case	_	_
18	_	_	DET	DT	_	19	det	_	_
19	_	_	NOUN	NN	_	15	conj	_	_
20	_	_	PUNCT	.	_	8	punct	_	_

~~~


