

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Lithuanian)

This feature is universal.
It occurs with 3 different values: `Cmp`, `Pos`, `Sup`.

721 tokens (13%) have a non-empty value of `Degree`.
515 types (22%) occur at least once with a non-empty value of `Degree`.
362 lemmas (23%) occur at least once with a non-empty value of `Degree`.
The feature is used with 3 part-of-speech tags: [lt-pos/ADJ]() (399; 7% instances), [lt-pos/ADV]() (321; 6% instances), [lt-pos/CCONJ]() (1; 0% instances).

### `ADJ`

399 [lt-pos/ADJ]() tokens (96% of all `ADJ` tokens) have a non-empty value of `Degree`.

The most frequent other feature values with which `ADJ` and `Degree` co-occurred: <tt><a href="Definite.html">Definite</a>=Ind</tt> (366; 92%), <tt><a href="Number.html">Number</a>=Sing</tt> (245; 61%), <tt><a href="Gender.html">Gender</a>=Masc</tt> (235; 59%).

`ADJ` tokens may have the following values of `Degree`:

* `Cmp` (13; 3% of non-empty `Degree`): <em>blogesnis, gajesnis, gilesnės, greitesniu, mielesnis, platesnių, sudėtingesnė, svarbesne, svarbesnių, svarbesnė</em>
* `Pos` (374; 94% of non-empty `Degree`): <em>kitų, vienas, lietuvis, tautinės, gero, kitas, lietuviu, lietuvius, lietuvių, tautinė</em>
* `Sup` (12; 3% of non-empty `Degree`): <em>svarbiausias, Sudėtingiausias, baisiausia, geriausias, griežčiausiomis, lengviausia, realiausia, svarbiausios, tikriausia, tinkamiausias</em>
* `EMPTY` (15): <em>1939, XIX, šiaip, 1941, 1944, 1961, 2002, 25, 423, XX</em>

<table>
  <tr><th>Paradigm <i>svarbus</i></th><th><tt>Pos</tt></th><th><tt>Cmp</tt></th><th><tt>Sup</tt></th></tr>
  <tr><td><tt><a href="Case.html">Case</a>=Gen|<a href="Gender.html">Gender</a>=Masc|<a href="Number.html">Number</a>=Plur</tt></td><td></td><td><em>svarbesnių</em></td><td></td></tr>
  <tr><td><tt><a href="Case.html">Case</a>=Gen|<a href="Gender.html">Gender</a>=Fem|<a href="Number.html">Number</a>=Sing</tt></td><td></td><td></td><td><em>svarbiausios</em></td></tr>
  <tr><td><tt><a href="Case.html">Case</a>=Ins|<a href="Gender.html">Gender</a>=Fem|<a href="Number.html">Number</a>=Sing</tt></td><td></td><td><em>svarbesne</em></td><td></td></tr>
  <tr><td><tt><a href="Case.html">Case</a>=Nom|<a href="Gender.html">Gender</a>=Masc|<a href="Number.html">Number</a>=Sing</tt></td><td><em>svarbus</em></td><td></td><td><em>svarbiausias</em></td></tr>
  <tr><td><tt><a href="Case.html">Case</a>=Nom|<a href="Gender.html">Gender</a>=Fem|<a href="Number.html">Number</a>=Sing</tt></td><td></td><td><em>svarbesnė</em></td><td></td></tr>
</table>

`Degree` seems to be **lexical feature** of `ADJ`. 97% lemmas (205) occur only with one value of `Degree`.

### `ADV`

321 [lt-pos/ADV]() tokens (100% of all `ADV` tokens) have a non-empty value of `Degree`.

`ADV` tokens may have the following values of `Degree`:

* `Cmp` (31; 10% of non-empty `Degree`): <em>vėliau, daugiau, labiau, tiksliau, blogiau, mažiau, sunkiau, toliau, anksčiau, geriau</em>
* `Pos` (282; 88% of non-empty `Degree`): <em>tik, dar, šiandien, taip, visada, šiol, dabar, tada, aiškiai, gana</em>
* `Sup` (8; 2% of non-empty `Degree`): <em>pirmiausia, geriausiai, greičiausiai, seniausiai</em>

<table>
  <tr><th>Paradigm <i>gerai</i></th><th><tt>Pos</tt></th><th><tt>Cmp</tt></th><th><tt>Sup</tt></th></tr>
  <tr><td><tt></tt></td><td><em>gerai</em></td><td><em>geriau</em></td><td><em>geriausiai</em></td></tr>
</table>

`Degree` seems to be **lexical feature** of `ADV`. 97% lemmas (147) occur only with one value of `Degree`.

### `CCONJ`

1 [lt-pos/CCONJ]() tokens (0% of all `CCONJ` tokens) have a non-empty value of `Degree`.

`CCONJ` tokens may have the following values of `Degree`:

* `Pos` (1; 100% of non-empty `Degree`): <em>kiek</em>
* `EMPTY` (310): <em>ir, bet, o, ar, bei, arba, nei, ne, tačiau, taigi</em>

## Relations with Agreement in `Degree`

The 10 most frequent relations where parent and child node agree in `Degree`:
<tt>ADJ --[<a href="../dep/advmod.html">advmod</a>]--> ADV</tt> (31; 89%),
<tt>ADJ --[<a href="../dep/conj.html">conj</a>]--> ADJ</tt> (31; 100%),
<tt>ADV --[<a href="../dep/fixed.html">fixed</a>]--> ADV</tt> (8; 100%),
<tt>ADV --[<a href="../dep/advmod.html">advmod</a>]--> ADV</tt> (8; 62%),
<tt>ADV --[<a href="../dep/conj.html">conj</a>]--> ADV</tt> (4; 80%),
<tt>ADV --[<a href="../dep/parataxis.html">parataxis</a>]--> ADV</tt> (2; 67%),
<tt>ADJ --[<a href="../dep/amod.html">amod</a>]--> ADJ</tt> (2; 100%),
<tt>ADV --[<a href="../dep/advcl.html">advcl</a>]--> ADJ</tt> (2; 100%),
<tt>ADV --[<a href="../dep/fixed.html">fixed</a>]--> ADJ</tt> (2; 100%),
<tt>ADJ --[<a href="../dep/orphan.html">orphan</a>]--> ADJ</tt> (1; 100%).

