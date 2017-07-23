---
layout: feature
title: 'VerbForm'
shortdef: 'form of verb or deverbative'
---

Even though the name of the feature seems to suggest that it is used
exclusively with [verbs](ru-pos/VERB), it is not the case.
The `Part` value can be used also with [adjectives](ru-pos/ADJ).
It distinguishes participles from other verb forms,
and participial adjectives from other adjectives.

### `Fin`: finite verb

Rule of thumb: if it has non-empty [Mood](), it is finite.
In Russian this applies to indicative and imperative forms,
and to the special conditional forms of the [auxiliary verb](ru-pos/AUX) _быть_.

#### Examples

- _несу, несёшь, несёт, несём, несёте, несут_ &nbsp;“I carry, you carry, he/she/it carries, we carry, you carry, they carry”
- _неси, несите_ &nbsp;“carry” (imperative in different persons and numbers)
- _буду, будешь, будет, будем, будете, будут_ &nbsp;“I will be, you will be, he/she/it will be, we will be, you will be, they will be”
- _будь, будьте_ &nbsp;“be” (imperative in different persons and numbers)

### `Inf`: infinitive

Infinitive is the citation form of verbs.
It is also used with the auxiliary _быть&nbsp;_ to form periphrastic future tense,
and it appears as the argument of modal and other verbs.

#### Examples

- _нести_ &nbsp;“to carry”
- _быть_ &nbsp;“to be”

### `Part`: participle

Participle is a non-finite verb form that shares properties of verbs
and adjectives. Russian has two types of participles:

- The active past participle 
  is used to form the active voice.
- The passive participle
  is used to form the passive voice.

Participles inflect for [Gender]() and [Number]() but not for [Person]().

#### Examples

- _пишущий, пишущая, пишущее, пишущие_ &nbsp;“writing” 
- _писаный, писаная, писаное, писаные_ &nbsp;“carried” 

### `Trans`: transgressive

The transgressive, also called adverbial participle, is a non-finite
verb form that shares properties of verbs and adverbs.

Imperfective verbs form present transgressive, meaning “while doing”.

Perfective verbs form past transgressive, meaning “having done”.

#### Examples

- _неся;“carrying”)
- _принеся_ &nbsp;“having brought” 

- _они смотреля на меня <b>держа</b> ружья;_ “they
  stared at me <b>while gripping</b> their guns”
- _<b>приготовив</b> обед, она позвала семью к столу;_ “<b>having
  prepared</b> the dinner, she called her family to the table”
