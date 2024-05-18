PB-CSE221 Assignment 2
Sameer Singh Godara (2022439; sameer22439@iiitd.ac.in)


Questions:
1. Access the NCBI database (https://www.ncbi.nlm.nih.gov/) and download the DNA sequence of the Saccharomyces cerevisiae PDC gene. (5 marks)
2. Use BLAST (Basic Local Alignment Search Tool) to compare the PDC gene sequence across different Saccharomyces cerevisiae strains and identify SNPs. (5 marks)
3. Use an translation tool (e.g., ExPASy Translate tool) to translate the normal and SNP-containing PDC gene sequences into amino acid sequences. (5 marks)
4. Select a SNP within the PDC gene. Utilize tools like SIFT (Sorting Intolerant From Tolerant) or PolyPhen (Polymorphism Phenotyping) to predict the impact of the SNP on the PDC protein function. (5 marks)


Library Used:
1. BioPython (module Entrez, SeqIO, NCBIWWW, NCBIXML) : It is used to parse; process the input sequences and perform blast methods and extract the data from the file returned by the blast query.


Taken help from various sources:
NCBI (National Center for Biotechnology Information): https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1522085/
Yeast Genome for knowing the sequence of the starting and ending index of the required gene which is PDC 1, PDC 5 and PDC 6.
https://www.hiv.lanl.gov/content/sequence/FORMAT_CONVERSION/form.html - For making a fasta file for protein sequence
http://genetics.bwh.harvard.edu/pph2/index.shtml - To predict the impact of the SNP on the PDC protein function


My Approach to solve the question:
1. First I downloaded the particular genome sequence of Baker's Yeast using their Accession Number.
2. I have used different functions for each specific task.
3. Then Extracting the sequence from it I applied the BLASTN query, for that sequence.
4. So as result I got a XML file, through which I have to extract the required data.
5. The data is extracted and formatted according to the requirement of the question.
6. SNP is Single Nucleotide Polymorphism, which is only possible when only one nucleotide is mis-match and other nucleotides beside that must have proper match.
7. I have removed excessive gaps and ambigious nucleotides from the sequence before translating them to their protein sequence.
8. After that I have created the fasta file for the protein sequence, and after finding the particular SNP's, I have uploaded the data, for Poly-Phen, for predicting the impact of SNP on that protein sequence. 


Answer of Last Question (4th Question):
Results for PolyPhen-2 analysis of Different SNP's in 3 Gene of Saccharomyces cerevisiae, i.e. PDC 1, PDC 5 and PDC 6

session id : 0ee7cc0802f7d10ef08cc68d35b7ead9646c9924

link 1 : http://genetics.bwh.harvard.edu/ggi/pph2/0ee7cc0802f7d10ef08cc68d35b7ead9646c9924/9644046.html : PDC 1
link 2 : http://genetics.bwh.harvard.edu/ggi/pph2/0ee7cc0802f7d10ef08cc68d35b7ead9646c9924/9644047.html : PDC 1
link 3 : http://genetics.bwh.harvard.edu/ggi/pph2/0ee7cc0802f7d10ef08cc68d35b7ead9646c9924/9644048.html : PDC 1
link 4 : http://genetics.bwh.harvard.edu/ggi/pph2/0ee7cc0802f7d10ef08cc68d35b7ead9646c9924/9644049.html : PDC 1
link 5 : http://genetics.bwh.harvard.edu/ggi/pph2/0ee7cc0802f7d10ef08cc68d35b7ead9646c9924/9644050.html : PDC 1
link 6 : http://genetics.bwh.harvard.edu/ggi/pph2/0ee7cc0802f7d10ef08cc68d35b7ead9646c9924/9644054.html : PDC 5
link 7 : http://genetics.bwh.harvard.edu/ggi/pph2/0ee7cc0802f7d10ef08cc68d35b7ead9646c9924/9644057.html : PDC 5
link 8 : http://genetics.bwh.harvard.edu/ggi/pph2/0ee7cc0802f7d10ef08cc68d35b7ead9646c9924/9644058.html : PDC 5
link 9 : http://genetics.bwh.harvard.edu/ggi/pph2/0ee7cc0802f7d10ef08cc68d35b7ead9646c9924/9644060.html : PDC 5
link 10 : http://genetics.bwh.harvard.edu/ggi/pph2/0ee7cc0802f7d10ef08cc68d35b7ead9646c9924/9644061.html : PDC 5
link 11 : http://genetics.bwh.harvard.edu/ggi/pph2/0ee7cc0802f7d10ef08cc68d35b7ead9646c9924/9645333.html : PDC 6
link 12 : http://genetics.bwh.harvard.edu/ggi/pph2/0ee7cc0802f7d10ef08cc68d35b7ead9646c9924/9645338.html : PDC 6
link 13 : http://genetics.bwh.harvard.edu/ggi/pph2/0ee7cc0802f7d10ef08cc68d35b7ead9646c9924/9645353.html : PDC 6
link 14 : http://genetics.bwh.harvard.edu/ggi/pph2/0ee7cc0802f7d10ef08cc68d35b7ead9646c9924/9645357.html : PDC 6
link 15 : http://genetics.bwh.harvard.edu/ggi/pph2/0ee7cc0802f7d10ef08cc68d35b7ead9646c9924/9645373.html : PDC 6