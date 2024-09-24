Tukey Test/procedure,  gives an ==Honest Significant Difference==, based on a **studentised range distribution.** The test compares **all possible pairs** of means.

ANOVA gives ==MSE==; MS error.

**[[q-value]]** is determined by the ==Q Table== using $k$ and $df$, which are number of groups and degrees of freedom, respectively.

> [!info] Tukey Statistic
> $T = q   \times \sqrt \frac{MSE}{n}$, where $n$ is the **number of items** in **one sample**
> 
> If ==$T \geq   \mid  \bar{x_{1}} - \bar{x_{2}}  \mid$==, the means are *significantly different*.

[[]]

should I use this? - ![[ANOVA#Post-Hoc analysis comparisons]]

> [!attention] Note
> Unequal sample sizes can use a modified version of the Tukey HSD called the **Tukey-Cramer method.** This factors in the estimated **sd** per pairwise comparison.

#definition #data-science #analysis #statistics #post-hoc