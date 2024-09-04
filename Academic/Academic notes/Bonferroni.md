Bonferroni test helps **adjust** test parameters that help prevent ==incorrect statistical significance== by identifying and ==reducing the instances== of, **false positives**.

> [!info] Definition of the ==Bonferroni adjustment/correction==:
> "the p-value of each test **must be equal to** $\frac{\alpha}{n}$ , where $n$ is the ==number of tests performed.=="

A **series of t-tests** is performed on each pair of groups. 

It's limited by bring conservative, as it risks failing to identify findings of significance within its parameters.
==Basically it overcorrects for [[Type 1 errors]], disregarding [[Type 2 errors]], despite the latter error rate being relatively high for ANOVA.==

should I use this? - ![[ANOVA#^faa453]]
#definition #data-science #analysis #statistics #post-hoc