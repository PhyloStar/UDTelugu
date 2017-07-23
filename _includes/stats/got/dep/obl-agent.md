

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Gothic)

This relation is a language-specific subtype of [obl]().

58 nodes (0%) are attached to their parents as `obl:agent`.

44 instances of `obl:agent` (76%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.51724137931034.

The following 5 pairs of parts of speech are connected with `obl:agent`: [got-pos/VERB]()-[got-pos/NOUN]() (32; 55% instances), [got-pos/VERB]()-[got-pos/PRON]() (15; 26% instances), [got-pos/VERB]()-[got-pos/ADJ]() (5; 9% instances), [got-pos/VERB]()-[got-pos/PROPN]() (5; 9% instances), [got-pos/VERB]()-[got-pos/NUM]() (1; 2% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 3 obl:agent	color:blue
1	raus	raus	NOUN	Nb	Case=Acc|Gender=Neut|Number=Sing	4	obj:dir	_	ref=LUKE_7.24
2	fram	fram	ADP	R-	_	3	case	_	ref=LUKE_7.24
3	winda	winds	NOUN	Nb	Case=Dat|Gender=Masc|Number=Sing	4	obl:agent	_	ref=LUKE_7.24
4	wagid	wagjan	VERB	V-	Aspect=Perf|Case=Acc|Gender=Neut|Number=Sing|Strength=Strong|Tense=Past|VerbForm=Part|Voice=Pass	0	root	_	ref=LUKE_7.24

~~~


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 11 obl:agent	color:blue
1	Atsaiƕiþ	at-saiƕan	VERB	V-	Mood=Imp|Number=Plur|Person=2|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	ref=MATT_6.1
2	armaion	armaio	NOUN	Nb	Case=Acc|Gender=Fem|Number=Sing	5	obj:dir	_	ref=MATT_6.1
3	izwara	jūs	PRON	Pp	Case=Gen|Gender=Fem|Number=Plur|Person=2|PronType=Prs	2	det	_	ref=MATT_6.1
4	ni	ni	ADV	Df	Polarity=Neg	5	advmod	_	ref=MATT_6.1
5	taujan	taujan	VERB	V-	Tense=Pres|VerbForm=Inf|Voice=Act	1	xcomp	_	ref=MATT_6.1
6	in	in	ADP	R-	_	7	case	_	ref=MATT_6.1
7	andwairþja	andwairþi	NOUN	Nb	Case=Dat|Gender=Neut|Number=Sing	5	obl	_	ref=MATT_6.1
8	manne	manna#2	NOUN	Nb	Case=Gen|Gender=Masc|Number=Plur	7	nmod	_	ref=MATT_6.1
9	du	du	ADP	R-	_	10	mark	_	ref=MATT_6.1
10	saiƕan	saiƕan	VERB	V-	Tense=Pres|VerbForm=Inf|Voice=Act	5	advcl	_	ref=MATT_6.1
11	im	is	PRON	Pp	Case=Dat|Gender=Masc|Number=Plur|Person=3|PronType=Prs	10	obl:agent	_	ref=MATT_6.1

~~~


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 9 obl:agent	color:blue
1	jah	jah	CCONJ	C-	_	3	cc	_	ref=LUKE_4.15
2	is	is	PRON	Pp	Case=Nom|Gender=Masc|Number=Sing|Person=3|PronType=Prs	3	nsubj	_	ref=LUKE_4.15
3	laisida	laisjan	VERB	V-	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	ref=LUKE_4.15
4	in	in	ADP	R-	_	5	case	_	ref=LUKE_4.15
5	gaqumþim	gaqumþs	NOUN	Nb	Case=Dat|Gender=Fem|Number=Plur	3	obl	_	ref=LUKE_4.15
6	ize	is	PRON	Pp	Case=Gen|Gender=Masc|Number=Plur|Person=3|PronType=Prs	5	det	_	ref=LUKE_4.15
7	mikilids	mikiljan	VERB	V-	Aspect=Perf|Case=Nom|Gender=Masc|Number=Sing|Strength=Strong|Tense=Past|VerbForm=Part|Voice=Pass	3	advcl	_	ref=LUKE_4.15
8	fram	fram	ADP	R-	_	9	case	_	ref=LUKE_4.15
9	allaim	alls	ADJ	Px	Case=Dat|Gender=Masc|Number=Plur	7	obl:agent	_	ref=LUKE_4.15

~~~


