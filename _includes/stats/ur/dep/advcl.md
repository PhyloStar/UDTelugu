

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Urdu)

This relation is universal.

1655 nodes (1%) are attached to their parents as `advcl`.

1306 instances of `advcl` (79%) are right-to-left (child precedes parent).
Average distance between parent and child is 8.92447129909366.

The following 11 pairs of parts of speech are connected with `advcl`: [ur-pos/VERB]()-[ur-pos/VERB]() (1571; 95% instances), [ur-pos/NOUN]()-[ur-pos/VERB]() (39; 2% instances), [ur-pos/ADJ]()-[ur-pos/VERB]() (19; 1% instances), [ur-pos/VERB]()-[ur-pos/PUNCT]() (10; 1% instances), [ur-pos/VERB]()-[ur-pos/AUX]() (6; 0% instances), [ur-pos/VERB]()-[ur-pos/NOUN]() (3; 0% instances), [ur-pos/VERB]()-[ur-pos/PART]() (3; 0% instances), [ur-pos/ADV]()-[ur-pos/VERB]() (1; 0% instances), [ur-pos/NUM]()-[ur-pos/VERB]() (1; 0% instances), [ur-pos/PART]()-[ur-pos/VERB]() (1; 0% instances), [ur-pos/PRON]()-[ur-pos/VERB]() (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 5 advcl	color:blue
1	اگر	اگر	SCONJ	CC	_	5	mark	_	AltTag=SCONJ-CCONJ|ChunkId=CCP|ChunkType=head
2	کاغذات	کاغذ	NOUN	NN	Case=Nom|Gender=Masc|Number=Plur|Person=3	5	obj	_	Vib=0|Tam=0|ChunkId=NP|ChunkType=head
3	مکمل	مکمل	ADJ	JJ	_	5	compound	_	ChunkId=JJP|ChunkType=head
4	نہیں	نہیں	PART	NEG	Polarity=Neg|PronType=Neg	5	advmod	_	ChunkId=VGF|ChunkType=child
5	رہیں	رہ	VERB	VM	Aspect=Perf|Gender=Fem|Number=Plur|VerbForm=Part|Voice=Act	9	advcl	_	Vib=یا|Tam=yA|ChunkId=VGF|ChunkType=head|Stype=declarative
6	تو	تو	SCONJ	CC	_	9	mark	_	AltTag=SCONJ-CCONJ|ChunkId=CCP2|ChunkType=head
7	قانونی	قانونی	ADJ	JJ	Case=Nom	8	amod	_	ChunkId=NP2|ChunkType=child
8	کارروائی	کارروائی	NOUN	NN	Case=Nom|Gender=Fem|Number=Sing|Person=3	9	compound	_	Vib=0|Tam=0|ChunkId=NP2|ChunkType=head
9	کی	کر	VERB	VM	Aspect=Perf|Gender=Fem|Number=Sing|VerbForm=Part|Voice=Act	0	root	_	Vib=یا|Tam=yA|ChunkId=VGF2|ChunkType=head|Stype=declarative
10	جائےگی	جا	AUX	VAUX	Gender=Fem|Mood=Ind|Number=Sing|Tense=Fut|VerbForm=Fin	9	aux	_	SpaceAfter=No|Vib=گا|Tam=gA|ChunkId=VGF2|ChunkType=child
11	۔	۔	PUNCT	SYM	_	9	punct	_	ChunkId=VGF2|ChunkType=child

~~~


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 11 advcl	color:blue
1	میرے	میرے	PRON	PRP	Case=Acc,Dat|PronType=Prs	6	advmod	_	Vib=کو|Tam=ko|ChunkId=NP|ChunkType=head
2	پاس	پاس	ADP	NST	AdpType=Post|Case=Nom	1	case	_	AltTag=ADP-NOUN|ChunkId=NP|ChunkType=child
3	کچھ	کچھ	DET	QF	PronType=Ind	4	det	_	ChunkId=NP2|ChunkType=child
4	صدقہ	صدقہ	NOUN	NN	Case=Acc|Gender=Masc|Number=Sing|Person=3	6	nmod	_	Vib=0|Tam=0|ChunkId=NP2|ChunkType=head
5	کے	کا	ADP	PSP	AdpType=Post|Case=Acc|Gender=Masc|Number=Sing	4	case	_	ChunkId=NP2|ChunkType=child
6	کھجور	کھجور	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing|Person=3	0	root	_	Vib=0|Tam=0|ChunkId=NP3|ChunkType=head
7	تھے	تھا	AUX	VM	Aspect=Imp|Gender=Masc|Number=Plur|VerbForm=Part|Voice=Act	6	cop	_	SpaceAfter=No|AltTag=AUX-VERB|Vib=تھا|Tam=wA|ChunkId=VGF|ChunkType=head|Stype=declarative
8	,	,	PUNCT	SYM	_	7	punct	_	ChunkId=VGF|ChunkType=child
9	جو	جو	PRON	PRP	Case=Nom|Number=Sing|Person=3|PronType=Prs	11	obj	_	Vib=0|Tam=0|ChunkId=NP4|ChunkType=head
10	مےں	مےں	PRON	PRP	Case=Nom|Number=Sing|Person=1	11	nsubj	_	Vib=0|Tam=0|ChunkId=NP5|ChunkType=head
11	لایا	لا	VERB	VM	Aspect=Perf|Gender=Masc|Number=Sing|VerbForm=Part|Voice=Act	6	advcl	_	Vib=یا|Tam=yA|ChunkId=VGF2|ChunkType=head|Stype=declarative
12	ہوں	ہے	AUX	VAUX	Mood=Ind|Number=Sing|Person=1|Tense=Pres|VerbForm=Fin	11	advcl	_	SpaceAfter=No|Vib=ہے|Tam=hE|ChunkId=VGF2|ChunkType=child
13	''	''	PUNCT	SYM	_	11	advcl	_	SpaceAfter=No|ChunkId=VGF2|ChunkType=child
14	۔	۔	PUNCT	SYM	_	11	advcl	_	ChunkId=VGF2|ChunkType=child

~~~


~~~ conllu
# visual-style 15	bgColor:blue
# visual-style 15	fgColor:white
# visual-style 18	bgColor:blue
# visual-style 18	fgColor:white
# visual-style 18 15 advcl	color:blue
1	ان	یہ	PRON	PRP	Case=Acc|Number=Plur|Person=3|PronType=Prs	3	nmod	_	Vib=0|Tam=0|ChunkId=NP|ChunkType=head
2	تمام	تمام	DET	QF	PronType=Ind	3	det	_	ChunkId=NP2|ChunkType=child
3	نقصانات	نقصان	NOUN	NN	Case=Acc|Gender=Masc|Number=Plur|Person=3	5	nmod	_	Vib=0|Tam=0|ChunkId=NP2|ChunkType=head
4	کا	کا	ADP	PSP	AdpType=Post|Case=Nom|Gender=Masc|Number=Sing	3	case	_	ChunkId=NP2|ChunkType=child
5	سدباب	سدباب	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing|Person=3	7	nsubj	_	Vib=0|Tam=0|ChunkId=NP3|ChunkType=head
6	اگر	اگر	SCONJ	CC	_	7	mark	_	ChunkId=CCP|ChunkType=head
7	ممکن	ممکن	ADJ	JJ	_	18	nmod	_	ChunkId=JJP|ChunkType=head
8	ہے	ہے	AUX	VM	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	7	cop	_	AltTag=AUX-VERB|Vib=ہے|Tam=hE|ChunkId=VGF|ChunkType=head|Stype=declarative
9	تو	تو	SCONJ	CC	_	18	mark	_	AltTag=SCONJ-CCONJ|ChunkId=CCP2|ChunkType=head
10	صرف	صرف	PART	RP	_	11	mark	_	ChunkId=NP4|ChunkType=child
11	احکام	حکم	NOUN	NNZ	Case=Nom|Gender=Masc|Number=Sing|Person=3	15	advmod	_	Vib=0|Tam=0|ChunkId=NP4|ChunkType=head
12	الٰہی	الٰہی	NOUN	NNZ	Case=Acc|Gender=Masc|Number=Sing|Person=3	11	nmod	_	Vib=0|Tam=0|ChunkId=NP5|ChunkType=head
13	پر	پر	ADP	PSP	AdpType=Post	11	dislocated	_	ChunkId=FRAGP|ChunkType=head
14	عمل_پیرا	عمل_پیرا	ADJ	JJ	_	15	compound	_	ChunkId=JJP2|ChunkType=head
15	ہو	ہو	VERB	VM	_	18	advcl	_	Vib=0|Tam=0|ChunkId=VGNF|ChunkType=head
16	کر	کر	AUX	VAUX	_	15	aux	_	Vib=0|Tam=0|ChunkId=VGNF|ChunkType=child
17	ہی	ہی	PART	RP	_	16	dep	_	ChunkId=VGNF|ChunkType=child
18	ممکن	ممکن	ADJ	JJ	_	0	root	_	ChunkId=JJP3|ChunkType=head
19	ہے	ہے	AUX	VM	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	18	cop	_	SpaceAfter=No|AltTag=AUX-VERB|Vib=ہے|Tam=hE|ChunkId=VGF2|ChunkType=head|Stype=declarative
20	۔	۔	PUNCT	SYM	_	19	punct	_	ChunkId=VGF2|ChunkType=child

~~~


