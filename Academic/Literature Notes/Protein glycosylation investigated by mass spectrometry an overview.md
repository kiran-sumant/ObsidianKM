# Main Idea of Thesis


#### [Doc Link](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7564411/)

# Details/Quotes
- Glycosylation is post translational modification
- Covalent bonding of oligosaccharide/*glycan* to a polypeptide chain

Glycans are **secondary gene products**

## N-glycans
- Synthesised in [[endoplasmic reticulum]] (see ==oligosaccharyltransferase==)
- Chaperone guided folding occurs

> [!example] Statements
> - N-glycan role and function spans the Eukaryotic domain
> - less complexity in plant N-glycans than in mammals' glycoproteins
> >[!quote] (semi-unrelated) quote
> >The functional role of _N_-glycans dictated from the specific folding of glycoproteins drives the evolutionary changes in the precise signalling of folding control in eukaryotes [[12](https://scholar.google.com/scholar_lookup?journal=Nat.+Rev.+Mol.+Cell+Biol.&title=Glycosylation-directed+quality+control+of+protein+folding&author=C.+Xu&author=D.T.W.+Ng&volume=16&publication_year=2015&pages=742-752&pmid=26465718&doi=10.1038/nrm4073&)]

## O-glycans


> [!example] Statements
> - biosynthesis is ==kingdom-specific==
> 

## Implications
- Immunity and inflammation: ==stimulated t-cells, cytokine release, immune receptors==
- Genetic defects in glycosylation are **often embryonice lethal**
- Changes in protein glycosylation seen at *both beginning and end* of **cancer progression** and **metastasis**.

## Experimentation
- MALDI-MS or LC-MS/MS - using [[CID]], [[ECD]] and [[ETD]]
- **Multiple reaction monitoring** approach w/ **Targeted mass spectrometry** ([[MRM]])
- **High-energy collision dissociation (HCD)**: frag method for peptides with PTMs to provide sequence info and ==localisation of modification sites.==

# [[Glycoscience Mass Spectrometry-Based Methodology]]

## Sample prep

- ==Bottom-up proteomics==
- In-situ/in-solution digestion to relase peptides from proteins, submitted to MS analysis.

> [!statement] Increase in -charge and acidity of modified peptides affects ionisation efficiency.
> It's speculated that MS signals of phosphorylated/glycosylated peptides undergo ==ion suppression== due to competition with more intense Ion currents from non-modified peptides.


> [!success] Overcoming Ionisation efficiency
> - Enzymatic/chemical cleavage of glycans, then purification for MS analysis
> Rudmentarily limited by simple method to single PTM prots
> - Overcome again by ==glycosylation site-specific analysis==
>
> > [!quote]-
> > Thus, the glycan composition can be correctly correlated to the glycosylation site of specific glycopeptides by using this approach referred to as ‘a glycosylation site-specific analysis’. The information obtained in a site-specific manner can be extremely important in correlating glycosylation profiles with specific glycosylation sites, which is useful in understanding structure–function relationships [[92](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7564411/#B92-cells-09-01986),[93](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7564411/#B93-cells-09-01986)].

![[cells-09-01986-g002 1.jpg]]

## Glycopeptide Characterisation via MS

| Technique                 | How it helps                                                                                                                             |
| ------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------- |
| HILIC                     | Affinity Purification technique, to purify glycopeptides for analysis                                                                    |
| Normal Phase              | ^                                                                                                                                        |
| Porous Graphitised Carbon | ^                                                                                                                                        |
| MALDI-MS                  | N-glycan analysis                                                                                                                        |
| nano-LC/MSMS              | analysis of free deglycosylated peptides                                                                                                 |
| [[MALDI-ToF]]             | glycan profile exploration and analysis                                                                                                  |
| [[ECD]]                   | fragmentation method: **ionic resonance instruments** in fourier transform cyclotron                                                     |
| EAD                       | Electron activated dissociation, kinda ECD pt 2.                                                                                         |
| [[ETD]]                   | fragmentation method: perfoemd in **ion trap mass spectrometer**. (==only works best on +3 ions, as more positive the better it works==) |
| [[IM-MS]]                 | Can be used in tandem with [[CID]] for improving glycoform separation                                                                    |


## [[MRM]] targeted mass spec for Glycosylation Quantification

Tools supporting data analysis for high-throughput mass spec results, all follow a conventional pattern:
1. Determine accurate mass from precursor spectra
2. Hypothesize glycan composition and peptide backbone seq from LC-MS/MS spectra
3. Database interrogation to match glycan/peptide backbone to theoretical spectra
4. Data validity score


# Related Links

[Unsupervised machine learning for **exploratory** data analysis in imaging **mass spectrometry**](https://analyticalsciencejournals.onlinelibrary.wiley.com/doi/abs/10.1002/mas.21602)

[**Mass**-**spectrometric exploration** of proteome structure and function](https://idp.nature.com/authorize/casa?redirect_uri=https://www.nature.com/articles/nature19949&casa_token=2cmgt7R3AI8AAAAA:9y54rK4FTSFBYxEokxM6zUpoRhBxX0KcLHPA-QK7tuiYboXcpFOA3HypGqxctm2F_RlOz43ug6-evY5R)

[Conventional-flow liquid chromatography–**mass spectrometry** for **exploratory** bottom-up proteomic analyses](https://pubs.acs.org/doi/abs/10.1021/acs.analchem.8b00525?casa_token=m_UMmPcbNo4AAAAA:rfkQ2-GJRLqP6_5Wt1nFP0u4JJH75bsBEqOXrYYC4105Tp5jc6jXpmWRB3TThhPIpEXCEYcAtTU0zZc)

[Post-translational modifications and **mass spectrometry** detection](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI)

[Discover the post‐translational modification proteome using **mass spectrometry**](https://onlinelibrary.wiley.com/doi/abs/10.1002/cjoc.202000515?casa_token=DDRr73PXckgAAAAA:-AG2zXpbYebTHEB-LRE-wa5mtyibzf5lRUBx7jjq-YlI9ILLG7DkQvq_sQ-DLLSuLI1kFCrB3Yyjrf4)

[**Mass spectrometry**-based candidate substrate and site identification of **PTM** enzymes](https://www.sciencedirect.com/science/article/pii/S016599362300078X?casa_token=IxBAHFAgJYYAAAAA:D3OW1-_eaV-opC18IeAg29ekT_XLPDXfcTKkSFHf8SpEkzmTZPEJJwy0jsINYoz9gkK3mcFt)

[Localization and Quantification of Post-Translational Modifications of Proteins Using Electron Activated Dissociation Fragmentation on a Fast-Acquisition Time-of-Flight **Mass Spectrometer**](https://pubs.acs.org/doi/abs/10.1021/jasms.3c00144?casa_token=FSrZ2lIcPxMAAAAA:WptDQFWiwNZM34clc8Hxfn1crqskfTV0lWNWmtjiltMYg60eruKyTyU5ZuQGcH7DRY0LjFsOweFqwHA)

[Analysis of tandem **mass spectrometry** data with CONGA: Combining Open and Narrow searches with Group-wise Analysis](https://pubs.acs.org/doi/abs/10.1021/acs.jproteome.3c00399?casa_token=woTweMAgutYAAAAA:p__v5OIVqYsVVQ4SRG2OMhgxOQcxqKf-oRWyIK0jj6kdHTpY8GTRhjaUS3S4K__VyS8By4MVe38Pm8I)

[Re-investigating the correctness of decoy-based false **discovery** rate control in proteomics tandem **mass spectrometry**](https://www.biorxiv.org/content/10.1101/2023.06.21.546013.abstract)

## Related Reading

[[Unsupervised machine learning for exploratory data analysis in imaging mass spectrometry]]

[[Mass-spectrometric exploration of proteome structure and function]]

[[Conventional-Flow Liquid Chromatography–Mass Spectrometry for Exploratory Bottom-Up Proteomic Analyses]]

[[Post-translational Modifications and Mass Spectrometry Detection]]

[[Discover the Post-Translational Modification Proteome Using Mass Spectrometry]]

[[Mass spectrometry-based candidate substrate and site identification of PTM enzymes]]

[[Localization and Quantification of Post-Translational Modifications of Proteins Using Electron Activated Dissociation Fragmentation on a Fast-Acquisition Time-of-Flight Mass Spectrometer]]

[[Analysis of Tandem Mass Spectrometry Data with CONGA: Combining Open and Narrow Searches with Group-Wise Analysis]]

[[ Re-investigating the correctness of decoy-based false discovery rate control in proteomics tandem mass spectrometry]]

#### Tags: #research #reference #glycomics #proteomics #mass-spectrometry #PTM #review 