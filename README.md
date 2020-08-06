# Quantifying the distribution of protein oligomerization degree reflects cellular information capacity

## Supplementary Method S1: Protein-homo-oligomer distribution calculation
Protein_classification.ipynb python notebook is calculating frequency of proteins with different subunits number for nine organisms’ whole proteomes as listed:
Name	          ID 	        Type	      Link
E. coli	        up000000625	Prokaryote	https://www.uniprot.org/proteomes/UP000000625
H. pylori	up000000429	Prokaryote	https://www.uniprot.org/proteomes/UP000000625
B. subtilis	up000001570	Prokaryote	https://www.uniprot.org/proteomes/UP000001570
D. discoideum	up000002195	Eukaryote	https://www.uniprot.org/proteomes/UP000002195
S. cerevisiae	up000002311	Eukaryote	https://www.uniprot.org/proteomes/UP000002311
D. melanogaster	up000000803	Eukaryote	https://www.uniprot.org/proteomes/UP000000803
M. musculus	up000000589	Eukaryote	https://www.uniprot.org/proteomes/UP000000589
D. rerio	up000000437	Eukaryote	https://www.uniprot.org/proteomes/UP000000437
H. sapiens	up000005640	Eukaryote   	https://www.uniprot.org/proteomes/UP000005640

Based on GO classification as defined

Molecular function	GO:0003674
  catalytic	GO:0003824		
  transporter	GO:0005215		
  binding	GO:0005488		
  transcription regulator	GO:0140110		

Cellular Component	GO:0005575
  membrane part	GO:0044425		
  cell part	GO:0044464
  intrinsic component of membrane	GO:0031224
  periplasmic space	GO:0042597
  plasma membrane	GO:0005886
  cytosol	GO:0005829
  
Biological process	GO:0008150
  cellular component organization	GO:0071840		
  response to stimulus	GO:0050896		
  localization	GO:0051179
  biological regulation	GO:0065007		
  metabolic process	GO:0008152
  nitrogen compound	GO:0006807
  catabolic process	GO:0009056
  biosynthetic process	GO:0009058
  oxidation-reduction process	GO:0055114

To reproduce calculation, all repository including the data files need to be downloaded. Jupiter Notebook free access software needs to be installed to run the Protein_classification.ipynb file.

## Supplementary Method S2: Protein-homo-oligomer abundance distribution calculation
Protein_classification_abundance.ipynb python notebook calculates the abundance distribution of proteins with different subunits number for eight organisms as listed:

Name	        ID 	  Coverage	Score	  File
E. coli         137	  99	      23.08	  511145-WHOLE_ORGANISM-integrated.txt
M. tuberculosis	253	  85	      12.33	  83332-WHOLE_ORGANISM-integrated.txt
B. henselae	437	  86	      9.2	  283166-Bhenselae_Albrethsen_2013.txt
S. pombe	250	  90	      18.49	  4896-WHOLE_ORGANISM-integrated.txt
S. cerevisiae	3	  96	      21.24	  4932-WHOLE_ORGANISM-integrated.txt
R. norvegicus	93	  73	      14.59	  10116-WHOLE_ORGANISM-integrated.txt
M. musculus	196	  89	      14.15	  10090-WHOLE_ORGANISM-integrated.txt
H. sapiens	29	  87	      15.5	  9606-WHOLE_ORGANISM-integrated.txt


Based on mapping as defined:
Name	          ID 	        Type	     	Link
E. coli	        up000000625	Prokaryote	https://www.uniprot.org/proteomes/UP000000625
M. tuberculosis	up000001584	Prokaryote	https://www.uniprot.org/proteomes/UP000001584
B. henselae	up000058422	Prokaryote	https://www.uniprot.org/proteomes/UP000058422
S. pombe	up000002485	Eukaryote   	https://www.uniprot.org/proteomes/UP000002485
S. cerevisiae	up000002311	Eukaryote   	https://www.uniprot.org/proteomes/UP000002311
R. norvegicus	up000002494	Eukaryote	https://www.uniprot.org/proteomes/UP000000803
M. musculus	up000000589	Eukaryote	https://www.uniprot.org/proteomes/UP000000589
H. sapiens	up000005640	Eukaryote	https://www.uniprot.org/proteomes/UP000005640


To reproduce calculation, all repository including the data files needs to be downloaded. Jupiter Notebook free access software need to be installed to run the Protein_classification_abundance.ipynb file.
