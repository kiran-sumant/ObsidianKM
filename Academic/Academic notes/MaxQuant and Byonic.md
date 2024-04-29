[[PRM]] vs [[DDA]]

take data to look at in Maxquant, identify ions etc etc

Byonic for data analysis:
- need to state which proteins may be present in sample (with IP products, feed in database for specific proteome)


> [!statement] Checkmark: Add Decoys
> - Decoy matches act as "false proteins" that shouldn't be discovered.
> - Adjusts scoring threshold for peptide cutoffs in order to limit the identification of decoy database proteins, in order to achieve a ==false discovery rate of 2%==
> - decoy database copies every sequence and puts it in reverse, swaps all arginines with lysines in order to reduce palindrome matches between decoy and original.

==set out mass spec analysis accepted precision to 3ppm (precursor mass tolerance)==

Trypsin digest noted with **RK** to denote both separations via digest and even accounting for missed cleavage.

CAA has CAT; alkylated, 99% efficient at **carbamidomethylation**.

also add Variable modifications:
- Oxidation
- Deamidation

Byonic can run to generate a **new database** (FASTA file format) based on running the data to assemble to figure out what proteins are in the sample as per the data obtained from MaxQuant.

Second we use the new database created to create a second, more efficient search to query the new data with, ==this time searching for our desired PTM targets noted/stated==. (found in temp folder under your id, KM_EXP numero xyz)

BYRSLT file is the best for looking at an interactible list of all proteins discovered in your sample.
Make a list of all glycans you're gonna be searching for, seen in EMI suite under




#mass-spectrometry #analysis #data-science #algorithm