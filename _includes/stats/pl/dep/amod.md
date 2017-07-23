

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Polish)

This relation is universal.

5640 nodes (8%) are attached to their parents as `amod`.

3645 instances of `amod` (65%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.21312056737589.

The following 12 pairs of parts of speech are connected with `amod`: [pl-pos/NOUN]()-[pl-pos/ADJ]() (5344; 95% instances), [pl-pos/PROPN]()-[pl-pos/ADJ]() (178; 3% instances), [pl-pos/PRON]()-[pl-pos/ADJ]() (49; 1% instances), [pl-pos/NUM]()-[pl-pos/ADJ]() (26; 0% instances), [pl-pos/NOUN]()-[pl-pos/DET]() (16; 0% instances), [pl-pos/X]()-[pl-pos/ADJ]() (11; 0% instances), [pl-pos/PRON]()-[pl-pos/DET]() (6; 0% instances), [pl-pos/ADP]()-[pl-pos/ADJ]() (3; 0% instances), [pl-pos/PUNCT]()-[pl-pos/ADJ]() (3; 0% instances), [pl-pos/NOUN]()-[pl-pos/NOUN]() (2; 0% instances), [pl-pos/DET]()-[pl-pos/ADJ]() (1; 0% instances), [pl-pos/NUM]()-[pl-pos/DET]() (1; 0% instances).


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 7 amod	color:blue
1	Dorota	Dorota	PROPN	subst:sg:nom:f	Case=Nom|Gender=Fem|Number=Sing	4	nsubj	_	_
2	z	z	ADP	prep:inst:nwok	AdpType=Prep|Case=Ins|Variant=Short	3	case	_	_
3	trudem	trud	NOUN	subst:sg:inst:m3	Animacy=Inan|Case=Ins|Gender=Masc|Number=Sing	4	obl	_	_
4	przepchnęła	przepchnąć	VERB	praet:sg:f:perf	Aspect=Perf|Gender=Fem|Number=Sing|Tense=Past|VerbForm=Part|Voice=Act	0	root	_	_
5	słowa	słowo	NOUN	subst:pl:acc:n	Case=Acc|Gender=Neut|Number=Plur	4	obj	_	_
6	przez	przez	ADP	prep:acc:nwok	AdpType=Prep|Case=Acc|Variant=Short	8	case	_	_
7	zaciśnięte	zaciśnięty	ADJ	ppas:sg:acc:n:perf:aff	Aspect=Perf|Case=Acc|Gender=Neut|Number=Sing|Polarity=Pos|VerbForm=Part|Voice=Pass	8	amod	_	_
8	gardło	gardło	NOUN	subst:sg:acc:n	Case=Acc|Gender=Neut|Number=Sing	4	iobj	_	SpaceAfter=No
9	.	.	PUNCT	interp	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 7 amod	color:blue
1	Projekt	projekt	NOUN	subst:sg:nom:m3	Animacy=Inan|Case=Nom|Gender=Masc|Number=Sing	3	nsubj:pass	_	_
2	został	zostać	AUX	praet:sg:m3:perf	Animacy=Inan|Aspect=Perf|Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part|Voice=Act	3	aux:pass	_	_
3	podpisany	podpisany	ADJ	ppas:sg:nom:m3:perf:aff	Animacy=Inan|Aspect=Perf|Case=Nom|Gender=Masc|Number=Sing|Polarity=Pos|VerbForm=Part|Voice=Pass	0	root	_	_
4	przez	przez	ADP	prep:acc:nwok	AdpType=Prep|Case=Acc|Variant=Short	5	case	_	_
5	cesarza	cesarz	NOUN	subst:sg:acc:m1	Animacy=Hum|Case=Acc|Gender=Masc|Number=Sing	3	obj	_	_
6	Wilhelma	Wilhelm	PROPN	subst:sg:acc:m1	Animacy=Hum|Case=Acc|Gender=Masc|Number=Sing	5	appos	_	_
7	II	II	ADJ	adj:sg:acc:m1:pos	Animacy=Hum|Case=Acc|Degree=Pos|Gender=Masc|Number=Sing	6	amod	_	SpaceAfter=No
8	.	.	PUNCT	interp	_	3	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 amod	color:blue
1	O	o	ADP	prep:loc	AdpType=Prep|Case=Loc	2	case	_	_
2	tym	to	PRON	subst:sg:loc:n	Case=Loc|Gender=Neut|Number=Sing|PronType=Dem	6	obj	_	_
3	poprzednim	poprzedni	ADJ	adj:sg:loc:n:pos	Case=Loc|Degree=Pos|Gender=Neut|Number=Sing	2	amod	_	_
4	wszyscy	wszyscy	PRON	subst:pl:nom:m1	Animacy=Hum|Case=Nom|Gender=Masc|Number=Plur|PronType=Tot	6	nsubj	_	_
5	rychło	rychło	ADV	adv:pos	Degree=Pos	6	advmod	_	_
6	zapominają	zapominać	VERB	fin:pl:ter:imperf	Aspect=Imp|Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	SpaceAfter=No
7	.	.	PUNCT	interp	_	6	punct	_	_

~~~


