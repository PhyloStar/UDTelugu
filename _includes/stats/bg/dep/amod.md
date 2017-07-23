

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Bulgarian)

This relation is universal.

10638 nodes (8%) are attached to their parents as `amod`.

10266 instances of `amod` (97%) are right-to-left (child precedes parent).
Average distance between parent and child is 1.29742432788118.

The following 10 pairs of parts of speech are connected with `amod`: [bg-pos/NOUN]()-[bg-pos/ADJ]() (10353; 97% instances), [bg-pos/PROPN]()-[bg-pos/ADJ]() (262; 2% instances), [bg-pos/NUM]()-[bg-pos/ADJ]() (6; 0% instances), [bg-pos/PRON]()-[bg-pos/ADJ]() (6; 0% instances), [bg-pos/VERB]()-[bg-pos/ADJ]() (6; 0% instances), [bg-pos/ADJ]()-[bg-pos/ADJ]() (1; 0% instances), [bg-pos/DET]()-[bg-pos/ADJ]() (1; 0% instances), [bg-pos/NOUN]()-[bg-pos/ADV]() (1; 0% instances), [bg-pos/NOUN]()-[bg-pos/PROPN]() (1; 0% instances), [bg-pos/PROPN]()-[bg-pos/PROPN]() (1; 0% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 1 amod	color:blue
1	Огрените	огрея	ADJ	Vpptcv--p-d	Aspect=Perf|Definite=Def|Degree=Pos|Number=Plur|VerbForm=Part|Voice=Pass	2	amod	_	_
2	скали	скала	NOUN	Ncfpi	Definite=Ind|Gender=Fem|Number=Plur	4	nsubj	_	_
3	отсреща	отсреща	ADV	Dl	Degree=Pos	2	advmod	_	_
4	немееха	немея	VERB	Vpiif-m3p	Aspect=Imp|Mood=Ind|Number=Plur|Person=3|Tense=Imp|VerbForm=Fin|Voice=Act	0	root	_	SpaceAfter=No
5	.	.	PUNCT	punct	_	4	punct	_	_

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 2 1 amod	color:blue
1	Синьото	син	ADJ	Ansd	Definite=Def|Degree=Pos|Gender=Neut|Number=Sing	2	amod	_	_
2	БЗНС	бзнс	PROPN	Npnsi	Definite=Ind|Gender=Neut|Number=Sing	5	nsubj	_	_
3	пак	пак	ADV	Dt	Degree=Pos	5	advmod	_	_
4	се	се	PRON	Ppxta	Case=Acc|PronType=Prs|Reflex=Yes	5	expl	_	_
5	цепи	цепя-(се)	VERB	Vpitf-r3s	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	0	root	_	_

~~~


~~~ conllu
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 4 amod	color:blue
1	Но	но	CCONJ	Cc	_	7	cc	_	_
2	ти	аз	PRON	Ppe-os2	Case=Nom|Number=Sing|Person=2|PronType=Prs	7	nsubj	_	SpaceAfter=No
3	,	,	PUNCT	punct	_	4	punct	_	_
4	малкият	малък	ADJ	Amsf	Definite=Def|Degree=Pos|Gender=Masc|Number=Sing	7	amod	_	SpaceAfter=No
5	,	,	PUNCT	punct	_	4	punct	_	_
6	не	не	PART	Tn	Polarity=Neg	7	advmod	_	_
7	мисли	мисля	VERB	Vpitz--2s	Aspect=Imp|Mood=Imp|Number=Sing|Person=2|VerbForm=Fin	0	root	_	SpaceAfter=No
8	,	,	PUNCT	punct	_	12	punct	_	_
9	че	че	SCONJ	Cs	_	12	mark	_	_
10	се	се	PRON	Ppxta	Case=Acc|PronType=Prs|Reflex=Yes	12	expl	_	_
11	е	съм	AUX	Vxitf-r3s	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	12	aux	_	_
12	свършило	свърша-(се)	VERB	Vpptcao-sni	Aspect=Perf|Definite=Ind|Gender=Neut|Number=Sing|Tense=Past|VerbForm=Part|Voice=Act	7	ccomp	_	SpaceAfter=No
13	.	.	PUNCT	punct	_	7	punct	_	_

~~~


