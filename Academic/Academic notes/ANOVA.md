# Analysis of Variances

**Single, continuous dependent variable**,
==+==
**Multi-level categorical independent variables**

Outcome variable is expressed as a function of explanatory variables.

[Willliams et al. (2010)](https://personal.utdallas.edu/~Herve/abdi-PostHoc2010-pretty.pdf) calls it an **F-test** and *omnibus test*. 

# Types
1. One-way ANOVA
2. Two-way ANOVA
3. Repeated Measures ANOVA

# Code: [[R Code assorted templates#ANOVA|Templates]]
# Post-Hoc Analyses

- **[[Bonferroni]]**
- **[[Tukey's HSD]]**
- **[[Scheffe]]**

> [!info] Assumed for the base version of all tests:
> - **Independence** between and within groups, 
> - All groups are ==normally distributed==,
> - Variance is ==homogeneous==

## Post-Hoc analysis comparisons

| Analysis           | Data suitability                                                                                |
| ------------------ | ----------------------------------------------------------------------------------------------- |
| Bonferroni         | **Set number of comparisons**                                                                   |
| Tukey's HSD        | **Individual pairwise** comparisons, best for ==equal sample sizes==                            |
| Scheffe            | **All possible simple** and complex mean comparisons; ==highly conservative, largest CI==       |
| Duncan's MRT       | Generates **q values** for identifying all **mean pairs** that are **statistically different.** |
| Fisher's LSD       | Like MRT, but generates                                                                         |
| Newman-Keuls       |                                                                                                 |
| Rodger             |                                                                                                 |
| Dunnett            |                                                                                                 |
| Benjamini-Hichberg |                                                                                                 |

## Post-Hoc decision flow
![[Pasted image 20240906162039.png]]

Alternative to ANOVA is **[[Kruskal-Wallis]]**, a **[[Non-parametric]]** analysis.

#definition #analysis #data-science #statistics 
