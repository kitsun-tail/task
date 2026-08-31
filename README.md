# task

https://rosalind.info/problems/list-view/
1) Counting DNA Nucleotides
dna = 'AGCTTTTCATTCTGACTGCAACGGGCAATATGTCTCTGTGTGGATTAAAAAAAGAGTGTCTGATAGCAGC'
# 20 12 17 21

2) Transcribing DNA into RNA
dna = 'GATGGAACTTGACTACGTAAATT'
# GAUGGAACUUGACUACGUAAAUU

3) Complementing a Strand of DNA
dna = 'AAAACCCGGT'
# ACCGGGTTTT

4) Computing GC Content
dna = 'CCACCCTCGTGGTATGGCTAGGCATTCAGGAACCGGAGAACGCTTCAGACCAGCCCGGACTGGGAACCTGCGGGCAGTAGGTGGAAT'
# 60.919540

5) Counting Point Mutations
dna1 = 'GAGCCTACTAACGGGAT'
dna2 = 'CATCGTAATGACGGCCT'
# 7

6) Translating RNA into Protein
rna = 'AUGGCCAUGGCGCCCAGAACUGAGAUCAAUAGUACCCGUAUUAACGGGUGA'
# MAMAPRTEINSTRING

https://rosalind.info/glossary/rna-codon-table/
UUU F      CUU L      AUU I      GUU V
UUC F      CUC L      AUC I      GUC V
UUA L      CUA L      AUA I      GUA V
UUG L      CUG L      AUG M      GUG V
UCU S      CCU P      ACU T      GCU A
UCC S      CCC P      ACC T      GCC A
UCA S      CCA P      ACA T      GCA A
UCG S      CCG P      ACG T      GCG A
UAU Y      CAU H      AAU N      GAU D
UAC Y      CAC H      AAC N      GAC D
UAA Stop   CAA Q      AAA K      GAA E
UAG Stop   CAG Q      AAG K      GAG E
UGU C      CGU R      AGU S      GGU G
UGC C      CGC R      AGC S      GGC G
UGA Stop   CGA R      AGA R      GGA G
UGG W      CGG R      AGG R      GGG G

7) Finding a Motif in DNA
dna1 = 'GATATATGCATATACTT'
dna2 = 'ATAT'
# 2 4 10

8) Consensus and Profile
dnas = ['ATCCAGCT', 'GGGCAACT', 'ATGGATCT', 'AAGCAACC', 'TTGGAACT', 'ATGCCATT', 'ATGGCACT']
# ATGCAACT