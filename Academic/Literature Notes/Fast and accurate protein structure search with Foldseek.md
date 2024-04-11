# Main Idea of Thesis

Foldseek has effective use as a "structural searching algorithm" for protein structure matches.

It aligns query proteins structure against database proteins via "description" of tertiary amino acid interactions within proteins

Very computationally efficient compared to Dali, TM-align and CE.

#### [Doc Link](https://www.nature.com/articles/s41587-023-01773-0)

# Details/Quotes

> [!important] Key Feature
> While it performs slightly below Dali, TM-align and CE (according to HOMSTRAD benchmark),
> 
> Other alignment tools may overlook homologous structures that **aren't globally superposable**.
> 
> Foldseek can find ==**homologous multi-domain structures**==, *independent* of ==relative domain orientations==.

Sequence alignment works based on a ==**3Di alphabet**==, which sequences/describes *residue-residue* interactions (more emphasis on tertiary interactions of the prot).

> [!example] 3Di alphabet
> - Tertiary contacts between residues and **spatial** nearest neighbours, ==described==.
> - 
> > [!quote]-




## Related Links

## Related Reading
[[ColabFold making protein folding accessible to all]]


#### Tags: #research #reference #software #proteomics 