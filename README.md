# Protein Seqence classification using Deep Learning and RNN from Pfam protein dataset

Description of fields:

sequence: These are usually the input features to your model. Amino acid sequence for this domain.
There are 20 very common amino acids (frequency > 1,000,000), and 4 amino acids that are quite
uncommon: X, U, B, O, Z.

family_accession: These are usually the labels for your model. Accession number in form PFxxxxx.y
(Pfam), where xxxxx is the family accession, and y is the version number.
Some values of y are greater than ten, and so 'y' has two digits.

family_id: One word name for family.

sequencename: Sequence name, in the form "$uniprotaccessionid/$startindex-$end_index".

aligned_sequence: Contains a single sequence from the multiple sequence alignment (with the rest of the members of
the family in seed, with gaps retained.
