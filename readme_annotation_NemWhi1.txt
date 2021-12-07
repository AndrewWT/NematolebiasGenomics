The genome annotation for the Rio Pearlfish (Nematolebias whitei), genome version NemWhi1 (NCBI accession: JAAMPK000000000), contained in this folder was generated with MAKER 2.31 by Andrew W. Thompson and Ingo Braasch (Michigan State U). Annotations represent the ‘MAKER standard build’ genes (see Campbell et al., 2014, Current Protoc Bioinform 48:4.11.1-4.11.39).


==========================================

Files in this folder:

reduced_NEW.gff			This is the GFF file containing info on MAKER standard genes only (repeat elements, blast hits, etc., removed)
NEW_transcripts.fasta		This is the fasta file of transcripts from gene models as output by the MAKER Standard pipeline
NEW_proteins.fasta		This is the fasta file of proteins from gene models as output by the MAKER Standard pipeline


==========================================

Nomenclature conventions:

We implement a nomenclature of constant character length:  NEW followed by a one letter prefix identifier-G, P, or T, followed by 8 digits.

1. IDs in the GFF file have a "G" prefix for "gene": 
NEWG00000001
NEWG00000002
...
NEWG00000009
NEWG00000010
...

2. IDs in the fasta transcript file have a "T" prefix for "transcript":
NEWT00000001
NEWT00000002
...

3. IDs in the fasta protein file have a "P" prefix for "protein":
NEWP00000001
NEWP00000002
...

Genes-Transcripts-Proteins are associated with the same digit identifier. So that:
Gene NEWG00000001 has transcript NEWT00000001 which encodes protein NEWP00000001. 

If a gene has additional alternative transcripts then these would become
NEWT10000001, NEWT20000001... and NEWP10000001, NEWP20000001... for the corresponding proteins.
Note that in the current annotation, each gene is represented by one transcript (and protein) only.

Gene/Transcript/Protein IDs are ordered by their appearance in the sorted GFF file, so that NEWG00000001 is the first gene on Nwh_scaf_1, which happens to be the first scaffold in the GFF file with an annotated gene (note that scaffolds are not in order from largest to smallest in the GFF file).


==========================================

For questions, concerns, issues, suggestions, please contact:

Ingo Braasch	braasch@msu.edu		+1 (517) 432 3484
Drew Thompson	thom1524@msu.edu	+1 (517) 432 3485