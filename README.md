# Ethereology

This project is built and maintained in LaTeX, XML (RDF, OWL), and HTML. It uses frontend and backend technologies to create a seamless environment between which anyone can explore, use, and understand Ethereum. It is composed of three separate parts that all work in complementary relationships to each other. sections utilizes APIs from [Etherscan](https://www.etherscan.io/apis) to track specific instances as examples.

## Modules

Modules represent sectionally complete, linguistically coherent, and descriptively precise documentation for Ethereum. A module is a chunk of technical writing that is larger than a sentence but smaller than a chapter, and which (being neutral in regard to content) can be put into a backend database and reproduced in any number of frontend applications.

All modules are stored in the modules/ directory using XML formatting. They are reproduced on the main site Directories containing the file "template.tex" represent entries that still need to be written.

### Pseudocode

When defining formal math operations, e.g. those from the Yellowpaper, prefer pseudocode. Anyone can write pseudocode by imagining whatever process one is trying to describe in terms of operational steps: 

<pre>
<i>first</i> do <i>this</i>
<i>then</i> do <i>that</i>
</pre>

## Revised Yellowpaper

There is need for a shorter and more concise Ethereum specification as a companion piece to this website. This is being written, modified, and maintained in the directory "off-whitepaper." 

## Ontology

For those who want to go *very* deep in their understanding of Ethereum, of its various parts, and of how they relate to the whole, a key component is the Ontology, which classifies the data stored in each module in logical relation to its component and exponent parts.

## Project Goals:

1. To help Ethereum developers build increasingly efficient and robust client implementations.
2. To include all necessary facts about Ethereum, and only those facts which are necessary for describing it.
3. To re-word, re-phrase, and/or re-identify concepts and terms which are not necessarily intuitively clear, to make them more intuitively clear.

## Further Resources

Links to several but not all of the various resources cited can be found in the references directory.
