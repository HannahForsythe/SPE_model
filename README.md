# What is in this project

This is a set of models that capture children's Subject Pronoun Expression (SPE) in Spanish. 

- The *Optimal model* assumes children in mono-dialectal and contact situations accurately learn and deploy priors and likelihoods to determine the posterior probability of overt or null SPE given the pronoun's reference P(pronoun|reference). The R notebook for this model is `optimal-draft2.Rmd`

- The *Noisy priors* model assumes that children in both situations accurately learn the priors and likelihoods but probabilistically fail to include the prior when calculating the posterior P(pronoun|reference). Th R notebook for this model is `noisy_prior-draft1.Rmd` THIS ONE IS NOT DONE YET.

# How to view the notebooks

R notebooks (.Rmd files) are not displayed well in Github, so I created a few different options. 

### Option I: Word doc
Download the .docx version of a given model to open it in word.


### Option II: Open R notebook in R Studio (prettiest looking option)


Download the .Rmd file and knit it to HTML in R in order to view the notebook as it is designed to be viewed.:

1. Make sure that you haveinstalled the `knitr` package in R (use the package installer or run `install.packages("knitr")` in the console). Once installed, `knitr` should add a button to the top of the coding pane.

[knitr button]("knitr_button.png")


2. Download the .Rmd file and the source dataset that it uses `aduchi.csv`; store them in the same location.

3. Open the .Rmd file in RStudio. Click Knit > Knit to HTML 

4. `knitr` will exectue all the code in the the .Rmd notebook and then convert the output into a pretty-looking html document.

### Option III: Just look at the Jupyter notebook (.ipynb)

The .ipynb file displays fine right here in GitHub--you just can't see any of the output tables or figures because I haven't yet figured out how to actually execute it. 

