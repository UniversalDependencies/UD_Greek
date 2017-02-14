# UD_Greek

## Description
The Greek UD Treebank is derived from the Greek Dependency Treebank (http://gdt.ilsp.gr), a resource developed and maintained by researchers at the Institute for Language and Speech Processing/Athena R.C. (http://www.ilsp.gr).

This release was generated by automatically converting the original annotations, with manual checks of several constructions. The conversion and harmonization to UD v2.0 is work in progress. The data in this release derive from primary texts that are in the public domain, including wikinews articles and european parliament sessions.

## Basic statistics

- Sentences: 2521
- Tokens: 61773
- Data split in train/dev/test sets: 1662/403/456 sentences, 41212/10139/10422 tokens

## Acknowledgments

We wish to thank all contributors to the original annotation efforts. A large part of those annotations was work by students of the postgraduate programme Technoglossia IV, organised by the Institute for Language and Speech Processing, the University of Athens and the National Technical University of Athens.

## References

* Prokopis Prokopidis and Haris Papageorgiou. Experiments for Dependency Parsing of Greek. In Proceedings of the First Joint Workshop on Statistical Parsing of Morphologically Rich Languages and Syntactic Analysis of Non-Canonical Languages, pages 89 -96, Dublin, Ireland, August 2014.

* Prokopis Prokopidis, Elina Desypri, Maria Koutsombogera, Haris Papageorgiou, and Stelios Piperidis. Theoretical and Practical Issues in the Construction of a Greek Dependency Treebank. In Montserrat Civit, Sandra Kubler, and Ma. Antonia Marti, editors, Proceedings of The Fourth Workshop on Treebanks and Linguistic Theories (TLT 2005), pages 149-160, Barcelona, Spain, December 2005. Universitat de Barcelona.

### CHANGELOG

#### 2.0
- Semi-automatic conversion to UD v2.0
- New data split into train/dev/test sets

#### 1.4
- Fixed issues in conversion of POS for articles

#### 1.3
- Added PronType and NumType attribute/value pairs to certain types of determiners and numerals
- Improved conversion of abbreviations

#### 1.2
- Fixed issues in conversion of determiner pos and adjective degree

#### 1.1
- Initial release of automatic conversion to UD

=== Machine-readable metadata =================================================
Documentation status: partial
Data source: semi-automatic
Data available since: UD v1.1
License: CC BY-NC-SA 3.0
Genre: news wiki spoken
Contributors: Prokopidis, Prokopis
Contact: prokopis@ilsp.gr

