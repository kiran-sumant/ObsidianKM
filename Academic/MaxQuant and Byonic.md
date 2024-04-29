[[PRM]] vs [[DDA]]

take data to look at in Maxquant, identify ions etc etc

Byonic for data analysis:
- need to state which proteins may be present in sample (with IP products, feed in database for specific proteome)


> [!statement] Checkmark: Add Decoys
> - Decoy matches act as "false proteins" that shouldn't be discovered.
> - Adjusts scoring threshold for peptide cutoffs in order to limit the identification of decoy database proteins, in order to achieve a ==false discovery rate less than 1%==
> - decoy database copies every sequence and puts it in reverse, swaps all arginines with lysines in order to reduce palindrome matches between decoy and original.

==set out mass spec analysis accepted precision to 3ppm (precursor mass tolerance)==

Trypsin digest noted with **RK** to denote both separations via digest and even accounting for missed cleavage.



#mass-spectrometry #analysis #data-science #algorithm