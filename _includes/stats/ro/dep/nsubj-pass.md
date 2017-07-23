

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Romanian)

This relation is a language-specific subtype of [nsubj]().

1727 nodes (1%) are attached to their parents as `nsubj:pass`.

1134 instances of `nsubj:pass` (66%) are right-to-left (child precedes parent).
Average distance between parent and child is 4.34163288940359.

The following 12 pairs of parts of speech are connected with `nsubj:pass`: [ro-pos/VERB]()-[ro-pos/NOUN]() (1431; 83% instances), [ro-pos/VERB]()-[ro-pos/PRON]() (155; 9% instances), [ro-pos/VERB]()-[ro-pos/PROPN]() (65; 4% instances), [ro-pos/ADJ]()-[ro-pos/NOUN]() (42; 2% instances), [ro-pos/VERB]()-[ro-pos/NUM]() (10; 1% instances), [ro-pos/VERB]()-[ro-pos/VERB]() (7; 0% instances), [ro-pos/ADJ]()-[ro-pos/PRON]() (6; 0% instances), [ro-pos/VERB]()-[ro-pos/ADJ]() (4; 0% instances), [ro-pos/ADJ]()-[ro-pos/PROPN]() (3; 0% instances), [ro-pos/NOUN]()-[ro-pos/NOUN]() (2; 0% instances), [ro-pos/AUX]()-[ro-pos/NOUN]() (1; 0% instances), [ro-pos/VERB]()-[ro-pos/DET]() (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 5 nsubj:pass	color:blue
1	3	3	NUM	Mc-p-d	Number=Plur|NumForm=Digit|NumType=Card	4	parataxis	_	SpaceAfter=No
2	.	.	PUNCT	PERIOD	_	1	punct	_	_
3	Se	sine	PRON	Px3--a--------w	Case=Acc|Person=3|PronType=Prs|Reflex=Yes|Strength=Weak	4	expl:pass	_	_
4	spală	spăla	VERB	Vmip3	Mood=Ind|Person=3|Tense=Pres|VerbForm=Fin	0	root	_	_
5	plăcile	placă	NOUN	Ncfpry	Case=Acc,Nom|Definite=Def|Gender=Fem|Number=Plur	4	nsubj:pass	_	_
6	de	de	ADP	Spsa	AdpType=Prep|Case=Acc	8	case	_	_
7	trei	trei	NUM	Mc-p-l	Number=Plur|NumForm=Word|NumType=Card	8	nummod	_	_
8	ori	oară	NOUN	Ncfp-n	Definite=Ind|Gender=Fem|Number=Plur	4	nmod:tmod	_	_
9	cu	cu	ADP	Spsa	AdpType=Prep|Case=Acc	10	case	_	_
10	PBS	PBS	PROPN	Np	_	4	obl	_	SpaceAfter=No
11	.	.	PUNCT	PERIOD	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 8 nsubj:pass	color:blue
1	Se	sine	PRON	Px3--a--------w	Case=Acc|Person=3|PronType=Prs|Reflex=Yes|Strength=Weak	2	expl:pv	_	_
2	găseau	găsi	VERB	Vmii3p	Mood=Ind|Number=Plur|Person=3|Tense=Imp|VerbForm=Fin	0	root	_	_
3	întotdeauna	întotdeauna	ADV	Rgp	Degree=Pos	2	advmod	_	_
4	alți	alt	DET	Di3mpr---e	Case=Acc,Nom|Gender=Masc|Number=Plur|Person=3|Position=Prenom|PronType=Ind	7	det	_	_
5	și	și	CCONJ	Crssp	Polarity=Pos	6	cc	_	_
6	alți	alt	DET	Di3mpr---e	Case=Acc,Nom|Gender=Masc|Number=Plur|Person=3|Position=Prenom|PronType=Ind	4	conj	_	_
7	naivi	naiv	NOUN	Ncmp-n	Definite=Ind|Gender=Masc|Number=Plur	2	nsubj	_	_
8	care	care	PRON	Pw3--r	Case=Acc,Nom|Person=3|PronType=Int,Rel	10	nsubj:pass	_	_
9	erau	fi	AUX	Vaii3p	Mood=Ind|Number=Plur|Person=3|Tense=Imp|VerbForm=Fin	10	aux:pass	_	_
10	seduși	seduce	VERB	Vmp--pm	Gender=Masc|Number=Plur|VerbForm=Part	7	acl	_	_
11	de	de	ADP	Spsa	AdpType=Prep|Case=Acc	12	case	_	_
12	el	el	PRON	Pp3msr--------s	Case=Acc,Nom|Gender=Masc|Number=Sing|Person=3|PronType=Prs|Strength=Strong	10	nmod:agent	_	SpaceAfter=No
13	.	.	PUNCT	PERIOD	_	2	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 1 nsubj:pass	color:blue
1	Pink	Pink	PROPN	Np	_	4	nsubj:pass	_	_
2	Floyd	Floyd	PROPN	Np	_	1	flat	_	_
3	fu	fi	AUX	Vais3s	Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	4	aux:pass	_	_
4	sfătuit	sfătui	VERB	Vmp--sm	Gender=Masc|Number=Sing|VerbForm=Part	0	root	_	_
5	discret	discret	ADV	Rgp	Degree=Pos	4	advmod	_	_
6	să	să	PART	Qs	Mood=Sub	8	mark	_	_
7	se	sine	PRON	Px3--a--------w	Case=Acc|Person=3|PronType=Prs|Reflex=Yes|Strength=Weak	8	expl:pv	_	_
8	retragă	retrage	VERB	Vmsp3	Mood=Sub|Person=3|Tense=Pres|VerbForm=Fin	4	ccomp	_	_
9	pentru	pentru	ADP	Spsa	AdpType=Prep|Case=Acc	11	case	_	_
10	acea	acel	DET	Dd3fsr---e	Case=Acc,Nom|Gender=Fem|Number=Sing|Person=3|Position=Prenom|PronType=Dem	11	det	_	_
11	noapte	noapte	NOUN	Ncfsrn	Case=Acc,Nom|Definite=Ind|Gender=Fem|Number=Sing	8	obl	_	SpaceAfter=No
12	.	.	PUNCT	PERIOD	_	4	punct	_	_

~~~


