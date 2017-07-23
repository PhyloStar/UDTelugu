---
layout: base
title:  'UD Contributors'
udver: '2'
---

# Contributors

## Universal guidelines

<!-- alphabetical by surname -->
* [Marie-Catherine de Marneffe](http://www.ling.ohio-state.edu/~mcdm/)
* [Filip Ginter](http://bionlp.utu.fi/)
* [Yoav Goldberg](http://www.cs.biu.ac.il/~yogo/)
* [Jan Hajič](http://ufal.mff.cuni.cz/jan-hajic/)
* [Christopher Manning](http://nlp.stanford.edu/~manning/)
* [Ryan McDonald](http://www.ryanmcd.com)
* [Joakim Nivre](http://stp.lingfil.uu.se/~nivre/)
* [Slav Petrov](http://www.petrovi.de/)
* [Sampo Pyysalo](http://bionlp.utu.fi/)
* Sebastian Schuster
* Natalia Silveira
* Reut Tsarfaty
* Francis Tyers
* [Dan Zeman](http://ufal.mff.cuni.cz/daniel-zeman/)

## Language-specific guidelines and treebanks 

This is the list of UD contributors gathered from the repository README files. See [here](language_metadata.html) for instructions on how to list contributors for your language.

{% for l in site.data.ldata %}

* **{{l.lang_name}}**: {{ l.contributors | map: 'full' | join:', ' }}

{% endfor %}
