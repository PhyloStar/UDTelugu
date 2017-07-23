

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Turkish)

This relation is a language-specific subtype of [compound]().
There are also 1 other language-specific subtypes of `compound`: [compound:redup]().

430 nodes (1%) are attached to their parents as `compound:lvc`.

430 instances of `compound:lvc` (100%) are left-to-right (parent precedes child).
Average distance between parent and child is 1.03720930232558.

The following 12 pairs of parts of speech are connected with `compound:lvc`: [tr-pos/NOUN]()-[tr-pos/VERB]() (342; 80% instances), [tr-pos/ADJ]()-[tr-pos/VERB]() (64; 15% instances), [tr-pos/VERB]()-[tr-pos/VERB]() (9; 2% instances), [tr-pos/ADV]()-[tr-pos/VERB]() (3; 1% instances), [tr-pos/NOUN]()-[tr-pos/ADJ]() (3; 1% instances), [tr-pos/ADP]()-[tr-pos/VERB]() (2; 0% instances), [tr-pos/VERB]()-[tr-pos/NOUN]() (2; 0% instances), [tr-pos/ADJ]()-[tr-pos/ADJ]() (1; 0% instances), [tr-pos/ADJ]()-[tr-pos/NOUN]() (1; 0% instances), [tr-pos/NOUN]()-[tr-pos/ADP]() (1; 0% instances), [tr-pos/NOUN]()-[tr-pos/NOUN]() (1; 0% instances), [tr-pos/VERB]()-[tr-pos/ADJ]() (1; 0% instances).


~~~ conllu
# visual-style 5	bgColor:blue
# visual-style 5	fgColor:white
# visual-style 4	bgColor:blue
# visual-style 4	fgColor:white
# visual-style 4 5 compound:lvc	color:blue
1	Kerem	Kerem	PROPN	Prop	Case=Nom|Number=Sing|Person=3	8	nsubj	_	SpaceAfter=No
2	,	,	PUNCT	Punc	_	8	punct	_	_
3	özgürlüğünü	özgürlük	NOUN	Noun	Case=Acc|Number=Sing|Number[psor]=Sing|Person=3|Person[psor]=3	4	obj	_	_
4	teslim	teslim	NOUN	Noun	Case=Nom|Number=Sing|Person=3	8	obl	_	_
5	ettiği	et	VERB	Verb	Aspect=Perf|Case=Nom|Mood=Ind|Number[psor]=Sing|Person[psor]=3|Polarity=Pos|Tense=Past|VerbForm=Part	4	compound:lvc	_	_
6	için	için	ADP	PCNom	_	4	case	_	_
7	sanki	sanki	ADV	Adverb	_	8	advmod	_	_
8	rahatlamıştı	rahatla	VERB	Verb	Aspect=Perf|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Pqp	0	root	_	SpaceAfter=No
9	.	.	PUNCT	Punc	_	8	punct	_	_

~~~


~~~ conllu
# visual-style 7	bgColor:blue
# visual-style 7	fgColor:white
# visual-style 6	bgColor:blue
# visual-style 6	fgColor:white
# visual-style 6 7 compound:lvc	color:blue
1	Sakın	sakın	INTJ	Interj	_	6	discourse	_	_
2	ha	ha	INTJ	Interj	_	6	discourse	_	SpaceAfter=No
3	,	,	PUNCT	Punc	_	6	punct	_	_
4	sana	sen	PRON	Pers	Case=Dat|Number=Sing|Person=2|PronType=Prs	6	obl	_	_
5	da	da	CCONJ	Conj	_	4	advmod:emph	_	_
6	musallat	musallat	ADJ	Adj	_	0	root	_	_
7	olur	ol	VERB	Verb	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Aor	6	compound:lvc	_	SpaceAfter=No
8	.	.	PUNCT	Punc	_	6	punct	_	_

~~~


~~~ conllu
# visual-style 2	bgColor:blue
# visual-style 2	fgColor:white
# visual-style 1	bgColor:blue
# visual-style 1	fgColor:white
# visual-style 1 2 compound:lvc	color:blue
1	İnceleme	incele	VERB	Verb	Aspect=Perf|Case=Nom|Mood=Ind|Polarity=Pos|Tense=Pres|VerbForm=Vnoun	0	root	_	_
2	yapılmış	yap	VERB	Verb	Aspect=Perf|Evident=Nfh|Mood=Ind|Number=Sing|Person=3|Polarity=Pos|Tense=Past|Voice=Pass	1	compound:lvc	_	SpaceAfter=No
3	.	.	PUNCT	Punc	_	1	punct	_	_

~~~


