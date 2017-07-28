---
layout: postag
title: 'VERB'
shortdef: 'verb'
---



* Light verbs

"Light verb constructions are verb + noun combi-
nations where most of the semantic content of the
whole expression is carried by the noun while the
syntactic head is the verb"
https://www.aclweb.org/anthology/E/E17/E17-1034.pdf

As it was discussed in the above UD for Hungarian paper, we should add a label lvc (light verb construction) to the dependency relation obj from verb to noun. e.g., In ఖర్చు పెట్టాను, the relation between the two words is: obj:lvc(ఖర్చు,పెట్టాను)

* Serial verbs

Serial verbs are two (or more) verbs coming in a sequence to indicate an activity (e.g., వెళ్ళి వచ్చాను). In these cases, all the verbs must be connected by compound relation, with a label svc (serial verb construction). e.g., in వెళ్ళి వచ్చాను, it is compound:svc(వెళ్ళి,వచ్చాను). Final verb is the head. 

* Negative verbs

లేదు , లేరు , కాదు, కారు, కాడు , లేడు 

* Participles

All participle constructions verbs that behave as adjectives are tagged as VERB but the VerbForm feature is indicated by **Part**
చెప్పటం, రావటం 

* Gerund

All verbal constructions that act as nouns are tagged as VERB but the VerbForm feature is indicated by **Ger**
