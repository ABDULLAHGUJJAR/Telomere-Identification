# Telomere-Identification
The Telomere Identification Toolkit (TIDK) is a software package or set of tools designed to analyze and identify telomeres. Telomeres are repetitive DNA sequences found at the ends of chromosomes that play a crucial role in maintaining genome stability and cellular lifespan. TIDK provides researchers with a range of computational methods and algorithms to detect, quantify, and analyze telomeres in various biological samples.

#######################################

conda install -c bioconda tidk

 
#manual string

tidk search --string TTTAGGG --output TTTAGGG --dir TTTAGGG --extension tsv Taxa-C.fasta

tidk search --string TAAACCC --output TAAACCC --dir TAAACCC --extension tsv Taxa-C.fasta


#########################
Plot
#########################

tidk plot  --tsv <tsv> --output <output>
