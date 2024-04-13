# Ensemble

A bio-dataset, available through the [ftp server of ensembl](https://ftp.ensembl.org/pub/). The most recent release was used which is release 111 as of writing this.

## Usage
Using the [📜extraction script](./unpack_files.py) the compressed tsv files can easily be extracted. Every file has a header line and for each animal there are four provided schemas. [RefSeq](https://www.ncbi.nlm.nih.gov/refseq/), [Entrez](https://en.wikipedia.org/wiki/Entrez), [ENA](https://www.ebi.ac.uk/ena/browser/home) and [UniProt](https://www.uniprot.org/).

These versions will be referenced as `Ensemble-RefSeq`, `Ensemble-Entrez`, `Ensemble-ENA` and `Ensemble-UniProt`.