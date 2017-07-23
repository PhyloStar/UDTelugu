

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Urdu)

This relation is universal.

3002 nodes (2%) are attached to their parents as `cc`.

2993 instances of `cc` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 5.80313124583611.

The following 28 pairs of parts of speech are connected with `cc`: [ur-pos/VERB]()-[ur-pos/CCONJ]() (1227; 41% instances), [ur-pos/NOUN]()-[ur-pos/CCONJ]() (1050; 35% instances), [ur-pos/PROPN]()-[ur-pos/CCONJ]() (423; 14% instances), [ur-pos/ADJ]()-[ur-pos/CCONJ]() (159; 5% instances), [ur-pos/PRON]()-[ur-pos/CCONJ]() (24; 1% instances), [ur-pos/NUM]()-[ur-pos/CCONJ]() (17; 1% instances), [ur-pos/VERB]()-[ur-pos/SCONJ]() (17; 1% instances), [ur-pos/NOUN]()-[ur-pos/SCONJ]() (15; 0% instances), [ur-pos/PROPN]()-[ur-pos/SCONJ]() (13; 0% instances), [ur-pos/NOUN]()-[ur-pos/PRON]() (11; 0% instances), [ur-pos/ADV]()-[ur-pos/CCONJ]() (7; 0% instances), [ur-pos/PROPN]()-[ur-pos/NOUN]() (7; 0% instances), [ur-pos/ADJ]()-[ur-pos/ADJ]() (6; 0% instances), [ur-pos/NOUN]()-[ur-pos/NOUN]() (4; 0% instances), [ur-pos/NUM]()-[ur-pos/ADJ]() (3; 0% instances), [ur-pos/NUM]()-[ur-pos/NUM]() (3; 0% instances), [ur-pos/ADJ]()-[ur-pos/SCONJ]() (2; 0% instances), [ur-pos/ADV]()-[ur-pos/ADV]() (2; 0% instances), [ur-pos/DET]()-[ur-pos/CCONJ]() (2; 0% instances), [ur-pos/VERB]()-[ur-pos/VERB]() (2; 0% instances), [ur-pos/ADV]()-[ur-pos/SCONJ]() (1; 0% instances), [ur-pos/DET]()-[ur-pos/DET]() (1; 0% instances), [ur-pos/NOUN]()-[ur-pos/ADJ]() (1; 0% instances), [ur-pos/NOUN]()-[ur-pos/NUM]() (1; 0% instances), [ur-pos/NUM]()-[ur-pos/DET]() (1; 0% instances), [ur-pos/PART]()-[ur-pos/CCONJ]() (1; 0% instances), [ur-pos/PROPN]()-[ur-pos/PROPN]() (1; 0% instances), [ur-pos/VERB]()-[ur-pos/NOUN]() (1; 0% instances).


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 1 cc	color:blue
1	لیکن	لیکن	CCONJ	CC	_	9	cc	_	ChunkId=CCP|ChunkType=head
2	ان	یہ	PRON	PRP	Case=Acc|Number=Plur|Person=3|PronType=Prs	4	nmod	_	Vib=0|Tam=0|ChunkId=NP|ChunkType=head
3	کے	کا	ADP	PSP	AdpType=Post|Case=Acc|Gender=Masc|Number=Sing	2	case	_	ChunkId=NP|ChunkType=child
4	بیان	بیان	NOUN	NN	Case=Acc|Gender=Masc|Number=Sing|Person=3	9	obj	_	Vib=0|Tam=0|ChunkId=NP2|ChunkType=head
5	کو	کو	ADP	PSP	AdpType=Post	4	case	_	ChunkId=NP2|ChunkType=child
6	کوئی	کوئی	PRON	PRP	Case=Nom|Number=Sing|Person=3|PronType=Prs	7	case	_	Vib=0|Tam=0|ChunkId=NP3|ChunkType=child
7	اہمیت	اہمیت	NOUN	NN	Case=Nom|Gender=Fem|Number=Sing|Person=3	9	compound	_	Vib=0|Tam=0|ChunkId=NP3|ChunkType=head
8	نہیں	نہیں	PART	NEG	Polarity=Neg|PronType=Neg	9	advmod	_	ChunkId=VGF|ChunkType=child
9	دی	دے	VERB	VM	Aspect=Perf|Gender=Fem|Number=Sing|VerbForm=Part|Voice=Pass	0	root	_	Vib=یا|Tam=yA|ChunkId=VGF|ChunkType=head|Stype=declarative
10	گئی	جا	AUX	VAUX	Aspect=Perf|Gender=Fem|Number=Sing|Person=3|VerbForm=Part	9	aux	_	SpaceAfter=No|Vib=1یا|Tam=yA1|ChunkId=VGF|ChunkType=child
11	۔	۔	PUNCT	SYM	_	9	punct	_	ChunkId=VGF|ChunkType=child

~~~


~~~ conllu
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 7 6 cc	color:blue
1	پی	پی	PROPN	NNPC	Case=Nom|Gender=Masc|Number=Sing|Person=3	3	compound	_	Vib=0|Tam=0|ChunkId=NP|ChunkType=child
2	اے	اے	PROPN	NNPC	Case=Nom|Gender=Masc|Number=Sing|Person=3	3	compound	_	Vib=0|Tam=0|ChunkId=NP|ChunkType=child
3	سی	سی	PROPN	NNP	Case=Nom|Gender=Masc|Number=Sing|Person=3	12	nsubj	_	Vib=0|Tam=0|ChunkId=NP|ChunkType=head
4	مختلف	مختلف	ADJ	JJ	Case=Acc	5	amod	_	ChunkId=NP2|ChunkType=child
5	محکموں	محکمہ	NOUN	NN	Case=Acc|Gender=Masc|Number=Plur|Person=3	10	nmod	_	Vib=0|Tam=0|ChunkId=NP2|ChunkType=head
6	اور	اور	CCONJ	CC	_	7	cc	_	ChunkId=CCP|ChunkType=head
7	وزارتوں	وزارت	NOUN	NN	Case=Acc|Gender=Masc|Number=Plur|Person=3	5	conj	_	Vib=0|Tam=0|ChunkId=NP3|ChunkType=head
8	کی	کا	ADP	PSP	AdpType=Post|Case=Nom|Gender=Fem|Number=Sing	5	case	_	ChunkId=NP3|ChunkType=child
9	مالیتی	مالیتی	ADJ	JJ	Case=Acc	10	amod	_	ChunkId=NP4|ChunkType=child
10	آڈٹ	آڈٹ	NOUN	NN	Case=Acc|Gender=Masc|Number=Sing|Person=3	12	advmod	_	Vib=0|Tam=0|ChunkId=NP4|ChunkType=head
11	کی	کا	ADP	PSP	AdpType=Post|Case=Nom|Gender=Fem|Number=Sing	10	case	_	ChunkId=NP4|ChunkType=child
12	ذمہ_دار	ذمہ_دار	ADJ	JJ	_	0	root	_	ChunkId=JJP|ChunkType=head
13	ہے	ہے	AUX	VM	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	12	cop	_	SpaceAfter=No|AltTag=AUX-VERB|Vib=ہے|Tam=hE|ChunkId=VGF|ChunkType=head|Stype=declarative
14	۔	۔	PUNCT	SYM	_	13	punct	_	ChunkId=VGF|ChunkType=child

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 2 cc	color:blue
1	شکیل	شکیل	PROPN	NNP	Case=Acc|Gender=Masc|Number=Sing|Person=3	6	nmod	_	Vib=0|Tam=0|ChunkId=NP|ChunkType=head
2	اور	اور	CCONJ	CC	_	4	cc	_	ChunkId=CCP|ChunkType=head
3	پروین	پروین	PROPN	NNPC	Case=Nom|Gender=Fem|Number=Sing|Person=3	4	compound	_	Vib=0|Tam=0|ChunkId=NP2|ChunkType=child
4	بیگم	بیگم	PROPN	NNP	Case=Acc|Gender=Fem|Number=Sing|Person=3	1	conj	_	Vib=0|Tam=0|ChunkId=NP2|ChunkType=head
5	کی	کا	ADP	PSP	AdpType=Post|Case=Nom|Gender=Fem|Number=Sing	1	case	_	ChunkId=NP2|ChunkType=child
6	حالت	حالت	NOUN	NN	Case=Nom|Gender=Fem|Number=Sing|Person=3	7	nsubj	_	Vib=0|Tam=0|ChunkId=NP3|ChunkType=head
7	تشویشناک	تشویشناک	ADJ	JJ	_	0	root	_	ChunkId=JJP|ChunkType=head
8	ہے	ہے	AUX	VM	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	7	cop	_	SpaceAfter=No|AltTag=AUX-VERB|Vib=ہے|Tam=hE|ChunkId=VGF|ChunkType=head|Stype=declarative
9	۔	۔	PUNCT	SYM	_	8	punct	_	ChunkId=VGF|ChunkType=child

~~~


