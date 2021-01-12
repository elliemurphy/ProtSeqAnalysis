# ProtSeqAnalysis
Data Science and Machine Learning for the Biosciences

**Software that explores protein sequences from land plant gene families.** 

There are three sections to the software:
1. A simple error checking function that identifies if there are any characters in sequences that do not represent an amino acid
2. A function to calculate amino acid composition of a protein sequence and plot the results
3. A final function allowing the identification of conserved motifs in protein sequences

To run:
1. Import necessary programs
2. Any protein sequence may be run through the error checking and amino acid composition functions. An example protein sequence derived from *Arabidopsis thaliana* encoding SLAH1, a protein bearing similarity to the SLAC1 protein, has been included in the Markdown for use
3. A number of .bgme files have also been uploaded as sample data for the conserved motif search function. Save these files to the working directory
4. Once again, an example of a conserved motif sequence to input when prompted has been included
5. This function may be used to analyse the sequences within any BMGE files, and the conserved motif may be altered as necessary
6. The results of the motif search will be placed in a new file (Results.txt) displaying each .bmge file and a list of the sequences containing the specified motif
7. The text file output will allow subsequent analysis of the search results, although due to time constraints the software for this is not included
