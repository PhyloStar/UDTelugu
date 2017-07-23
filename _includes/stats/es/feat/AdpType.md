

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Spanish-AnCora)

This feature is language-specific.
It occurs with 2 different values: `Prep`, `Preppron`.

80126 tokens (16%) have a non-empty value of `AdpType`.
115 types (0%) occur at least once with a non-empty value of `AdpType`.
81 lemmas (0%) occur at least once with a non-empty value of `AdpType`.
The feature is used with 3 part-of-speech tags: [es-pos/ADP]() (79717; 16% instances), [es-pos/ADV]() (233; 0% instances), [es-pos/ADJ]() (176; 0% instances).

### `ADP`

79717 [es-pos/ADP]() tokens (100% of all `ADP` tokens) have a non-empty value of `AdpType`.

The most frequent other feature values with which `ADP` and `AdpType` co-occurred: <tt><a href="Number.html">Number</a>=EMPTY</tt> (70004; 88%), <tt><a href="Gender.html">Gender</a>=EMPTY</tt> (70004; 88%).

`ADP` tokens may have the following values of `AdpType`:

* `Prep` (70004; 88% of non-empty `AdpType`): <em>de, en, a, por, con, para, entre, sobre, sin, desde</em>
* `Preppron` (9713; 12% of non-empty `AdpType`): <em>del, al, da, do, dels, als, de, pelo</em>

<table>
  <tr><th>Paradigm <i>de</i></th><th><tt>Prep</tt></th><th><tt>Preppron</tt></th></tr>
  <tr><td><tt>_</tt></td><td><em>de</em></td><td></td></tr>
  <tr><td><tt><a href="Gender.html">Gender</a>=Masc|<a href="Number.html">Number</a>=Sing</tt></td><td></td><td><em>de</em></td></tr>
</table>

`AdpType` seems to be **lexical feature** of `ADP`. 97% lemmas (58) occur only with one value of `AdpType`.

### `ADV`

233 [es-pos/ADV]() tokens (1% of all `ADV` tokens) have a non-empty value of `AdpType`.

The most frequent other feature values with which `ADV` and `AdpType` co-occurred: <tt><a href="Polarity.html">Polarity</a>=EMPTY</tt> (233; 100%).

`ADV` tokens may have the following values of `AdpType`:

* `Prep` (182; 78% of non-empty `AdpType`): <em>además, encima, debajo, acerca, después, detrás, aparte, dentro, delante, menos</em>
* `Preppron` (51; 22% of non-empty `AdpType`): <em>además, debajo, acerca, detrás, encima, dentro, alrededor, delante, después, lejos</em>

<table>
  <tr><th>Paradigm <i>después</i></th><th><tt>Prep</tt></th><th><tt>Preppron</tt></th></tr>
  <tr><td><tt>_</tt></td><td><em>después</em></td><td></td></tr>
  <tr><td><tt><a href="Gender.html">Gender</a>=Masc|<a href="Number.html">Number</a>=Sing</tt></td><td></td><td><em>después</em></td></tr>
</table>

### `ADJ`

176 [es-pos/ADJ]() tokens (1% of all `ADJ` tokens) have a non-empty value of `AdpType`.

The most frequent other feature values with which `ADJ` and `AdpType` co-occurred: <tt><a href="VerbForm.html">VerbForm</a>=EMPTY</tt> (176; 100%), <tt><a href="Number.html">Number</a>=EMPTY</tt> (144; 82%), <tt><a href="Gender.html">Gender</a>=EMPTY</tt> (144; 82%).

`ADJ` tokens may have the following values of `AdpType`:

* `Prep` (144; 82% of non-empty `AdpType`): <em>junto, debido, gran, nuevo</em>
* `Preppron` (32; 18% of non-empty `AdpType`): <em>junto, debido, mismo</em>

<table>
  <tr><th>Paradigm <i>junto</i></th><th><tt>Prep</tt></th><th><tt>Preppron</tt></th></tr>
  <tr><td><tt>_</tt></td><td><em>junto</em></td><td></td></tr>
  <tr><td><tt><a href="Gender.html">Gender</a>=Masc|<a href="Number.html">Number</a>=Sing</tt></td><td></td><td><em>junto</em></td></tr>
</table>

## Relations with Agreement in `AdpType`

The 10 most frequent relations where parent and child node agree in `AdpType`:
<tt>ADP --[<a href="../dep/fixed.html">fixed</a>]--> ADP</tt> (1085; 80%),
<tt>ADJ --[<a href="../dep/fixed.html">fixed</a>]--> ADP</tt> (172; 95%),
<tt>ADV --[<a href="../dep/fixed.html">fixed</a>]--> ADP</tt> (159; 76%),
<tt>ADP --[<a href="../dep/case.html">case</a>]--> ADP</tt> (78; 84%),
<tt>ADP --[<a href="../dep/case.html">case</a>]--> ADV</tt> (4; 100%),
<tt>ADP --[<a href="../dep/conj.html">conj</a>]--> ADP</tt> (2; 100%),
<tt>ADP --[<a href="../dep/case.html">case</a>]--> ADJ</tt> (2; 100%),
<tt>ADP --[<a href="../dep/mark.html">mark</a>]--> ADP</tt> (1; 100%),
<tt>ADP --[<a href="../dep/compound.html">compound</a>]--> ADP</tt> (1; 100%).

