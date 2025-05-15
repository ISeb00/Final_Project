# Final_Project
Final project for BIOL 668
Jupyter notebooks that read in DNA and protein sequence files and Blast them using blastn or blastp.

1. FinalProject_blastn.ipynb
>Uses pFBD_SCTH2.fasta, a whole plasmid sequence of the pFastBac Dual vector with two protein inserts under different promotors. Regions encoding proteins of interest are sliced from the plasmid sequence and blasted against the nucleotide database. Results are parsed and iterated through to generate readable outputs of hits and alignments.
2. FinalProject_blastp.ipynb
>Uses prtn_DmIKKB-uniprot.fasta and prtn_DmIKKY-uniprot.fasta. The two protein sequences are blasted, searching against the PDB database. Results are parsed and iterated through to generate readable outputs of hits, alignments and scores, E values, and PDB IDs.
