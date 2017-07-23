---
layout: postag
title: 'DET'
shortdef: 'determiner'
---

[UD documentation on Determiners](http://universaldependencies.org/u/pos/DET.html) says there are six categories of determiners:

>
    articles (a closed class indicating definiteness, specificity or givenness): a, an, the
    possessive determiners: [cs] můj, tvůj, jeho, její, náš, váš, jejich
    demonstrative determiners: this as in I saw this car yesterday.
    interrogative determiners: which as in “Which car do you like?”
    relative determiners: which as in “I wonder which car you like.”
    quantity determiners (quantifiers): indefinite any, universal: all, and negative no as in “We have no cars available.”

Going by this definition, most of the Telugu pronouns (except the personal and reflexive pronouns) may have to be tagged as determiners. Let us go category by category.

**Articles:** Telugu does not have articles. So no issues.

**Possessive determiners:**
If we take one Telugu noun ఊరు, possible possessive pronouns that come with it can be:
నా ఊరు, నీ ఊరు, మీ ఊరు, మా ఊరు, మన ఊరు, వాళ్ళ ఊరు, వీళ్ళ ఊరు, వీడి ఊరు. ఆమె ఊరు. అతని ఊరు. ఆమె ఊరు. దాని ఊరు

So, all these "pronouns" should be treated as Determiners in UD if they appear as possessives. However, they should be treated as pronouns when they are actually referring to a noun. e.g., "వీడి దగ్గర నా కలం ఉంది." (He has my pen) "వీడి" here is a pronoun, whereas "నా" is still a possessive determiner. 

**Demonstrative Determiners:**
For the same Telugu noun above, two demonstrative pronouns (determiners) are:
ఈ ఊరు, ఆ ఊరు

Other demonstratives such as అది, ఇది, అవి, ఇవి perhaps should be considered pronouns, since they are not typically used as qualifiers for a noun like above, but are used to refer to some noun. 

**Interrogative Determiners:**
ఎవరి ఊరు, ఏ ఊరు, దేని ఊరు

Note: Words such as "ఎవరు" (non-interrogative version of ఎవరి)  should be tagged as Pronouns. 

**Quantity determiners/quantifiers**: 
For the same noun ఊరు, quantity determiners can be: కొన్ని ఊళ్ళు, అన్ని ఊళ్ళు, ఎన్ని ఊళ్ళు, చాలా ఊళ్ళు, బోలెడు ఊళ్ళు, 

For another noun ఉప్పు (salt), quantity determiners can be: కొంచెం ఉప్పు, ఎక్కువ ఉప్పు, తక్కువ ఉప్పు, ఎంత ఉప్పు, అంత ఉప్పు, కొంత ఉప్పు,

Other determiners in this category: 
* అన్నీ in అన్నీ అబద్దాలే. 
* ఏవీ in ఏవీ పుస్తకాలు?

**LIST OF ALL DETERMINERS IN TELUGU**

నా  
నీ  
మీ  
మా  
మన  
వాళ్ళ  
వీళ్ళ  
వీడి  
ఆమె   
అతని  
దాని   





