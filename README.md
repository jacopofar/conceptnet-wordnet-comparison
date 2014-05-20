conceptnet-wordnet-comparison
=============================

This application compares Conceptnet and Wordnet IsA relationships to list differences.
Concepted contains more data (nodes, edges and kinds of concepts) than Wordnet, but often with a lower quality.
The idea behind this small program is to compare the two knowledge bases in order to list differences and possibly build and valuate heuristics to identify wrong edges, mainly IsA relationshisp.

Currently, the application just create two TSV files listing the IsA relationships present in conceptnet between lemmas present also in Wordnet, one for relationshisp present also in Wordnet, the other one for the absent ones.

For each hyponym-hypernym couple a natural language description is given when present in conceptnet.
