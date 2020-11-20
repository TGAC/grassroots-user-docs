##Introduction

[BLAST](https://blast.ncbi.nlm.nih.gov/Blast.cgi) is a tool by NCBI to find regions of similarity between biological sequences. It can compare nucleotide or protein sequences to sequence databases and calculate the statistical significance of how similar they are.

There are currently 3 BLAST Services that can be run within Grassroots:

 * **blastn** for searching nucleotide databases using nucleotide queries.
 * **blastp** for searching protein databases using protein queries.
 * **blastx** for searching protein databases using translated nucleotide queries.

The standard form for entering a BLAST search consists of:

 * **Query Sequence Parameters**: This is the sequence that you wish to search for.

Below this is a list of available databases where you can tick the databases that you wish to search for your query sequence in.

![The form for submitting a BLAST search](images/basic_options.png "Submit BLAST Search")

