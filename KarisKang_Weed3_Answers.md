Problem Set 1
Due 2/15/2023

Instructions

## Problems

1. Let's imagine a 5 bp section of a genome, and that there is a SNP (A/G) in basepair 3.  Assume that we are genotyping **one** heterozygous individual (50% chance of sequencing either allele).  Please calculate the probability for the following sequencing reads:
    
    **Set 1**
    
    ```
    AAATG
    AAATG
    AAATG
    ```
Answer: 0.125 probability 

    **Set 2**

    ```
    AAATG
    AAATG
    AAATG
    AAATG
    AAATG
    ```
Answer: 0.03125 probability 

    **Set 3**

    ```
    AAATG
    AAGTG
    AAATG
    AAATG
    AAATG
    ```
Answer: 0.03125 probability 

2. Way back in old 1993, Spitze reported the following number of genotypes at the *PGI* allozyme locus in the *Daphnia* population in Nothing Pond:

|Genotype|Count|
|--------|-----|
|*SS*| 11|
|*SS-*|55|
|*S-S-*|61|

    A. What are the observed genotype and allele frequencies? 
    Genotype frequencies: 
    |Genotype|Frequency| 
    |--------| ----|
    |SS| 0.0866|
    |SS-| 0.433|
    |S-S-| 0.4803| 
    
    |Allele|Frequency|
    |---|---| 
    |S|0.303|
    |S-|0.697|
    B. Given the observed allele frequencies, what are the genotypic frequencies expected under Hardy-Weinberg?  Using a chi-square test, how well do the observed genotype frequences agree with the HWE expecations?
    |Genotype|Expected Genomic Frequency|Observed Genomic Frequency|
    |---|---|---|
    |SS| 0.091809| 0.0866| 
    |SS-|0.422382| 0.433|
    |S-S-|0.4803| 0.485809|
    
    Chi-squared = 0.999685
    Expectations and observations not statistically different
    
    C. What is the observed heterozygosity in this population and what is the expected heterozygosity?
    Ho = 0.4331
    He = 0.422382

3.  Let's imagine another small population with the following genotype counts at a single SNP:
  
  |Genotype|Count|
  |--------|-----|
  |A/A|0|
  |A/G|10|
  |GG|0|
  
  A. What are the observed genotype and allele frequencies? 
  |Genotype|Frequency|
  |---|---| 
  |A/A|0| 
  |A/G|1|
  |G/G|0| 
  
  |Allele|Frequency|
  |---|---| 
  |A|0.5|
  |G|0.5| 
  B. Given the observed allele frequencies, what are the genotypic frequencies expected under Hardy-Weinberg?  Using a chi-square test, how well do the observed genotype frequences agree with the HWE expecations?
  
  C. Simulate one generation of random mating (you don't need to code this simulation; it can be by hand):
        * Pair off the ten indivduals into mating pairs
        * Randomly pick two expected offspring genotypes per pair (10 offspring genotypes)
        * Create a new genotype table from the offsrping only (should only be 10 genotypes)
        * Repeat subqestions A and B on the new genotype table

4.  Take a look at Gel C below:

![img](./img/February%209%2C%202023/IMG_0524.jpeg)

Gel C is the banding pattern from two AFLP markers (the upper and lower sets of bands).
    
    A. Estimate the frequency (q) of the null allele of each of the two AFLP markers assuming HWE.
    
    B. Estimate the percentage of *band-present* individuals (not the overall frequencies) that are heterozygous at each of the two markers.  What biological principle does the difference between these two percentages illustrate?

