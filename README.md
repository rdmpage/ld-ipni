# ld-ini

Generate a version of IPNI’s data as N-triples for import into a triple store.

## IPNI

The International Plant Names Index (IPNI) https://www.ipni.org/ is an amalgamation of data from the Royal Botanic Gardens, Kew, Harvard University Herbaria & Libraries, and the Australian National Botanic Gardens. Each name in IPNI has a Life Science Identifier (LSID) which has an associated set of metadata in RDF/XML. This repository takes the XML for each IPNI name and reformats it as N-triples, correcting any minor format issues as part of that process. The resulting N-triples are intended to be uploaded into a triple store.

## License

The code in this repository is under a MIT license. The data from IPNI is under a [Creative Commons CC-BY](http://opendefinition.org/licenses/cc-by/) license.

