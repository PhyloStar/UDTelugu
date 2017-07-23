---
layout: base
title:  'Universal Dependencies'
udver: '2'
---

## Introduction

Universal Dependencies (UD) is a project that is developing cross-linguistically consistent treebank
annotation for many languages, with the goal of facilitating multilingual parser development,
cross-lingual learning, and parsing research from a language typology perspective. The annotation
scheme is based on an evolution of (universal) Stanford dependencies (de Marneffe et al., 2006, 2008, 2014), Google
universal part-of-speech tags (Petrov et al., 2012), and the Interset interlingua for
morphosyntactic tagsets (Zeman, 2008). The general philosophy is to provide a universal
inventory of categories and guidelines to facilitate consistent annotation of similar
constructions across languages, while allowing language-specific extensions when necessary.

This is illustrated in the following parallel examples from English, Bulgarian, Czech and Swedish, 
where the main grammatical relations involving a passive verb, a nominal subject and an oblique agent
are the same, but where the concrete grammatical realization varies.

~~~ conllu
# visual-style 4 2 nsubj:pass	color:blue
# visual-style 4 7 obl	color:blue
1	The	the	DET	_	Definite=Def|PronType=Art	2	det	_	_
2	dog	dog	NOUN	_	Gender=Neut|Number=Sing	4	nsubj:pass	_	_
3	was	be	AUX	_	Mood=Ind|Number=Sing|Tense=Past|VerbForm=Fin	4	aux:pass	_	_
4	chased	chase	VERB	_	Tense=Past|VerbForm=Part	0	ROOT	_	_
5	by	by	ADP	_	_	7	case	_	_
6	the	the	DET	_	Definite=Def|PronType=Art	7	det	_	_
7	cat	cat	NOUN	_	Gender=Neut|Number=Sing	4	obl	_	_
8	.	.	PUNCT	_	_	4	punct	_	_

~~~

~~~ conllu
# visual-style 3 1 nsubj:pass	color:blue
# visual-style 3 5 obl	color:blue
1	Кучето	куче	NOUN	_	Definite=Def|Gender=Neut|Number=Sing	3	nsubj:pass	_	_
2	се	се	PRON	_	Case=Acc|PronType=Prs|Reflex=Yes	3	expl:pass	_	_
3	преследваше	преследвам	VERB	_	Aspect=Imp|Mood=Ind|Number=Sing|Person=3|Tense=Past|VerbForm=Fin	0	root	_	_
4	от	от	ADP	_	_	5	case	_	_
5	котката	котка	NOUN	_	Definite=Def|Gender=Fem|Number=Sing	3	obl	_	_
6	.	.	PUNCT	_	_	3	punct	_	_

~~~

~~~ conllu
# visual-style 3 1 nsubj:pass	color:blue
# visual-style 3 4 obl	color:blue
1	Pes	pes	NOUN	_	Animacy=Anim|Case=Nom|Gender=Masc|Number=Sing	3	nsubj:pass	_	_
2	byl	být	AUX	_	Aspect=Imp|Gender=Masc|Number=Sing|Tense=Past|VerbForm=Part|Voice=Act	3	aux:pass	_	_
3	honěn	honit	VERB	_	Aspect=Imp|Gender=Masc|Number=Sing|VerbForm=Part|Voice=Pass	0	root	_	_
4	kočkou	kočka	NOUN	_	Case=Ins|Gender=Fem|Number=Sing	3	obl	_	_
5	.	.	PUNCT	_	_	3	punct	_	_

~~~

~~~ conllu
# visual-style 2 1 nsubj:pass	color:blue
# visual-style 2 4 obl	color:blue
1	Hunden	hund	NOUN	_	Definite=Def	2	nsubj:pass	_	_
2	jagades	jaga	VERB	_	Tense=Past|Voice=Pass	0	root	_	_
3	av	av	ADP	_	_	4	case	_	_
4	katten	katt	NOUN	_	Definite=Def	2	obl	_	_
5	.	.	PUNCT	_	_	2	punct	_	_

~~~


## What is needed for UD to be successful?

The secret to understanding the design and current success of UD is to realize that the design
is a very subtle compromise between approximately 6 things:

1. UD needs to be satisfactory on linguistic analysis grounds for individual languages.
2. UD needs to be good for linguistic typology, i.e., providing a suitable basis for bringing out cross-linguistic parallelism across languages and language families.
3. UD must be suitable for rapid, consistent annotation by a human annotator.
4. UD must be suitable for computer parsing with high accuracy.
5. UD must be easily comprehended and used by a non-linguist, whether a language learner or an engineer with prosaic needs for language processing. We refer to this as seeking a _habitable_ design, and it leads us to favor traditional grammar notions and terminology.
6. UD must support well downstream language understanding tasks (relation extraction, reading comprehension, machine translation, …).

It's easy to come up with a proposal that improves UD on one of these dimensions. The interesting and difficult part is to improve UD while remaining sensitive to all these dimensions.

## History

The Stanford dependencies were originally developed in 2005 as a backend to the Stanford parser
to help in Recognizing Textual Entailment systems,
then eventually emerged as the de facto standard for dependency analysis of English, and have since
been adapted to a number of different languages (Chang et al., 2009, Bosco et al., 2013, Haverinen et al., 2013,
Seraji et al., 2013, Tsarfaty, 2013, Lipenkova and Souček 2014).
The Google universal tag set grew out of the cross-linguistic error analysis based on the
CoNLL-X shared task data by McDonald and Nivre (2007), was initially used for unsupervised
part-of-speech tagging by Das and Petrov (2011), and has since been adopted as a widely used
standard for mapping diverse tagsets to a common standard.
The Interset (Zeman, 2008) started as a tool for conversion between morphosyntactic tagsets of multiple languages.
It dates back to 2006 when it was used in the first experiments with cross-lingual delexicalized parser adaptation
(Zeman and Resnik, 2008). It was later employed as the morphological layer in HamleDT (Zeman et al., 2014) –
a project that brings treebanks of many languages under a common annotation scheme.

The first attempt to combine Stanford dependencies and Google universal tags into a universal
annotation scheme was the Universal Dependency Treebank (UDT) project (McDonald et al., 2013),
which released treebanks for 6 languages in 2013 and 11 languages in 2014, and the first proposal
for incorporating morphology was made by Tsarfaty (2013). The second version of HamleDT (Rosa et al., 2014)
provided Stanford/Google annotation for 30 languages in 2014. This was followed by the development of
universal Stanford dependencies (USD) (de Marneffe et al., 2014).
The new Universal Dependencies is the result of merging all these initiatives into a single coherent framework,
based on universal Stanford dependencies, an extended version of the Google universal tagset, a revised
subset of the Interset feature inventory, and a revised version of the CoNLL-X format (called CoNLL-U).

The first version of the new guidelines, released in October 2014, introduced a somewhat extended universal 
part-of-speech tag set. This set makes some distinctions that were missing in the original proposal, but 
were perceived to be of importance by many, and clarifies the definition of categories. As a result of this work,
universal POS categories have substantive definitions and are not necessarily just equivalence classes
of categories in underlying language-particular treebanks. Hence, work to convert to UD POS tags often
requires context-sensitive rules, or some hand correction. The UD morphological features aim to provide a 
stripped down basic set of features which are most crucial for analysis and are widespread across languages.
The dependency representation of UD evolves out of Stanford Dependencies (SD), which itself follows ideas
of grammatical relations-focused description that can be found in many linguistic frameworks. That is,
it is centrally organized around notions of subject, object, clausal complement, noun determiner, noun modifier, etc.
The goal of the new universal version was to add or refine relations to better accommodate the grammatical structures of typologically different languages and to clean up some of the quirkier and more English-specific features of the original version. Hence, the new taxonomy has _less_ relations than the original SD.

## Project organization

UD is an open collaboration with many project members. The administrative structure is kept at a minimum and currently consists of the following:

* The project is coordinated by Joakim Nivre (aka chief cat herder).
* Releases (including validation and documentation) are managed by Filip Ginter, Sampo Pyysalo and Dan Zeman.
* Universal guidelines are managed by a small group of core members, currently consisting of Marie de Marneffe, Filip Ginter, Yoav Goldberg, Jan Hajič, Chris Manning, Ryan McDonald, Joakim Nivre, Slav Petrov, Sampo Pyysalo, Sebastian Schuster, Natalia Silveira, Reut Tsarfaty, Fran Tyers and Dan Zeman.
* Language-specific guidelines and treebanks are maintained by each specific language team. 
* Issues are raised on GitHub and resolved through discussion and voting. 

[List of contributors](contributors.html)

## UD-related publications

* Cristina Bosco, Simonetta Montemagni, Maria Simi. 2013.
  [Converting Italian treebanks: Towards an Italian Stanford dependency treebank](http://medialab.di.unipi.it/downloads/ISDT/MIDT-STD2013_law.pdf),
  In *7th Linguistic Annotation Workshop and Interoperability with Discourse*.

* Pi-Chuan Chang, Huihsin Tseng, Dan Jurafsky, and Christopher D. Manning. 2009.
  [Discriminative Reordering with Chinese Grammatical Relations Features](http://nlp.stanford.edu/pubs/ssst09-chang.pdf).
  In *Proceedings of the Third Workshop on Syntax and Structure in Statistical Translation*.

* Dipanjan Das, and Slav Petrov. 2011.
  [Unsupervised part-of-speech tagging with bilingual graph-based projections](http://static.googleusercontent.com/media/research.google.com/sv//pubs/archive/37071.pdf)
  In *Proceedings of ACL*.

* Katri Haverinen, Jenna Nyblom, Timo Viljanen, Veronika Laippala, Samuel Kohonen, Anna Missilä, Stina Ojala, Tapio Salakoski, and Filip Ginter. 2013.
  [Building the essential resources for Finnish: the Turku Dependency Treebank](http://dx.doi.org/10.1007/s10579-013-9244-1). Language Resources and Evaluation. Volume 48, Issue 3, pp 493-531.

* Janna Lipenkova and Milan Souček. 2014. [Converting Russian Dependency Treebank to Stanford Typed
Dependencies Representation](http://www.aclweb.org/anthology/E14-4028). In *Proceedings of the 14th Conference of the European Chapter of the Association for Computational Linguistics*, pp. 143-147.

* Marie-Catherine de Marneffe, Miriam Connor, Natalia Silveira, Samuel R. Bowman, Timothy Dozat, and Christopher D. Manning. 2013.
  [More constructions, more genres: extending Stanfod Dependencies](http://anthology.aclweb.org/W/W13/W13-3721.pdf).
  In *Proceedings of the Second International Conference on Dependency Linguistics (DepLing 2013)*.

* Marie-Catherine de Marneffe, Timothy Dozat, Natalia Silveira, Katri
  Haverinen, Filip Ginter, Joakim Nivre, and Christopher D. Manning. 2014.
  [Universal Stanford Dependencies: A cross-linguistic
  typology](http://nlp.stanford.edu/pubs/USD_LREC14_paper_camera_ready.pdf).
  In *Proceedings of LREC*.

* Marie-Catherine de Marneffe, Bill MacCartney, and Christopher D. Manning. 2006.
  [Generating typed dependency parses from phrase structure parses](http://nlp.stanford.edu/pubs/LREC06_dependencies.pdf).
  In *Proceedings of LREC*.

* Marie-Catherine de Marneffe and Christopher D. Manning. 2008.
  [The Stanford typed dependencies representation](http://nlp.stanford.edu/pubs/dependencies-coling08.pdf).
  In *COLING Workshop on Cross-framework and Cross-domain Parser Evaluation*.

* Ryan McDonald, and Joakim Nivre. 2007.
  [Characterizing the errors of data-driven dependency parsing models](http://www.aclweb.org/anthology/D/D07/D07-1013.pdf).
  In *Proceedings of EMNLP-CoNLL*.

* Ryan McDonald, Joakim Nivre, Yvonne Quirmbach-Brundage, Yoav
  Goldberg, Dipanjan Das, Kuzman Ganchev, Keith Hall, Slav Petrov, Hao
  Zhang, Oscar Täckström, Claudia Bedini, Núria Bertomeu Castelló, and
  Jungmee Lee. 2013. [Universal Dependency Annotation for Multilingual
  Parsing](http://ryanmcd.com/papers/treebanksACL2013.pdf).
  In *Proceedings of ACL*.
  ([home page](https://code.google.com/p/uni-dep-tb/))

* Joakim Nivre. 2014. [Universal Dependencies for Swedish](http://www2.lingfil.uu.se/SLTC2014/abstracts/sltc2014_submission_7.pdf).
  In [*SLTC 2014*](http://www2.lingfil.uu.se/SLTC2014/).

* Joakim Nivre. 2015. Towards a Universal Grammar for Natural Language Processing. *Computational Linguistics and Intelligent Text Processing*.

* Joakim Nivre, Marie-Catherine de Marneffe, Filip Ginter, Yoav Goldberg, Jan Hajič, Christopher D. Manning, Ryan McDonald, Slav Petrov, Sampo Pyysalo, Natalia Silveira, Reut Tsarfaty, Daniel Zeman. 2016. [Universal Dependencies v1: A Multilingual Treebank Collection](http://www.lrec-conf.org/proceedings/lrec2016/pdf/348_Paper.pdf). In *Proceedings of LREC*.

* Petya Osenova and Kiril Simov. 2015. Universalizing BulTreeBank: a Linguistic Tale about Glocalization.(http://www.aclweb.org/anthology/W/W15/W15-5313.pdf). In: *Proceedings of BSNLP* 2015, Hissar, Bulgaria, pp. 81–89.

* Slav Petrov, Dipanjan Das, and Ryan McDonald. 2012. [A universal
  part-of-speech tagset](http://www.petrovi.de/data/universal.pdf).
  In *Proceedings of LREC*.
  ([home page](https://code.google.com/p/universal-pos-tags/))

* Sampo Pyysalo, Jenna Kanerva, Anna Missilä, Veronika Laippala, and Filip Ginter. 2015. [Universal Dependencies for Finnish](http://www.aclweb.org/anthology/W/W15/W15-1821.pdf). In *Proceedings of Nodalida 2015*.

* Rudolf Rosa, Jan Mašek, David Mareček, Martin Popel, Daniel Zeman, Zdeněk Žabokrtský. 2014.
  [HamleDT 2.0: Thirty Dependency Treebanks
  Stanfordized](http://www.lrec-conf.org/proceedings/lrec2014/pdf/915_Paper.pdf).
  In *Proceedings of LREC*.
  ([home page](http://ufal.mff.cuni.cz/hamledt))

* Mojgan Seraji, Carina Jahani, Beáta Megyesi, and Joakim Nivre. 2013.
  [A Persian treebank with Stanford typed dependencies](http://www.lrec-conf.org/proceedings/lrec2014/pdf/378_Paper.pdf).
  In *Proceedings of LREC*.

* Pavel Straňák, Jan Štěpánek. 2010.
  [Representing Layered and Structured Data in the CoNLL-ST Format](http://ufal.mff.cuni.cz/biblio/index.jsp?section=publication&id=5199616322962363209&mode=view). In *Proceedings of ICGL 2010*.

* Reut Tsarfaty. 2013.
  [A unified morpho-syntactic scheme of Stanford dependencies](http://www.tsarfaty.com/pdfs/acl13.pdf).
  In *Proceedings of ACL*.

* Daniel Zeman. 2008. [Reusable Tagset Conversion Using Tagset
  Drivers](http://lrec-conf.org/proceedings/lrec2008/pdf/66_paper.pdf).
  In *Proceedings of LREC*.
  ([home page](http://ufal.mff.cuni.cz/interset))

* Daniel Zeman. 2015. [Slavic Languages in Universal Dependencies](http://ufal.mff.cuni.cz/biblio/?section=publication&id=-1745977273001647149&mode=view). In *Slovko 2015: Natural Language Processing, Corpus Linguistics, E-learning*. Bratislava, Slovakia. [PDF](http://ufal.mff.cuni.cz/biblio/servlet/File?timestamp=1441201812368&id=4326707699154676324&field=File)

* Daniel Zeman, Ondřej Dušek, David Mareček, Martin Popel, Loganathan Ramasamy,
  Jan Štěpánek, Zdeněk Žabokrtský, and Jan Hajič. 2014.
  [HamleDT: Harmonized multi-language dependency treebank](http://link.springer.com/article/10.1007/s10579-014-9275-2).
  In *Language Resources and Evaluation,* DOI 10.1007/s10579-014-9275-2.
  (Extended version of [paper from LREC 2012](http://www.lrec-conf.org/proceedings/lrec2012/pdf/429_Paper.pdf).)

* Daniel Zeman, and Philip Resnik. 2008. [Cross-Language Parser Adaptation between Related
  Languages](http://ufal.mff.cuni.cz/~zeman/publikace/2008-01/padapt-hyderabad-05c-postfinal.pdf).
  In *Proceedings of IJCNLP 2008 Workshop on NLP for Less Privileged Languages*
