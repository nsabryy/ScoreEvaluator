# ScoreEaluator 
1) **INPUT**: EFO Value, Cohort GT/PT data
2) Use EFO Value to pull relevant scores from [PGSCatalog](https://www.pgscatalog.org/)
3) Use PGSCalc to compute scores. 
4) Run various statistical tests evaluating output distributions (options: KS, ANOVA, Levenes, Bartletts, Anderson-Darling)
5) Use PT data to validate the risk classification of distributions. 
6) Compare 4 & 5. 