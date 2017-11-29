# Modules

Complete, coherent, and modular documentation for Ethereum. This project is built and maintained in LaTeX. A module is a chunk of technical documentation that is larger than a sentence but smaller than a chapter, and which (being neutral in regard to content) can be put into a backend database and reproduced in any number of frontend applications.

In the modules/ directory, you'll find single LaTeX articles covering various topics that are both *intrinsic*, and conceptually *centripetal*, to understanding the technical details which undergird Ethereum. Folders in the modules/ directory that contain the file "template.tex" represent topical entries which have not yet been written.

##### Focuses of this project:

1. To help users build working Ethereum client implementations.
2. To include all necessary facts, and only those facts.
3. To remove obstacles against understanding which exist in the current protocol specification.
4. To re-word, re-phrase, or re-identify concepts and terms which are not intuitively clear, to make them intuitively clear.

##### Revised Yellowpaper

In addition to modular documentation, a second goal of this project is to put all of the modules together into an entirely new specification. This is being constructed in: modules/offwhtp/off-whitepaper.pdf

##### Pseudocode

When defining formal math operations, prefer pseudocode. Anyone can write pseudocode by imagining whatever process one is trying to describe in terms of operational steps: 

<pre>
<i>first</i> do <i>this</i>
<i>then</i> do <i>that</i>
</pre>

Links to several but not all of the various resources cited can be found in the references directory.
