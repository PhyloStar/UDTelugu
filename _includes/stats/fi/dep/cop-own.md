

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Finnish)

This relation is a language-specific subtype of [cop]().

307 nodes (0%) are attached to their parents as `cop:own`.

292 instances of `cop:own` (95%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.49837133550489.

The following 5 pairs of parts of speech are connected with `cop:own`: [fi-pos/PRON]()-[fi-pos/AUX]() (197; 64% instances), [fi-pos/NOUN]()-[fi-pos/AUX]() (77; 25% instances), [fi-pos/PROPN]()-[fi-pos/AUX]() (26; 8% instances), [fi-pos/ADJ]()-[fi-pos/AUX]() (5; 2% instances), [fi-pos/VERB]()-[fi-pos/AUX]() (2; 1% instances).


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 cop:own	color:blue
1	Lapsina	lapsi	NOUN	N	Case=Ess|Number=Plur	2	obl	_	_
2	meillä	minä	PRON	Pron	Case=Ade|Number=Plur|Person=1|PronType=Prs	0	root	_	_
3	oli	olla	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	2	cop:own	_	_
4	maalla	maa	NOUN	N	Case=Ade|Number=Sing	2	obl	_	_
5	satumetsä	satu#metsä	NOUN	N	Case=Nom|Number=Sing	2	nsubj:cop	_	SpaceAfter=No
6	.	.	PUNCT	Punct	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 3 cop:own	color:blue
1	Kielenopiskelijoilla	kieli#opiskelija	NOUN	N	Case=Ade|Number=Plur	0	root	_	_
2	taas	taas	ADV	Adv	_	1	advmod	_	_
3	on	olla	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	1	cop:own	_	_
4	kaksi	kaksi	NUM	Num	Case=Nom|Number=Sing|NumType=Card	6	nummod	_	_
5	erillistä	erillinen	ADJ	A	Case=Par|Degree=Pos|Number=Sing	6	amod	_	_
6	järjestelmää	järjestelmä	NOUN	N	Case=Par|Number=Sing	1	nsubj:cop	_	SpaceAfter=No
7	.	.	PUNCT	Punct	_	1	punct	_	_

~~~


~~~ conllu
# visual-style 3	bgColor:blue
# visual-style 3	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 3 cop:own	color:blue
1	Herra	herra	NOUN	N	Case=Nom|Number=Sing	2	compound:nn	_	_
2	Rübigillä	Rübig	PROPN	N	Case=Ade|Number=Sing	0	root	_	_
3	on	olla	AUX	V	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	2	cop:own	_	_
4	puheenvuoro	puheen#vuoro	NOUN	N	Case=Nom|Number=Sing	2	nsubj:cop	_	_
5	eiliseen	eilinen	ADJ	A	Case=Ill|Degree=Pos|Number=Sing	6	amod	_	_
6	pöytäkirjaan	pöytä#kirja	NOUN	N	Case=Ill|Number=Sing	7	obl	_	_
7	liittyen	liittyä	VERB	V	Case=Ins|InfForm=2|Number=Sing|VerbForm=Inf|Voice=Act	4	advcl	_	SpaceAfter=No
8	.	.	PUNCT	Punct	_	2	punct	_	_

~~~


