

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Portuguese-BR)

This relation is a language-specific subtype of [det]().

1556 nodes (1%) are attached to their parents as `det:poss`.

1467 instances of `det:poss` (94%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.13496143958869.

The following 17 pairs of parts of speech are connected with `det:poss`: [pt-pos/NOUN]()-[pt-pos/DET]() (1419; 91% instances), [pt-pos/NOUN]()-[pt-pos/X]() (59; 4% instances), [pt-pos/PROPN]()-[pt-pos/PROPN]() (37; 2% instances), [pt-pos/PROPN]()-[pt-pos/DET]() (18; 1% instances), [pt-pos/PART]()-[pt-pos/DET]() (7; 0% instances), [pt-pos/NOUN]()-[pt-pos/PRON]() (3; 0% instances), [pt-pos/VERB]()-[pt-pos/X]() (3; 0% instances), [pt-pos/ADJ]()-[pt-pos/DET]() (1; 0% instances), [pt-pos/ADP]()-[pt-pos/DET]() (1; 0% instances), [pt-pos/NOUN]()-[pt-pos/PROPN]() (1; 0% instances), [pt-pos/NUM]()-[pt-pos/DET]() (1; 0% instances), [pt-pos/NUM]()-[pt-pos/X]() (1; 0% instances), [pt-pos/PRON]()-[pt-pos/X]() (1; 0% instances), [pt-pos/PROPN]()-[pt-pos/NOUN]() (1; 0% instances), [pt-pos/PROPN]()-[pt-pos/PUNCT]() (1; 0% instances), [pt-pos/VERB]()-[pt-pos/DET]() (1; 0% instances), [pt-pos/X]()-[pt-pos/DET]() (1; 0% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 8 det:poss	color:blue
1	A	_	DET	DET	_	2	det	_	_
2	ideia	_	NOUN	NOUN	_	0	root	_	_
3	é	_	VERB	VERB	_	2	cop	_	_
4	de	_	ADP	ADP	_	7	mark	_	_
5	que	_	CCONJ	CONJ	_	7	mark	_	_
6	todos	_	PRON	PRON	_	7	nsubj	_	_
7	desliguem	_	VERB	VERB	_	2	nmod	_	_
8	seus	_	DET	DET	_	9	det:poss	_	_
9	celulares	_	NOUN	NOUN	_	7	obj	_	SpaceAfter=No
10	.	_	PUNCT	.	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 det:poss	color:blue
1	O	_	DET	DET	_	2	det	_	_
2	depoimento	_	NOUN	NOUN	_	4	nsubj	_	_
3	dela	_	X	ADPPRON	_	2	det:poss	_	_
4	ficou	_	VERB	VERB	_	0	root	_	_
5	para	_	ADP	ADP	_	7	case	_	_
6	outro	_	DET	DET	_	7	det	_	_
7	dia	_	NOUN	NOUN	_	4	nmod	_	SpaceAfter=No
8	.	_	PUNCT	.	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 det:poss	color:blue
1	Festas	_	PROPN	PNOUN	_	0	root	_	_
2	e	_	CCONJ	CONJ	_	3	cc	_	_
3	Romarias	_	PROPN	PNOUN	_	1	conj	_	_
4	--	_	PUNCT	.	_	6	punct	_	_
5	Nossa	_	PROPN	PNOUN	_	6	det:poss	_	_
6	Senhora	_	PROPN	PNOUN	_	1	appos	_	_
7	de	de	ADP	ADP	_	9	case	_	_
8	a	o	DET	DET	Definite=Def|Gender=Fem|Number=Sing|PronType=Art	9	det	_	_
9	Graça	_	PROPN	PNOUN	_	6	nmod	_	_
10	--	_	PUNCT	.	_	6	punct	_	_
11	08	_	NUM	NUM	NumType=Card	6	nmod	_	_
12	de	_	ADP	ADP	_	13	case	_	_
13	Setembro	_	PROPN	PNOUN	_	11	nmod	_	SpaceAfter=No
14	;	_	PUNCT	.	_	1	punct	_	_

~~~


