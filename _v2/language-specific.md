---
layout: base
title:  'Language-specific subtypes and syntactic features in UD v2'
---

# Language-specific subtypes and features in UD v2

Whereas the morphological annotation layer allows an arbitrary number of features (universal or language-specific) on top of the universal part-of-speech tags, the syntactic annotation is limited to universal syntactic relations and language-specific subtypes of these. (In addition, there is the enhanced representation, which allows additional relations to be added but does not really provide a mechanism for subclassifying basic syntactic relations.) This has led to a situation where subtypes are used to encode a rather heterogeneous set of distinctions with very little consistency across treebanks. Moreover, because only one level of subtyping is allowed, there is a blocking effect such that, if a treebank uses subtypes for one dimension (say, LVC-hood), it cannot encode any other dimension (at least not for one and the same relation). For v2 we therefore propose two changes:

* Subtyping should be restricted to a proper subclassification of syntactic relations 
* Other types of information could instead be expressed as **syntactic features** (yet to be defined)

# Syntactic subtypes

The following (existing) subtypes are plausible candidates for proper syntactic subtypes:

* **acl:relcl** - A relative clause is a special type of [u-dep/acl](), normally with a characteristic syntactic structure (with relativization of a major clause participant).
* **advcl:compar** - A comparative clause is a special type of [u-dep/advcl](), which again has a characteristic syntactic structure (introduced by a marker such as "as" or "than") and furthermore puts syntactic constraints on the matrix clause (a function word such as "as" or "more" that correlates with the marker); other possible subtypes of [u-dep/advcl]() could come from the traditional subclassification of adverbial clauses as conditional, temporal, consecutive, and so on.
* **advmod:tmod** - A temporal modifier is a special type of adverbial modifier; as for adverbial clauses there is a traditional taxonomy that could be used to subclassify [u-dep/advmod]() as referring to time, place, manner, etc.
* **aux:caus**, **aux:q** - These are special types of auxiliary verbs used to form causatives and questions, respectively; this seems to be well in line with the proposal to replace [u-dep/auxpass]() with the subtype **aux:pass** (see proposal on [core dependents](core-dependents.html)).
* **cc:preconj** - Words like "both" and "either" have a special role in coordinated structures, distinct from the one filled by "and" and "or", so it seems appropriate to have a subtype for this relation.
* **compound:lvc**, **compound:prt** - Complex predicates in languages like Persian and particle verbs in Germanic languages are special types of compounds, with characteristic syntactic properties.
* **nmod:agent**, **nmod:poss** - These are pecial types of nominal modifiers used to express the agent of a passive verb and a genitive/possessive modifier, respectively; nominal modifiers can however be subclassified in many ways, so we need to make sure that we have a consistent taxonomy.
* **nsubj:cop** - The subject of a nominal clause (with or without an overt copula verb) is often distinguished from other subjects in language typology; in addition, this subtype is needed for disambiguation when the predicate of a nominal clause is itself a clause.

Finally, if we merge [u-dep/dobj]() and [u-dep/iobj]() to **obj**, it seems natural to subclassify objects into direct (**obj:dir**) and indirect (**obj:ind**) (see proposal on [core dependents](core-dependents.html)).

Here are some examples of subtypes that we think are less suitable, partly because of the blocking effect discussed above:

* **:mwe** - Except for fixed multiword expressions, which should be handled using the [u-dep/mwe]()), the fact that a particular construction is idiomatic and non-compositional is not a syntactic classification and is better handled in a separate annotation layer (or, if nothing else fits, in the MISC column).
* **:part**, **:inf** - Subclassifying clausal complements or modifiers as being participial or infinitival may have syntactic relevance (for example, for the realization of arguments) but is better handled through features on the main predicate.

# Syntactic features

As noted above, the current annotation scheme gives very little opportunity for subclassification at the syntactic level (in contrast to the morphological level, where features can in principle be added ad infinitum). When talking about syntactic features, there seems to be at least two different things one could have in mind:

* **Features of syntactic relations:** If dependency labels were coupled with syntactic features, just as part-of-speech tags are coupled with morphological features, it would be possible to subclassify syntactic relations along more than one dimension at a time (just like, say, a pronoun can be subclassified as being personal, singular, third person **and** feminine). It is not clear how such features could be introduced without a major change to the CoNLL-U format. Nor is it clear how great the need for such features really is.
* **Features of syntactic phrases:** Even in a dependency-based representation, the need arises to classify structures larger than words. A case in point is (main) clause mood. Most languages in the world distinguish (at least) declarative, interrogative, and imperative clauses, something that is currently not reflected in the UD annotation at all but could be useful also from a more practical NLP perspective. The most natural place to put this information is on the main predicate of the clause (normally a verb), but it is clearly not a morphological feature of this word (except perhaps for imperatives). Hence, we would need to make a distinction between features that encode morphological properties of a word and features that capture properties of an entire phrase or clause headed at that word. Note also that the relevant phrase cannot in general be identified with the entire subtree rooted at that word in the basic dependency tree. In principle, such features could just be stored in the FEATS column, perhaps with a special prefix or symbol in the feature name to indicate that they are phrase-level features. However, this would at least be a conceptual change in the interpretation of the CoNLL-U format, where so far there has been a clear division between morphological information (in columns 3-6) and syntactic information (in columns 7-9). Moreover, it would not solve the issue with phrases smaller than complete subtrees. Finally, it is again not clear how great the need for such features really is.

Tentative proposal:

* Features that do not apply primarily to a word in itself but to a phrase headed by the word or to the dependency going into the word can be added to the FEATS field. Such features should have a name that starts with the character "~", which will indicate that they are not morphological features of the word and make sure that they are alphabetically sorted after all the morphological features. Candidates for such features are: 

  * **~Mood** - sentence mood like **Decl**, **Interr** or **Imper**, indicated on the main predicate
  * **~MWEPos** - part-of-speech category of a fixed MWE, indicated on the pseudo-head
  * **~Definite** - definiteness for noun phrases in languages where this is a holistic property of the phrase, indicated on the head noun

