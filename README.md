# LoB_scores
LoB scores generated from K-OPL profiles.
Originally described Cornett, 2018 DOI: 10.1126/sciadv.aav2623

Where might my methyllysine reading protein/antibody bind in the human proteome? 

K-OPL profile: The amino acid preference determined for a protein in positions plus and minus three from a methyllysine. 
Determined by using a sequence degenerate Lysine Oriented Peptide Library (K-OPL).

LoB score: Lowest Bin (LoB) scoring ranks the most likely binders in the human proteome.
LoB scoring minimizes false positives because the lowest K-OPL value dictates the score instead of positionally weighting residues.

Files are organized by methyl order of K-OPL.
Within a file, the four columns from left to right are uniprot ID, lysine centered sevenmer sequence, LoB score, and residue number of the central lysine within the protein.
