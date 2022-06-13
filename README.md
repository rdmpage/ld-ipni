# ld-ini

Generate a version of IPNI’s data for import into a triple store.

## IPNI

The International Plant Names Index (IPNI) https://www.ipni.org/ is an amalgamation of data from the Royal Botanic Gardens, Kew, Harvard University Herbaria & Libraries, and the Australian National Botanic Gardens. Each name in IPNI has a Life Science Identifier (LSID) which has an associated set of metadata in RDF/XML. This repository takes the XML, corrects any minor format issues, and creates a single file comprising one XML record per line.

## License

The code in this repository is under a MIT license. The data from IPNI is under a [Creative Commons CC-BY](http://opendefinition.org/licenses/cc-by/) license.

