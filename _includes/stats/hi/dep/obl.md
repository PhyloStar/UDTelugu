

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Hindi)

This relation is universal.

26382 nodes (8%) are attached to their parents as `obl`.

26322 instances of `obl` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 7.5724736562808.

The following 12 pairs of parts of speech are connected with `obl`: [hi-pos/VERB]()-[hi-pos/NOUN]() (15631; 59% instances), [hi-pos/VERB]()-[hi-pos/PROPN]() (5255; 20% instances), [hi-pos/VERB]()-[hi-pos/PRON]() (3497; 13% instances), [hi-pos/VERB]()-[hi-pos/VERB]() (1080; 4% instances), [hi-pos/VERB]()-[hi-pos/ADV]() (802; 3% instances), [hi-pos/VERB]()-[hi-pos/NUM]() (50; 0% instances), [hi-pos/VERB]()-[hi-pos/ADJ]() (29; 0% instances), [hi-pos/VERB]()-[hi-pos/PART]() (19; 0% instances), [hi-pos/VERB]()-[hi-pos/DET]() (14; 0% instances), [hi-pos/AUX]()-[hi-pos/VERB]() (2; 0% instances), [hi-pos/VERB]()-[hi-pos/X]() (2; 0% instances), [hi-pos/VERB]()-[hi-pos/PUNCT]() (1; 0% instances).


~~~ conllu
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 10	bgColor:blue
# visual-style 10	fgColor:white
# visual-style 10 8 obl	color:blue
1	इस	यह	DET	DEM	Case=Acc|Number=Sing|Person=3|PronType=Dem	2	det	_	ChunkId=NP|ChunkType=child|Translit=isa
2	मूर्ति	मूर्ति	NOUN	NN	Case=Acc|Gender=Fem|Number=Sing|Person=3	10	nsubj	_	Vib=0_का|Tam=0|ChunkId=NP|ChunkType=head|Translit=mūrti
3	के	का	ADP	PSP	AdpType=Post|Case=Nom|Gender=Masc|Number=Plur	2	case	_	ChunkId=NP|ChunkType=child|Translit=ke
4	भी	भी	PART	RP	_	2	dep	_	ChunkId=NP|ChunkType=child|Translit=bhī
5	करीब	करीब	PART	RP	_	7	dep	_	ChunkId=NP2|ChunkType=child|Translit=karība
6	पाँच	पाँच	NUM	QCC	NumType=Card	7	dep	_	ChunkId=NP2|ChunkType=child|Translit=pām̃ca
7	सौ	सौ	NUM	QC	NumType=Card	8	nummod	_	ChunkId=NP2|ChunkType=child|Translit=sau
8	वर्ष	वर्ष	NOUN	NN	Case=Nom|Gender=Masc|Number=Plur|Person=3	10	obl	_	Vib=0|Tam=0|ChunkId=NP2|ChunkType=head|Translit=varṣa
9	पुराना	पुराना	ADJ	JJ	Gender=Masc|Number=Sing	10	xcomp	_	ChunkId=JJP|ChunkType=head|Translit=purānā
10	होने	हो	VERB	VM	Case=Acc|Number=Sing|VerbForm=Inf	12	nmod	_	Vib=ना_का|Tam=nA|ChunkId=VGNN|ChunkType=head|Translit=hone
11	का	का	ADP	PSP	AdpType=Post|Case=Nom|Gender=Masc|Number=Sing	10	mark	_	ChunkId=VGNN|ChunkType=child|Translit=kā
12	प्रमाण	प्रमाण	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing|Person=3	13	nsubj	_	Vib=0|Tam=0|ChunkId=NP3|ChunkType=head|Translit=pramāṇa
13	मिलता	मिल	VERB	VM	Aspect=Imp|Gender=Masc|Number=Sing|Person=3|VerbForm=Part|Voice=Act	0	root	_	Vib=ता_है|Tam=wA|ChunkId=VGF|ChunkType=head|Stype=declarative|Translit=milatā
14	है	है	AUX	VAUX	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	13	aux	_	Vib=है|Tam=hE|ChunkId=VGF|ChunkType=child|Translit=hai
15	।	।	PUNCT	SYM	_	13	punct	_	ChunkId=BLK|ChunkType=head|Translit=.

~~~


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 9	bgColor:blue
# visual-style 9	fgColor:white
# visual-style 9 5 obl	color:blue
1	मंदिर	मंदिर	NOUN	NN	Case=Acc|Gender=Masc|Number=Sing|Person=3	3	nmod	_	Vib=0_का|Tam=0|ChunkId=NP|ChunkType=head|Translit=maṁdira
2	का	का	ADP	PSP	AdpType=Post|Case=Nom|Gender=Masc|Number=Sing	1	case	_	ChunkId=NP|ChunkType=child|Translit=kā
3	निर्माण	निर्माण	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing|Person=3	9	compound	_	Vib=0|Tam=0|ChunkId=NP2|ChunkType=head|Translit=nirmāṇa
4	थाईलैंड	थाईलैंड	PROPN	NNPC	Case=Nom|Gender=Masc|Number=Sing|Person=3	5	compound	_	Vib=0|Tam=0|ChunkId=NP3|ChunkType=child|Translit=thāīlaiṁḍa
5	सरकार	सरकार	PROPN	NNP	Case=Acc|Gender=Masc|Number=Sing|Person=3	9	obl	_	Vib=0_के_सौजन्य_से|Tam=0|ChunkId=NP3|ChunkType=head|Translit=sarakāra
6	के	के	ADP	PSP	AdpType=Post|Case=Acc|Gender=Masc	5	case	_	ChunkId=NP3|ChunkType=child|Translit=ke
7	सौजन्‍य	सौजन्य	ADP	PSP	Case=Acc|Gender=Masc	5	case	_	ChunkId=NP3|ChunkType=child|Translit=saujanya
8	से	से	ADP	PSP	AdpType=Post	5	case	_	ChunkId=NP3|ChunkType=child|Translit=se
9	किया	कर	VERB	VM	Aspect=Perf|Gender=Masc|Number=Sing|Person=3|VerbForm=Part|Voice=Pass	0	root	_	Vib=या_जा+या1_है|Tam=yA|ChunkId=VGF|ChunkType=head|Stype=declarative|Translit=kiyā
10	गया	जा	AUX	VAUX	Aspect=Perf|Gender=Masc|Number=Sing|VerbForm=Part	9	aux:pass	_	Vib=या1|Tam=yA1|ChunkId=VGF|ChunkType=child|Translit=gayā
11	है	है	AUX	VAUX	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	10	aux:pass	_	Vib=है|Tam=hE|ChunkId=VGF|ChunkType=child|Translit=hai
12	।	।	PUNCT	SYM	_	9	punct	_	ChunkId=BLK|ChunkType=head|Translit=.

~~~


~~~ conllu
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 1 obl	color:blue
1	यहाँ	यहाँ	PRON	PRP	Case=Acc|PronType=Prs	8	obl	_	Vib=0_पर|ChunkId=NP|ChunkType=head|Translit=yahām̃
2	पर	पर	ADP	PSP	AdpType=Post	1	case	_	ChunkId=NP|ChunkType=child|Translit=para
3	भगवान	भगवान	NOUN	NNC	Case=Nom|Gender=Masc|Number=Sing|Person=3	4	compound	_	Vib=0|Tam=0|ChunkId=NP2|ChunkType=child|Translit=bhagavāna
4	बुद्ध	बुद्ध	PROPN	NNP	Case=Acc|Gender=Masc|Number=Sing|Person=3	7	nmod	_	Vib=0_का|Tam=0|ChunkId=NP2|ChunkType=head|Translit=buddha
5	का	का	ADP	PSP	AdpType=Post|Case=Nom|Gender=Masc|Number=Sing	4	case	_	ChunkId=NP2|ChunkType=child|Translit=kā
6	अंतिम	अंतिम	ADJ	JJ	Case=Nom	7	amod	_	ChunkId=NP3|ChunkType=child|Translit=aṁtima
7	संस्‍कार	संस्कार	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing|Person=3	8	compound	_	Vib=0|Tam=0|ChunkId=NP3|ChunkType=head|Translit=saṁskāra
8	किया	कर	VERB	VM	Aspect=Perf|Gender=Masc|Number=Sing|VerbForm=Part|Voice=Pass	0	root	_	Vib=या_जा+या1_था|Tam=yA|ChunkId=VGF|ChunkType=head|Stype=declarative|Translit=kiyā
9	गया	जा	AUX	VAUX	Aspect=Perf|Gender=Masc|Number=Sing|VerbForm=Part	8	aux:pass	_	Vib=या1|Tam=yA1|ChunkId=VGF|ChunkType=child|Translit=gayā
10	था	था	AUX	VAUX	Gender=Masc|Mood=Ind|Number=Sing|Tense=Past|VerbForm=Fin	9	aux:pass	_	Vib=था|Tam=WA|ChunkId=VGF|ChunkType=child|Translit=thā
11	।	।	PUNCT	SYM	_	8	punct	_	ChunkId=BLK|ChunkType=head|Translit=.

~~~


