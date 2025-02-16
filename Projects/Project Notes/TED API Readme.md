# A few warnings before downloading:

- Recommended minimum RAM: 16 GB (the bigger the better)
- You will need to install all dependables via conda please download [Anaconda](https://www.anaconda.com/download) or Conda-mini before running this program.
- Ideally run the script on [VScode](https://code.visualstudio.com/docs/setup/windows), as that is where I wrote and tested it, so I have ample knowledge of all the ways it can possibly go wrong in VScode specifically
- ==DO NOT RUN JSON FILES LARGER THAN 1GB,== it will crash your computer due to the artifacts generated to run the code, and you will risk corrupting your hard drive. 
- For larger .json file sizes (aka larger desired protein databases) I recommend dividing the data you wish to run into chunks that are <1GB.

# Details
[The Encyclopaedia of Domains](https://www.science.org/doi/10.1126/science.adq4946) (TED) database is a database created using "deep learning-based domain parsing and structure comparison algorithms to segment and classify domains" 
On proteins in the AlphaFold database. Domains from the TED database can be used to construct a local database to classify queried domains against TED domains in order to determine structural homology and relations via classification.

 >[!quote]
We uncover over 10, 000 previously unseen structural interactions between superfamilies, expand domain coverage to over 1 million taxa, and unveil thousands of architectures and folds across the unexplored continuum of protein fold space. We expect TED to be a valuable resource that provides a functional interface to the AFDB, empowering it to be useful for a multitude of downstream analyses.

[Merizo search](https://www.biorxiv.org/content/10.1101/2024.03.25.586696v2.full) and Foldclass can make use of databases constructed using data from the TED database for homology detection and detecting "per-domain similarities for complete chains". 

I created this script to generate a folder of pdb. files downloaded from the TED API, to generate a database for running on a local computer, according to input data downloaded from UniProt (as an example, I used the SwissProt *homo sapiens* proteins as I wish to conduct a homology search across the human proteome for specific protein domains).

# Instructions
1. Use [UniProtKB](https://www.uniprot.org/uniprotkb?query=*) to create a desired set of proteins, and narrow down the desired database to the proteins you wish to query that belong to the same species/ are reviewed/ have specific scores or sequence lengths, depending on your aims for searching. 
2. Open the download sidebar, and choose the "JSON" from the format dropdown menu. Then, click the download button.
3. Once downloaded, copy the location address of the .json file and the address of the folder you wish the script to populate with .pdb files.
4. The script is run from the file script_TED_files.py. Run this file only. 
5. In the terminal, you will be greeted by the following prompts in succession:
```
Please state the address of Uniprot-downloaded json file for accession ID extraction:
Please state the address of an EXISTING root folder for writing in the pdb file database:
```
6. Paste the previously copied addresses in for each prompt and click enter after submitting the address for each one. The addresses should not be within quotation marks. 
7. If the json file address is incorrect the script will not run. If the folder file address is not correct the script will dump files into a folder created in the working directory called "ted_output"
8. Once it is run, you should see all the .pdb files have populated the folder. If you cannot open the files, please restart your computer once and try again. 
9. Additionally, a file called "null_ted_proteins.txt" will be generated, containing the proteins from your json file where the accession ID of the protein generated a 404 error as no domains have been generated on the TED database. This contains proteins that are either longer than a certain size set by DeepMind for distribution; or in the case of shorter sequences, the presence of missing/non-standard residues.

If you have any further questions, please raise them in the Issues section.