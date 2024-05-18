PB-CSE221 Assignment 1
Sameer Singh Godara (2022439; sameer22439@iiitd.ac.in)

Question : 
1. Download the genome sequence of Baker’s Yeast (Saccharomyces cerevisiae) using Python or R. Submit and Document the code.
2. Find the Origin of Replication in the Yeast Genome. Give the logic and submit the code

Libraries and Modules Used : 
1. BioPython (module Entrez, SeqIO) : It is used to parse and process the input sequences.
2. module re : Functions under this module re allow you to perform various operations based on regular expressions, such as searching for patterns, finding all occurrences of a pattern, and many more.

Approach Used :
1. First, Downloaded the fasta files using the accession numbers which we hard-coded into the list, then the fasta file were named in specific convention used (i.e. "output_{chromosome_number}.fasta")
2. Then, I have surfed through various sites, to know Autonomously Replicating Sequence for Baker’s Yeast (Saccharomyces cerevisiae) (Method 1 + 2).
3. There were 2 types of sequences which are the core of the Origin of Replication in the Genome Sequence.
4. The 2 sequences are 5'-WTTTATRTTTW-3' and 5'-WTTTAYRTTTW-3'; which will have 8 and 16 possible cases, The latter sequence was found to be more precise.
5. Searching for these 2 sequences in whole genome, and stored the starting indexes of these sequences, to know the site where these sequences were found.
6. Printing these Indexes Side by Side for Each chromosome along with the sequence that is matched in the genome.
7. Another Method used for geting the Origin of Replication Site is the place where AT content is in high amount.
8. Taking input from user, about the window size, and the threshold percentage of AT content; window of particular size is in which we have to find the AT percentage.
9. Another Method used is, directly extracting data from the GeneBank by using the accession number of the chromosome.
10. And directly geting the indexes of the Origin of Replication in the DNA sequence; printing the initial and final index of the Replicating Origin in the sequence.


Sources:
Yeast Genome Database: https://www.yeastgenome.org/locus/S000114488
NCBI (National Center for Biotechnology Information): https://www.ncbi.nlm.nih.gov/pmc/articles/PMC1522085/
       
WikiPedia: https://en.wikipedia.org/wiki/Autonomously_replicating_sequence
