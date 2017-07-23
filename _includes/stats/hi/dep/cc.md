

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Hindi)

This relation is universal.

5915 nodes (2%) are attached to their parents as `cc`.

5905 instances of `cc` (100%) are right-to-left (child precedes parent).
Average distance between parent and child is 4.89044801352494.

The following 20 pairs of parts of speech are connected with `cc`: [hi-pos/VERB]()-[hi-pos/CCONJ]() (2092; 35% instances), [hi-pos/NOUN]()-[hi-pos/CCONJ]() (2005; 34% instances), [hi-pos/PROPN]()-[hi-pos/CCONJ]() (1327; 22% instances), [hi-pos/ADJ]()-[hi-pos/CCONJ]() (295; 5% instances), [hi-pos/ADJ]()-[hi-pos/ADJ]() (34; 1% instances), [hi-pos/NOUN]()-[hi-pos/PRON]() (29; 0% instances), [hi-pos/PRON]()-[hi-pos/CCONJ]() (26; 0% instances), [hi-pos/NUM]()-[hi-pos/NUM]() (21; 0% instances), [hi-pos/NUM]()-[hi-pos/CCONJ]() (20; 0% instances), [hi-pos/NOUN]()-[hi-pos/PUNCT]() (13; 0% instances), [hi-pos/ADV]()-[hi-pos/CCONJ]() (12; 0% instances), [hi-pos/DET]()-[hi-pos/CCONJ]() (11; 0% instances), [hi-pos/PROPN]()-[hi-pos/PUNCT]() (11; 0% instances), [hi-pos/VERB]()-[hi-pos/PUNCT]() (11; 0% instances), [hi-pos/ADV]()-[hi-pos/NOUN]() (3; 0% instances), [hi-pos/ADJ]()-[hi-pos/PUNCT]() (1; 0% instances), [hi-pos/AUX]()-[hi-pos/CCONJ]() (1; 0% instances), [hi-pos/PART]()-[hi-pos/CCONJ]() (1; 0% instances), [hi-pos/PRON]()-[hi-pos/PRON]() (1; 0% instances), [hi-pos/X]()-[hi-pos/CCONJ]() (1; 0% instances).


~~~ conllu
# visual-style 11	bgColor:blue
# visual-style 11	fgColor:white
# visual-style 14	bgColor:blue
# visual-style 14	fgColor:white
# visual-style 14 11 cc	color:blue
1	अर्धा	अर्धा	NOUN	NN	Case=Nom|Gender=Fem|Number=Sing|Person=3	9	nsubj	_	SpaceAfter=No|Vib=0|Tam=0|ChunkId=NP|ChunkType=head|Translit=ardhā
2	,	COMMA	PUNCT	SYM	_	1	punct	_	ChunkId=NP|ChunkType=child|Translit=,
3	जो	जो	PRON	PRP	Case=Nom|Number=Sing|Person=3|PronType=Prs	4	nsubj	_	Vib=0|Tam=0|ChunkId=NP2|ChunkType=head|Translit=jo
4	चौकोर	चौकोर	NOUN	NN	Case=Nom|Gender=Masc|Number=Sing|Person=3	1	acl:relcl	_	Vib=0|Tam=0|ChunkId=NP3|ChunkType=head|Translit=caukora
5	है	है	AUX	VM	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	4	cop	_	SpaceAfter=No|Vib=है|Tam=hE|ChunkId=VGF|ChunkType=head|Stype=declarative|Translit=hai
6	,	COMMA	PUNCT	SYM	_	5	punct	_	ChunkId=VGF|ChunkType=child|Translit=,
7	अंदर	अंदर	ADV	NST	AdpType=Post|Case=Acc|Gender=Masc|Number=Sing|Person=3	9	advmod	_	AltTag=ADV-NOUN|Vib=0_से|ChunkId=NP4|ChunkType=head|Translit=aṁdara
8	से	से	ADP	PSP	AdpType=Post	7	case	_	ChunkId=NP4|ChunkType=child|Translit=se
9	पोली	पोला	ADJ	JJ	Gender=Fem|Number=Sing	0	root	_	ChunkId=JJP|ChunkType=head|Translit=polī
10	है	है	AUX	VM	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin|Voice=Act	9	cop	_	Vib=है|Tam=hE|ChunkId=VGF2|ChunkType=head|Stype=declarative|Translit=hai
11	और	और	CCONJ	CC	_	14	cc	_	ChunkId=CCP|ChunkType=head|Translit=aura
12	अपेक्षाकृत	अपेक्षाकृत	ADV	RB	_	13	advmod	_	ChunkId=RBP|ChunkType=head|Translit=apekṣākr̥ta
13	नवीन	नवीन	ADJ	JJ	_	14	xcomp	_	ChunkId=JJP2|ChunkType=head|Translit=navīna
14	बनी	बन	VERB	VM	Aspect=Perf|Gender=Fem|Number=Sing|Person=3|VerbForm=Part|Voice=Act	9	conj	_	Vib=या_है|Tam=yA|ChunkId=VGF3|ChunkType=head|Stype=declarative|Translit=banī
15	है	है	AUX	VAUX	Mood=Ind|Number=Sing|Person=3|Tense=Pres|VerbForm=Fin	14	aux	_	Vib=है|Tam=hE|ChunkId=VGF3|ChunkType=child|Translit=hai
16	।	।	PUNCT	SYM	_	9	punct	_	ChunkId=BLK|ChunkType=head|Translit=.

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 7 cc	color:blue
1	इन	यह	DET	DEM	Case=Acc|Number=Plur|Person=3|PronType=Dem	3	det	_	ChunkId=NP|ChunkType=child|Translit=ina
2	सभी	सभी	DET	QF	PronType=Ind	3	det	_	ChunkId=NP|ChunkType=child|Translit=sabhī
3	स्‍थानों	स्थान	NOUN	NN	Case=Acc|Gender=Masc|Number=Plur|Person=3	12	obl	_	Vib=0_पर|Tam=0|ChunkId=NP|ChunkType=head|Translit=sthānoṁ
4	पर	पर	ADP	PSP	AdpType=Post	3	case	_	ChunkId=NP|ChunkType=child|Translit=para
5	इन	यह	DET	DEM	Case=Acc|Number=Plur|Person=3|PronType=Dem	6	det	_	ChunkId=NP2|ChunkType=child|Translit=ina
6	भस्‍मों	भस्म	NOUN	NN	Case=Acc|Gender=Fem|Number=Plur|Person=3	12	obl	_	Vib=0|Tam=0|ChunkId=NP2|ChunkType=head|Translit=bhasmoṁ
7	और	और	CCONJ	CC	_	8	cc	_	ChunkId=CCP|ChunkType=head|Translit=aura
8	अस्‍थियों	अस्थि	NOUN	NN	Case=Acc|Gender=Fem|Number=Plur|Person=3	6	conj	_	Vib=0_के_ऊपर|Tam=0|ChunkId=NP3|ChunkType=head|Translit=asthiyoṁ
9	के	के	ADP	PSP	AdpType=Post	8	case	_	ChunkId=NP3|ChunkType=child|Translit=ke
10	ऊपर	ऊपर	ADP	NST	AdpType=Post|Case=Nom|Gender=Masc|Number=Sing|Person=3	8	case	_	AltTag=ADP-NOUN|ChunkId=NP3|ChunkType=child|Translit=ūpara
11	स्‍तूप	स्‍तूप	NOUN	NN	Case=Nom|Gender=Masc|Number=Plur|Person=3	12	obj	_	Vib=0|Tam=0|ChunkId=NP4|ChunkType=head|Translit=stūpa
12	बनाए	बना	VERB	VM	Aspect=Perf|Gender=Masc|Number=Plur|VerbForm=Part|Voice=Pass	0	root	_	Vib=या_जा+या1|Tam=yA|ChunkId=VGF|ChunkType=head|Stype=declarative|Translit=banāe
13	गए	जा	AUX	VAUX	Aspect=Perf|Gender=Masc|Number=Plur|VerbForm=Part	12	aux:pass	_	Vib=या1|Tam=yA1|ChunkId=VGF|ChunkType=child|Translit=gae
14	।	।	PUNCT	SYM	_	12	punct	_	ChunkId=BLK|ChunkType=head|Translit=.

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 8	bgColor:blue
# visual-style 8	fgColor:white
# visual-style 8 7 cc	color:blue
1	लेकिन	लेकिन	CCONJ	CC	_	11	cc	_	SpaceAfter=No|ChunkId=CCP|ChunkType=head|Translit=lekina
2	,	COMMA	PUNCT	SYM	_	1	punct	_	ChunkId=CCP|ChunkType=child|Translit=,
3	इस	यह	DET	DEM	Case=Acc|Number=Sing|Person=3|PronType=Dem	4	det	_	ChunkId=NP|ChunkType=child|Translit=isa
4	समझौते	समझौता	NOUN	NN	Case=Acc|Gender=Masc|Number=Sing|Person=3	11	obl	_	Vib=0_से|Tam=0|ChunkId=NP|ChunkType=head|Translit=samajhaute
5	से	से	ADP	PSP	AdpType=Post	4	case	_	ChunkId=NP|ChunkType=child|Translit=se
6	राजद	राजद	PROPN	NNP	Case=Acc|Gender=Masc|Number=Sing|Person=3	10	nmod	_	Vib=0|Tam=0|ChunkId=NP2|ChunkType=head|Translit=rājada
7	और	और	CCONJ	CC	_	8	cc	_	ChunkId=CCP2|ChunkType=head|Translit=aura
8	माकपा	माकपा	PROPN	NNP	Case=Acc|Gender=Fem|Number=Sing|Person=3	6	conj	_	Vib=0_का|Tam=0|ChunkId=NP3|ChunkType=head|Translit=mākapā
9	की	का	ADP	PSP	AdpType=Post|Case=Nom|Gender=Fem|Number=Plur	8	case	_	ChunkId=NP3|ChunkType=child|Translit=kī
10	भवें	भौं	NOUN	NN	Case=Nom|Gender=Fem|Number=Plur|Person=3	11	nsubj	_	Vib=0|Tam=0|ChunkId=NP4|ChunkType=head|Translit=bhaveṁ
11	तन	तन	VERB	VM	Gender=Fem|Number=Plur|Person=3|Voice=Act	0	root	_	Vib=0_जा+या१_है|Tam=0|ChunkId=VGF|ChunkType=head|Stype=declarative|Translit=tana
12	गई	जा	AUX	VAUX	Aspect=Perf|Gender=Fem|Number=Plur|VerbForm=Part	11	aux	_	Vib=या१|Tam=yA1|ChunkId=VGF|ChunkType=child|Translit=gaī
13	हैं	है	AUX	VAUX	Mood=Ind|Number=Plur|Person=3|Tense=Pres|VerbForm=Fin	12	aux:pass	_	Vib=है|Tam=hE|ChunkId=VGF|ChunkType=child|Translit=haiṁ
14	।	।	PUNCT	SYM	_	11	punct	_	ChunkId=BLK|ChunkType=head|Translit=.

~~~


