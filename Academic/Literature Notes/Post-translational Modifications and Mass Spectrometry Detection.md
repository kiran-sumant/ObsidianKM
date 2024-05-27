# Main Idea of Thesis

Another Lit review BRUHH

- Principles of mass spec and **peptide enrichment strategies**
- Analysed all PTM data in UniProt as of 2013
- Analysed evolution of data
- in depth analysis for articles 2010-2012 reporting PTM detection via MS.

#### Doc Link: [Post-translational modifications and **mass spectrometry** detection](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI)


# Details/Quotes

> [!statement] The History
> 2D Gel electrophoresis is considered the "Early application of proteomics"
> 
> Now proteomics uses many techs including NMR, Fourier transform infrarred spectrpscopy, array experiments, chip experiments, and most essentially, Mass Spectrometry.
> 
> 
> >[!quote]
> >“[[Proteomics]] includes not only the **identification and quantification** of proteins, but also the **determination** of their ==localization==, ==modifications, interactions, activities==, and, ultimately, their **function**” [10]([https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib10](https://www.science.org/doi/full/10.1126/science.291.5507.1221))


> [!quote]
> Tandem mass spectrometers have the additional capability of selecting an ion and fragmenting it in order to obtain structural information (MS/MS).

> [!example] Soft ionization techniques
> - Helps analyze unstable compounds that react with aggressive ionisation techniques. 
> - Electro-spray ionisation ([[ESI]]) and matrix-assisted laser desorption/ionization ([[MALDI-ToF|MALDI]])
> - ESI favours hydrophobic peptides  [22](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib22), [23](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib23), MALDI favours basic and aromatic peptides  [22](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib22), [24](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib24), [25](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib25)
> 
> >[!quote]-
> >capable of ionizing non-volatile and thermo-unstable biological compounds, namely [electrospray ionization](https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/electrospray-ionization "Learn more about electrospray ionization from ScienceDirect's AI-generated Topic Pages") (ESI) [17](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib17) and matrix-assisted laser desorption/ionization (MALDI)
> 
> &emsp;
> >[!warning] Issues with soft Ionisation techniques
> > - Ion suppression; occurs due to **cross-talk** from sample matrix, co-eluting compounds and contaminants that interact with ions.
> > - Has ==deletorious effects==.
> > - "Nevertheless, nowadays most proteomics experimental approaches include a sample pre-fractionation step for peptide separation, with the aim of maximizing sensitivity."

> [!statement] Things to Consider for PTM detection
> 1. Speed of aquisition
> 2. Resolving power
> 3. mass accuracy
> 4. sensitivity
> 5. dynamic range
> 6. methods of fragmentation
> 7. available software packages
> 
> >[!quote]-
> >Nevertheless, it is now considered that high resolving power and mass accuracy are essential for proteomics and PTM analysis [43](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib43), [44](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib44). This limits the instruments to three principal [tandem mass spectrometry](https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/tandem-mass-spectrometry "Learn more about tandem mass spectrometry from ScienceDirect's AI-generated Topic Pages") platforms: quadrupole time-of-flight (QqTOF), time-of-flight/time-of-flight (TOF/TOF) and ion trap/orbitrap (IT/orbitrap) mass spectrometers.

> [!statement] PTM discovery with Fragmentation
> - [[CID]] is the main method of dissociation used to fragment molecules in mass spec.
> - However peptides containing multiple PTMs with **have different fragmentation pathways** compared to unmodded peptides.
> - Many essential PTMs are ==labile==, so are the first removed during dissociation using CID, -> **[[neutral loss]]**.
> - [[ECD]] improves the analysis of "sulfated [58], glycosylated [59] and phosphorylated [60] peptides."
> - [[ETD]] induces fragmentation via electron transfer to **multiply protonated peptides.
> 
> >[!quote]-
> >Similarly to ECD, the neutral loss of labile PTMs is not the preferred fragmentation pathway (reviewed in [63]), particularly in phosphorylated and glycated peptides [64]. Several studies have shown that there is little overlap in peptide identifications between ETD and CID.

> [!example] Data analysis for PTM detection
> - (High-throughput) gives access to **simultaneous identification** of 1000s of ==modded peptides==
> - Workflow tasks include: **data processing, analysis, presentation**.
> - (*unless using targetred approach*) Usuallt **all PTM/peptide/residue* mass shifts** are searched for reach identified peptide in a protein database; ==computationally heavy==.
> - [[consensus sequence|Consensus sequence]] or consensus-based approaches are among approaches used to search fo PTM sites, by scanning a query protein sequence aga8inst observed protein signatures. **However**, consensus seq presence ==does not immediately imply== PTM presence. 
> 
> > [!quote]-
> > "Unless targeted approaches are used, the characterization of PTMs using MS/MS data involves exhaustive searches of all potential combinations of mass shift for each identified peptide from a [protein database](https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/protein-database "Learn more about protein database from ScienceDirect's AI-generated Topic Pages") [102](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib102), [103](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib103),[104](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib104)."
> > 
> > "Other approaches use consensus-based approaches, combining several signature recognition methods to scan a given query protein sequence against observed protein signatures [104](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib104)."

> [!quote] 
> "Advances in proteomics offer much to biological discovery. However, the realization of the full potential of technological advances will require concurrent intensive efforts on the computational front."
> > [!summary]- Reference
> > [Data analysis—the Achilles heel of proteomics](https://www.nature.com/articles/nbt0303-221)
> > *Patterson, S. D. (2003). Data analysis—the Achilles heel of proteomics. _Nature biotechnology_, _21_(3), 221-222.*

> [!example] Chemical Proteomics for PTM Analysis
> - Sample complexity in bottom-down proteomics results in less PTM detection.
> - Thus ==peptide enrichment methods== are required to **reduce complexity**.
> - enrichment methods are usually **selective** for indentification and quantification of PTMs.
> 
> >[!quote]-
> >Depending on the purpose of the enrichment technique, two main approaches have been used ([Fig. 1](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#f0005)): enrichment at the protein level, or enrichment at the peptide level after digestion of whole [protein lysates](https://www.sciencedirect.com/topics/medicine-and-dentistry/protein-hydrolysate "Learn more about protein lysates from ScienceDirect's AI-generated Topic Pages") with [proteases](https://www.sciencedirect.com/topics/medicine-and-dentistry/proteinase "Learn more about proteases from ScienceDirect's AI-generated Topic Pages").

## [[glycosylation|Glycosylation]]

- One of most complex PTMs
- Plays roles in **protein stability, folding, solubility**
- Instrumental in some **Cell process modulation** (e.g- ==cell adhesion, differentiation==)


> [!important] Glycosylation in Physiological States
> - Interrelation is still poorly understood.
> - Currently in the process of ==glycoprotein and glycopeptide characterisation==.
> - In this case, Physiological state refers to **internal** and **external** changes of the environment that affect the internal biochemistry of an organism/ cell system.
> 
> >[!quote]-
> > the underlying interrelation between this PTM and [physiological states](https://www.sciencedirect.com/topics/medicine-and-dentistry/physiological-state "Learn more about physiological states from ScienceDirect's AI-generated Topic Pages") is still poorly understood and extensive research aimed at glycoprotein/glycopeptide characterization has been conducted, mainly with the aid of MS methodologies [144](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib144), [145](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib145), [146](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib146), [147](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib147).


| N-glycosylation                                                                                           | O-glycosylation                                                                                                |
| --------------------------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------- |
| Sugar molecule is covalently attached to the **nitrogen atom** of an ==asparagine residue==               | Sugar molecule is covalently attached to the **oxygen atom** of a ==serine== or ==threonine== residue          |
| Process usually happens in the ==ER== and ==Golgi apparatus==.                                            | Process occurs mostly within the ==Golgi apparatus== (FUT10 and FUT11 excluded)                                |
| Sugar core stucture is ==high mannose core==                                                              | More diverse core stuctures seen (core 1,2,3)                                                                  |
| Protein can exhibit **multiple glycan structures**                                                        | Usually only a **single sugar residue added** to the ==AA residue==                                            |
| β-1,4 glycosidic bond                                                                                     | α-O-glycosidic bond                                                                                            |
| ==Co-translational Modification==, occurs **during protein synth**                                        | ==Post-translational Modification==, occurs **after protein synth** and sometimes even *after protein folding* |
| Functions usually for protein ==localisation== and ==secretion==. also immunogenicity and immune response | Involved in inter-cellular interactions, ==signal transduction== and sometimes in response to viral infection. |
| Analysis based on **hydrazide chemistry**                                                                 | Largely utilises **lectins** for characterisation, bound to sepharose, agarose etc.                            |


> [!quote]- Quote(s)
> - "For the analysis of N-glycoproteins, most of the enrichment procedures are based on [hydrazide](https://www.sciencedirect.com/topics/medicine-and-dentistry/hydrazide "Learn more about hydrazide from ScienceDirect's AI-generated Topic Pages") chemistry, involving oxidation of the carbohydrates in glycoproteins that allows their subsequent immobilization onto a hydrazide-activated resin, followed by the release of glycopeptides with Peptide -N-Glycosidase F (PNGase F) [148](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib148)."
> <br>
> - "For the characterization of O-glycoproteins, [lectins](https://www.sciencedirect.com/topics/medicine-and-dentistry/lectin "Learn more about lectins from ScienceDirect's AI-generated Topic Pages") have been largely exploited [152](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib152). Lectins are proteins or glycoproteins ubiquitously found in nature that bind reversibly to specific glycan structures. Most [lectins](https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/lectin "Learn more about lectins from ScienceDirect's AI-generated Topic Pages") interact exclusively with the terminal non-reducing [position](https://www.sciencedirect.com/topics/biochemistry-genetics-and-molecular-biology/position "Learn more about position from ScienceDirect's AI-generated Topic Pages") in an [oligosaccharide](https://www.sciencedirect.com/topics/medicine-and-dentistry/oligosaccharide "Learn more about oligosaccharide from ScienceDirect's AI-generated Topic Pages"), but some, such as [Concanavalin A](https://www.sciencedirect.com/topics/medicine-and-dentistry/concanavalin-a "Learn more about Concanavalin A from ScienceDirect's AI-generated Topic Pages") (ConA) and [wheat germ agglutinin](https://www.sciencedirect.com/topics/medicine-and-dentistry/wheat-germ-agglutinin "Learn more about wheat germ agglutinin from ScienceDirect's AI-generated Topic Pages") (WGA), bind to internal sugars [153](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib153), [154](https://www.sciencedirect.com/science/article/pii/S089158491300587X?casa_token=Ex3_B9syPoUAAAAA:5UB5T-5fddnUqjoK87fSncyZkz_o63vWzHbsg7micJ5ycmj5meaGtNoTy9PXJnfzHeyGA4dI#bib154)."


In the case of glycosylation PTMs, ==enrichment method== is **highly dependent** on the ==type of glycan being studied.==



## Related Links

## Related Reading



#### Tags: #research #reference 