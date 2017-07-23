

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Old_Church_Slavonic)

This relation is a language-specific subtype of [obl]().

65 nodes (0%) are attached to their parents as `obl:agent`.

55 instances of `obl:agent` (85%) are left-to-right (parent precedes child).
Average distance between parent and child is 2.06153846153846.

The following 5 pairs of parts of speech are connected with `obl:agent`: [cu-pos/VERB]()-[cu-pos/NOUN]() (41; 63% instances), [cu-pos/VERB]()-[cu-pos/PRON]() (14; 22% instances), [cu-pos/VERB]()-[cu-pos/ADJ]() (5; 8% instances), [cu-pos/VERB]()-[cu-pos/PROPN]() (3; 5% instances), [cu-pos/VERB]()-[cu-pos/NUM]() (2; 3% instances).


~~~ conllu
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 9 obl:agent	color:blue
1	Се	сь	DET	Pd	Case=Nom|Gender=Neut|Number=Sing	3	det	_	ref=MATT_21.4
2	же	же	ADV	Df	_	4	discourse	_	ref=MATT_21.4
3	вьсе	вьсь	ADJ	Px	Case=Nom|Gender=Neut|Number=Sing	4	nsubj	_	ref=MATT_21.4
4	бꙑстъ	бꙑти	VERB	V-	Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	ref=MATT_21.4
5	да	да	SCONJ	G-	_	6	mark	_	ref=MATT_21.4
6	събѫдетъ	събꙑти	VERB	V-	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	4	advcl	_	ref=MATT_21.4
7	сѧ	себе	AUX	Pk	Case=Acc|Number=Sing|Person=3	6	aux	_	ref=MATT_21.4
8	реченое	рещи	VERB	V-	Case=Nom|Gender=Neut|Number=Sing|Strength=Weak|Tense=Past|VerbForm=Part|Voice=Pass	6	nsubj	_	ref=MATT_21.4
9	п҃ркмъ	пророкъ	NOUN	Nb	Case=Ins|Gender=Masc|Number=Sing	8	obl:agent	_	ref=MATT_21.4
10	г҃лѭщемъ	глаголати	VERB	V-	Case=Ins|Gender=Masc,Neut|Number=Sing|Strength=Strong|Tense=Pres|VerbForm=Part|Voice=Act	9	acl	_	ref=MATT_21.4

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 5 obl:agent	color:blue
1	горе	горѥ	INTJ	I-	_	0	root	_	ref=MATT_26.24
2	же	же	ADV	Df	_	1	discourse	_	ref=MATT_26.24
3	ч҃лвкоу	чловѣкъ	NOUN	Nb	Case=Dat|Gender=Masc|Number=Sing	1	iobj	_	ref=MATT_26.24
4	томоу	тъ	DET	Pd	Case=Dat|Gender=Masc,Neut|Number=Sing	3	det	_	ref=MATT_26.24
5	имьже	иже	PRON	Pr	Case=Ins|Gender=Masc|Number=Sing|PronType=Rel	8	obl:agent	_	ref=MATT_26.24
6	с҃нъ	сꙑнъ#1	NOUN	Nb	Case=Nom|Gender=Masc|Number=Sing	8	nsubj	_	ref=MATT_26.24
7	ч҃скъ	чловѣчьскъ	ADJ	A-	Case=Nom|Degree=Pos|Gender=Masc|Number=Sing|Strength=Weak	6	amod	_	ref=MATT_26.24
8	прѣдастъ	прѣдати	VERB	V-	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	3	acl	_	ref=MATT_26.24
9	сѧ	себе	AUX	Pk	Case=Acc|Number=Sing|Person=3	8	aux	_	ref=MATT_26.24

~~~


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 8 obl:agent	color:blue
1	ꙇ	и	CCONJ	C-	_	3	cc	_	ref=LUKE_4.15
2	тоу	тоу	ADV	Df	_	3	advmod	_	ref=LUKE_4.15
3	оучааше	оучити	VERB	V-	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin|Voice=Act	0	root	_	ref=LUKE_4.15
4	на	на	ADP	R-	_	5	case	_	ref=LUKE_4.15
5	сънъмищихъ	съньмище	NOUN	Nb	Case=Loc|Gender=Neut|Number=Plur	3	obl	_	ref=LUKE_4.15
6	ихъ	и	PRON	Pp	Case=Gen|Gender=Masc|Number=Plur|Person=3|PronType=Prs	5	det	_	ref=LUKE_4.15
7	славимъ	славити	VERB	V-	Case=Nom|Gender=Masc|Number=Sing|Strength=Strong|Tense=Pres|VerbForm=Part|Voice=Pass	3	advcl	_	ref=LUKE_4.15
8	вьсѣми	вьсь	ADJ	Px	Case=Ins|Gender=Masc|Number=Plur	7	obl:agent	_	ref=LUKE_4.15

~~~


