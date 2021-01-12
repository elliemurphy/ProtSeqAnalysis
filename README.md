# ProtSeqAnalysis
Data Science and Machine Learning for the Biosciences

**Software that explores protein sequences from land plant gene families.** 

There are three sections to the software:
1. A simple error checking function that identifies if there are any characters in sequences that do not represent an amino acid.
2. A function to calculate amino acid composition of a protein sequence and plot the results.
3. A final function allowing the identification of conserved motifs in protein sequences.

To run:
1. Import necessary programs.
2. Any protein sequence may be run through the error checking and amino acid composition functions. 
..Example protein sequences derived from *Arabidopsis thaliana* encoding PYL1 and PYL2 receptor proteins has been included in the Markdown for use. These were obtained from Uniprot (https://www.uniprot.org/uniprot/Q8VZS8; https://www.uniprot.org/uniprot/O80992).
3. A number of BMGE files (.bmge) have also been uploaded as sample data for the conserved motif search function. Save these files to the working directory.
..Once again, an example of a motif sequence to input when prompted has been included. Alternative motifs may be obtained though the NCBI Batch CD-Search Tool [NCBI] (https://www.ncbi.nlm.nih.gov/Structure/bwrpsb/bwrpsb.cgi), which identifies and lists any conserved domains within the protein sequence you provide.
4. Run the motif search functions to analyse the sequences within the downloaded BMGE files, and identify any sequences containing the motif.
5. The results of the motif search will be placed in a new file (Results.txt) displaying each BMGE file and a list of the sequences containing the specified motif.
6. The text file output may be used for extended analysis, although due to time constraints the software for this is not included.
