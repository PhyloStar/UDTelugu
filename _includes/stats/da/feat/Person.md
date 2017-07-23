

--------------------------------------------------------------------------------

## Treebank Statistics (UD_Danish)

This feature is universal.
It occurs with 3 different values: `1`, `2`, `3`.

5021 tokens (6%) have a non-empty value of `Person`.
64 types (0%) occur at least once with a non-empty value of `Person`.
22 lemmas (0%) occur at least once with a non-empty value of `Person`.
The feature is used with 2 part-of-speech tags: [da-pos/PRON]() (4303; 5% instances), [da-pos/DET]() (718; 1% instances).

### `PRON`

4303 [da-pos/PRON]() tokens (70% of all `PRON` tokens) have a non-empty value of `Person`.

The most frequent other feature values with which `PRON` and `Person` co-occurred: <tt><a href="PronType.html">PronType</a>=Prs</tt> (4303; 100%), <tt><a href="PartType.html">PartType</a>=EMPTY</tt> (4303; 100%), <tt><a href="Number.html">Number</a>=Sing</tt> (3053; 71%), <tt><a href="Gender.html">Gender</a>=Com</tt> (2430; 56%), <tt><a href="Case.html">Case</a>=Nom</tt> (2224; 52%).

`PRON` tokens may have the following values of `Person`:

* `1` (1103; 26% of non-empty `Person`): <em>jeg, vi, mig, os, min, vore</em>
* `2` (197; 5% of non-empty `Person`): <em>du, dig, De, I, jer, Dem, Deres</em>
* `3` (3003; 70% of non-empty `Person`): <em>det, han, de, sig, hun, den, ham, dem, hende, dét</em>
* `EMPTY` (1807): <em>der, man, som, hvad, noget, selv, en, andre, hver, andet</em>

<table>
  <tr><th>Paradigm <i>de</i></th><th><tt>2</tt></th><th><tt>3</tt></th></tr>
  <tr><td><tt><a href="Case.html">Case</a>=Acc|<a href="Number.html">Number</a>=Plur</tt></td><td></td><td><em>dem</em></td></tr>
  <tr><td><tt><a href="Case.html">Case</a>=Nom|<a href="Gender.html">Gender</a>=Com|<a href="Polite.html">Polite</a>=Form</tt></td><td><em>De</em></td><td></td></tr>
  <tr><td><tt><a href="Case.html">Case</a>=Nom|<a href="Number.html">Number</a>=Plur</tt></td><td></td><td><em>de</em></td></tr>
</table>

`Person` seems to be **lexical feature** of `PRON`. 94% lemmas (17) occur only with one value of `Person`.

### `DET`

718 [da-pos/DET]() tokens (14% of all `DET` tokens) have a non-empty value of `Person`.

The most frequent other feature values with which `DET` and `Person` co-occurred: <tt><a href="Poss.html">Poss</a>=Yes</tt> (718; 100%), <tt><a href="PronType.html">PronType</a>=Prs</tt> (718; 100%), <tt><a href="Number[psor].html">Number[psor]</a>=Sing</tt> (542; 75%), <tt><a href="Gender.html">Gender</a>=EMPTY</tt> (384; 53%).

`DET` tokens may have the following values of `Person`:

* `1` (174; 24% of non-empty `Person`): <em>min, vores, mit, vore, mine, vor, vort</em>
* `2` (32; 4% of non-empty `Person`): <em>din, Deres, jeres, dit, dine</em>
* `3` (512; 71% of non-empty `Person`): <em>sin, deres, hans, sit, hendes, sine, dets, dens</em>
* `EMPTY` (4287): <em>en, den, de, et, det, andre, denne, nogle, ingen, anden</em>

`Person` seems to be **lexical feature** of `DET`. 100% lemmas (11) occur only with one value of `Person`.

## Relations with Agreement in `Person`

The 10 most frequent relations where parent and child node agree in `Person`:
<tt>PRON --[<a href="../dep/appos.html">appos</a>]--> PRON</tt> (1; 100%),
<tt>PRON --[<a href="../dep/reparandum.html">reparandum</a>]--> PRON</tt> (1; 100%).

