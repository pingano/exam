# Take home exam

## Introduction
the exam will involve characterisation of the let-7 family of microRNAs

the let-7 family is highly conserved across animal species andis often present in multiple copies in a genome

## Characterisation of miRBase



#### Question 1: How many species are there in the current miRBase release?

#### Task: generate an ordered plot (i.e. from lowest to highest) of number of miRNAs / species

#### Question 2: how many **let-7** miRNAs are there in the current release of miRBase 

(you can get all this information from the mature.fa file we have been using in the course)

#### Question 3: what is the current version of miRBase?

#### Task: generate a plot to show which let miRNAs are present in each species. 
For example

![dotplot](images/dot.png)

## Levenshtein Distance
What is the average levenshtein distance for the let-7 miRNAs for each species?

e.g., for human, we have the following let-7 miRNAs

```
>hsa-let-7a-5p
>hsa-let-7a-3p
>hsa-let-7a-2-
>hsa-let-7b-5p
>hsa-let-7b-3p
>hsa-let-7c-5p
>hsa-let-7c-3p
>hsa-let-7d-5p
>hsa-let-7d-3p
>hsa-let-7e-5p
>hsa-let-7e-3p
>hsa-let-7f-5p
```

#### Question 4: what is the average Levenshtein distance among all pairs for human?

#### Task: repeat this for all species and plot


#### Question 5: What is the levenshtein distance for each let-7 miRNA across all species?

for example, let-7a is present in 121 species, what is the average Levenshtein distance among all pairs?

#### task: repeat for all let-7 miRNAs and plot

## Other points
Ideally, you should submit your work through Github (just send me a link to your results)

Your submitted work should consist of your code, your data files and your report should (ideally) be submitted in Markdown

Plots should be generated in Matplotlib, Seaborn or plotnine. 

You can work together, but you should submit your original work and say who you were working with

##submission date May 31st 2023
 

