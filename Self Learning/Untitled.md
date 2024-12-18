# A few warnings before downloading:

- Recommended minimum RAM: 16 GB (the bigger the better)
- You will need to install all dependables via conda please download [Anaconda](https://www.anaconda.com/download) or Conda-mini before running this program.
- Ideally run the script on [VScode](https://code.visualstudio.com/docs/setup/windows), as that is where I wrote and tested it, so I have ample knowledge of all the ways it can possibly go wrong in VScode specifically

# Details
The Encyclopaedia of Domains (TED) database is a database created using "deep learning-based domain parsing and structure comparison algorithms to segment and classify domains" 
On proteins in the AlphaFold database. Domains from the TED database can be used to construct a local database to classify queried domains against TED domains in order to determine structural homology and relations via classification.

 >[!quote]
We uncover over 10, 000 previously unseen structural interactions between superfamilies, expand domain coverage to over 1 million taxa, and unveil thousands of architectures and folds across the unexplored continuum of protein fold space. We expect TED to be a valuable resource that provides a functional interface to the AFDB, empowering it to be useful for a multitude of downstream analyses.

[Merizo search](https://www.biorxiv.org/content/10.1101/2024.03.25.586696v2.full) and Foldclass can make use of databases constructed using data from the TED database for homology detection and detecting "per-domain similarities for complete chains". The efficacy of similar programs such as Foldseek

- The script is run from the file 