# Multi-Dimensional-Analysis
Code for a part-of-speech-driven MD analysis using the Stanford Tagger and R

The code is semi-flexible in that it was originially written to perform an MD analysis of a particular version of the English Protestant Bible, but can be modified for any (collection of) text(s).

This project includes the following documents:
<br>1. "Bible-FA-results.zip" contains the output of R's summary statistics for the original factor analysis of the Bible, and barplots of the resulting factor scores for each of the three factors inferred in the factor analysis
<br>2. "MD-code" contains all code used for MD analysis (all in R, except running the Tagger from Unix command line)
<br>3. "MD-code.txt" download code in .txt file
<br>4. "NIV-Bible.txt" the version of the New International Version Bible used in the original MD analysis
<br>5. "Tagged-Bible-Books.zip" folder containing the POS-tagged versions of the 66 books of the NIV-Bible.txt file

The Stanford Tagger can be downloaded at http://nlp.stanford.edu/software/tagger.shtml 
<br>Kristina Toutanova, Dan Klein, Christopher Manning, and Yoram Singer. 2003. Feature-Rich Part-of-Speech Tagging with a Cyclic Dependency Network. In Proceedings of HLT-NAACL 2003, pp. 252-259. 
