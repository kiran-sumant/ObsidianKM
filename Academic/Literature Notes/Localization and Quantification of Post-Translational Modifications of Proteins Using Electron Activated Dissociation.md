# Main Idea of Thesis

PTMs are "diverse, dynamic and cruicial to large variety of cellular processes and signalling".

PTM analysis remains challenging in 2023 due to potential low PTM stoichiometry, neutral loss, multiple PTMs per proteolytic peptide.

CID is commonly used, but results in ==neutral loss== and ==incomplete peptide sequencing==.

Article focuses on [[EAD]] for PTM characterisation, site localisaiton, and peptide quantification.

Uses PRM for final analyses.

Finds "electron-based fragmentation preserves the malonyl group from neutral losses" where malonyl is a highly labile PTM.

Demonstrates high reproducability, quantification accuracy and stronger peptide sequence coverage.



#### Doc Link: [Localization and Quantification of Post-Translational Modifications of Proteins Using Electron Activated Dissociation Fragmentation on a Fast-Acquisition Time-of-Flight **Mass Spectrometer**](https://pubs.acs.org/doi/abs/10.1021/jasms.3c00144?casa_token=FSrZ2lIcPxMAAAAA:WptDQFWiwNZM34clc8Hxfn1crqskfTV0lWNWmtjiltMYg60eruKyTyU5ZuQGcH7DRY0LjFsOweFqwHA)


# Details/Quotes

![[Pasted image 20240610123145.png]]

> [!statement] Introduction
> EAD fragmentation on a quadrupole-time-of-flight [[Q-ToF]] Mass spec, analysing peptides with following PTMs: malonyl, succinyl, double malonyl acetyl, phosphate. 
> Peptides are **identified**, PTM sites are **localised and quantified**. Results derived from ==PRM method==. 
> >[!quote]-
> >In this study, we present a first proof-of-concept of EAD fragmentation performed on a novel QqTOF mass spectrometer to analyze malonylated, succinylated, doubly malonylated-acetylated, and phosphorylated peptides. We assessed the performances of EAD versus CID to confidently and accurately identify, site localize, and quantify PTMs using the same MS platform to limit the varying factors to the fragmentation type. We analyzed a series of biologically relevant synthetic modified peptides using targeted parallel reaction monitoring (PRM or MRMHR) assays (32) performed on a QqTOF system ([Figure 1](https://pubs.acs.org/doi/full/10.1021/jasms.3c00144?casa_token=FSrZ2lIcPxMAAAAA%3AWptDQFWiwNZM34clc8Hxfn1crqskfTV0lWNWmtjiltMYg60eruKyTyU5ZuQGcH7DRY0LjFsOweFqwHA#fig1)). We explored a range of EAD KE values to determine optimal values, which keep labile modifications intact and provide comprehensive peptide fragmentation coverage, that generates strong PTM site-localizing ions, with a particular focus on malonylation and phosphorylation. We also investigated the capabilities of the trap-and-release technology to increase sensitivity when combined with EAD fragmentation.

ZenoTOF 7600 mentioned!!!!!!!!!!!! REEEEEEEEEEEEE


| What is Investigated                                    | How it's Investigated                                                                                                                                 | Result                                                                                                                                                                                                             |
| ------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| Preservation of Labile PTMs and Neutral Loss mitigation | Used a ==synthetic malonylated peptide==, position known at K-192, compared analysis between **EAD-PRM** and **CID PRM**                              | ==EAD== did **not** have significant neutral loss ***->*** **confident PTM site ID**. CID though sig **loss CO2** ***->*** malonyl decarboxylation ***->*** **mistakes malonyl for acetyl** (malonyl-44m/z)        |
| Optimisation of EAD fragmentation                       | Malonyl peptide fragmentation performed with KE ranging 0-11 eV.                                                                                      | KE 5 eV showed most strongest **intact PTM intensity** of site-spectific ions, with minimal noise. over **8 eV showed CO2 neutral loss** from malonyl.                                                             |
| Quantification of Phosphopeptide Isomers                | Used two isomeric phosphopeptides with different phosphate locations (S-56 and S-59)                                                                  | Optimal KE 2 eV, "created high-intensity and intact differentiating PTM-containing fragment ions". ==c-ions== provided **direct evidence**. Near complete series for both peptides, but abundance was low for CID. |
| Accurate Quantification; Targeteed EAD PRM Assay        | Doubly malonylated-acetylated peptide ==isoforms== of human **histone H2B type-1**, M1 and M2. ==Mix ratios== for **M1:M2**- 0:4, 1:3, 2:2, 3:1, 4:0. | ==EAD== estimates ratios fairly close to initial values. CID PRM has neutral loss -> quantifying primarily the acetyl group. CID ratios were way off, only M1 identified at 99:1.                                  |
|                                                         |                                                                                                                                                       |                                                                                                                                                                                                                    |

> [!info] Note
> While [[EAD]] can tune electron kinetic energy, [[ETD]] ==does not and can not==. Speaks to versatility.


> [!info] Note for CID
> When **PTM site** is ==closer== to the ==C-terminus== (higher residue number), there are ==less peptides available== to identify and locate the PTM site. as **y-ions are the only ions with reliable info** in **CID** -> PTM closer to C-terminus more difficult to detect with confidence. 




## Related Links

## Related Reading



#### Tags: #research #reference 