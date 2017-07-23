

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Lithuanian)

This relation is universal.
There are 1 language-specific subtypes of `advmod`: [advmod:emph]().

294 nodes (5%) are attached to their parents as `advmod`.

272 instances of `advmod` (93%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.94897959183673.

The following 35 pairs of parts of speech are connected with `advmod`: [lt-pos/VERB]()-[lt-pos/ADV]() (153; 52% instances), [lt-pos/ADJ]()-[lt-pos/ADV]() (35; 12% instances), [lt-pos/NOUN]()-[lt-pos/ADV]() (26; 9% instances), [lt-pos/ADV]()-[lt-pos/ADV]() (13; 4% instances), [lt-pos/NOUN]()-[lt-pos/PART]() (11; 4% instances), [lt-pos/ADV]()-[lt-pos/PART]() (5; 2% instances), [lt-pos/ADJ]()-[lt-pos/PART]() (4; 1% instances), [lt-pos/VERB]()-[lt-pos/ADP]() (4; 1% instances), [lt-pos/DET]()-[lt-pos/ADV]() (3; 1% instances), [lt-pos/DET]()-[lt-pos/PART]() (3; 1% instances), [lt-pos/PRON]()-[lt-pos/ADV]() (3; 1% instances), [lt-pos/PROPN]()-[lt-pos/PART]() (3; 1% instances), [lt-pos/VERB]()-[lt-pos/NOUN]() (3; 1% instances), [lt-pos/VERB]()-[lt-pos/PART]() (3; 1% instances), [lt-pos/NOUN]()-[lt-pos/ADP]() (2; 1% instances), [lt-pos/NOUN]()-[lt-pos/NOUN]() (2; 1% instances), [lt-pos/VERB]()-[lt-pos/PRON]() (2; 1% instances), [lt-pos/VERB]()-[lt-pos/SCONJ]() (2; 1% instances), [lt-pos/ADJ]()-[lt-pos/ADP]() (1; 0% instances), [lt-pos/ADJ]()-[lt-pos/CCONJ]() (1; 0% instances), [lt-pos/ADJ]()-[lt-pos/VERB]() (1; 0% instances), [lt-pos/ADP]()-[lt-pos/ADV]() (1; 0% instances), [lt-pos/ADV]()-[lt-pos/CCONJ]() (1; 0% instances), [lt-pos/AUX]()-[lt-pos/ADV]() (1; 0% instances), [lt-pos/NOUN]()-[lt-pos/ADJ]() (1; 0% instances), [lt-pos/NOUN]()-[lt-pos/CCONJ]() (1; 0% instances), [lt-pos/NOUN]()-[lt-pos/PRON]() (1; 0% instances), [lt-pos/NOUN]()-[lt-pos/SCONJ]() (1; 0% instances), [lt-pos/NUM]()-[lt-pos/ADV]() (1; 0% instances), [lt-pos/PRON]()-[lt-pos/PART]() (1; 0% instances), [lt-pos/PROPN]()-[lt-pos/PRON]() (1; 0% instances), [lt-pos/PROPN]()-[lt-pos/SCONJ]() (1; 0% instances), [lt-pos/VERB]()-[lt-pos/ADJ]() (1; 0% instances), [lt-pos/VERB]()-[lt-pos/CCONJ]() (1; 0% instances), [lt-pos/VERB]()-[lt-pos/X]() (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 5 advmod	color:blue
1	Taip	taip	PART	UH	_	0	root	_	En=so
2	nėra	būti	AUX	VBC	Mood=Ind|Number=Sing|Person=3|Polarity=Neg|Reflex=No|Tense=Pres|VerbForm=Fin|Voice=Act	1	cop	_	En=be|SpaceAfter=No
3	:	:	PUNCT	PUNCT	_	6	punct	_	En=:
4	mes	mes	PRON	PRP	Case=Nom|Number=Plur|Person=1	6	nsubj	_	En=we
5	tik	tik	ADV	RB	Degree=Pos	6	advmod	_	En=only
6	draudžiame	drausti	VERB	VBC	Mood=Ind|Number=Plur|Person=1|Polarity=Pos|Reflex=No|Tense=Pres|VerbForm=Fin|Voice=Act	1	parataxis	_	En=friend
7	drausti	drausti	VERB	VB	Polarity=Pos|Reflex=No|VerbForm=Inf|Voice=Act	6	xcomp	_	En=friend|SpaceAfter=No
8	,	,	PUNCT	PUNCT	_	9	punct	_	En=,
9	draudžiame	drausti	VERB	VBC	Mood=Ind|Number=Plur|Person=1|Polarity=Pos|Reflex=No|Tense=Pres|VerbForm=Fin|Voice=Act	6	conj	_	En=friend
10	prievartauti	prievartauti	VERB	VB	Polarity=Pos|Reflex=No|VerbForm=Inf|Voice=Act	9	xcomp	_	En=coerce|SpaceAfter=No
11	.	.	PUNCT	PUNCT	_	1	punct	_	En=.

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 6 advmod	color:blue
1	Kas	kas	PRON	WP	Case=Nom	3	nsubj	_	En=who
2	mums	mes	PRON	PRP	Case=Dat|Number=Plur|Person=1	3	iobj	_	En=we
3	lieka	likti	VERB	VBC	Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Reflex=No|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	En=remain
4	dabartinėje	dabartinis	ADJ	JJL	Case=Loc|Definite=Ind|Degree=Pos|Gender=Fem|Number=Sing	3	iobj	_	En=current
5	ne	ne	PART	UH	Polarity=Neg	7	advmod	_	En=not
6	itin	itin	ADV	RB	Degree=Pos	7	advmod	_	En=very
7	linksmoje	linksmas	ADJ	JJL	Case=Loc|Definite=Ind|Degree=Pos|Gender=Fem|Number=Sing	8	amod	_	En=bright
8	situacijoje	situacija	NOUN	NN	Case=Loc|Gender=Fem|Number=Sing	3	obl	_	En=situation|SpaceAfter=No
9	?	?	PUNCT	PUNCT	_	3	punct	_	En=?

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 5 2 advmod	color:blue
1	Autorius	autorius	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing	5	nsubj	_	En=author
2	aiškiai	aiškiai	ADV	RB	Degree=Pos	5	advmod	_	En=clearly
3	yra	būti	AUX	VBC	Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Reflex=No|Tense=Pres|VerbForm=Fin|Voice=Act	5	cop	_	En=be
4	Strepsiado	Strepsiadas	PROPN	NNP	Case=Gen|Gender=Masc|Number=Sing	5	nmod	_	En=Strepsiade
5	pusėje	pusė	NOUN	NN	Case=Loc|Gender=Fem|Number=Sing	0	root	_	En=half
6	–	–	PUNCT	PUNCT	_	10	punct	_	En=–
7	taip	taip	ADV	RB	Degree=Pos	10	advmod	_	En=so
8	Sokratui	Sokratas	PROPN	NNP	Case=Dat|Gender=Masc|Number=Sing	10	obj	_	En=Socrates
9	ir	ir	PART	UH	_	10	advmod:emph	_	En=even
10	reikia	reikėti	VERB	VBC	Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Reflex=No|Tense=Pres|VerbForm=Fin|Voice=Act	5	parataxis	_	En=deserve|SpaceAfter=No
11	.	.	PUNCT	PUNCT	_	5	punct	_	En=.

~~~


