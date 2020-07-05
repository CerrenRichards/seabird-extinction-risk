# seabird-extinction-risk

This repository contains the data and R code required to replicate the analyses in **Richards, C., Cooke, R.S.C. & Bates, A.E. - Biological traits of seabirds predict extinction risk and vulnerability to anthropogenic threats.**


## Scripts
`seabird-extinction-risk.Rmd` The R Markdown file that contains the code for the analysis.

**Contents:**
1. Trait imputations
2. Averaging the 15 trait datasets
3. Extracting IUCN categories
4. Define species as globally and non-threatened
5. Mixed data PCA
    - Plot the PCA mixed data output
    - Plot the PCA mixed data trait coordinates
6. Individual trait distributions
    - Continuous Trait Distributions
    - Categorical Trait Distributions
    - Differences in globally and non-threatened traits
7. Unique trait combination (UTCs)
    - Bin continuous traits to small, medium and large
    - Calculate UTCs
    - Make the UTC plots
8. Importing IUCN threat data
9. SIMPER analysis
    - Create SIMPER table


## Data
`281_sb_traits.csv` Non-imputed trait data for 281 seabird species.

`341_sb_traits.csv` Imputed and averaged trait dataset for 341 seabird species.


### Contact
Any queries can be directed to **Cerren Richards** cerrenrichards@gmail.com
