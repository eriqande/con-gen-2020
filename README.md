Con-Gen 2020. Eric C. Anderson’s resources
================

## Tuesday, September 8, 2020

The presentation follows the narrative in the following html document:

  - <https://eriqande.github.io/con-gen-2020/bayes-mcmc-gtyperr-narrative.nb.html>

Within that notebook are links to the Shiny Apps I have written to play
with genotype likelihoods (as well as directions on how to use them). If
you want to get the associated R project, you can download it from Box
at:

  - <https://umt.box.com/s/jdsq97eg2tsse3mw4ig5f3h2ynmdhg74>

or get it directly from GitHub:

  - <https://github.com/eriqande/ngs-genotype-models>

And, *only as a last resort*, if you can’t get the Shiny Apps working in
RStudio on your computer, you can visit their pages on `shinyapps.io`:

  - <https://eriqande.shinyapps.io/ngs-genotype-models/001-allele-freq-estimation.Rmd>
  - <https://eriqande.shinyapps.io/ngs-genotype-models/002-genotype-likelihoods-from-reads.Rmd>

## Monday, Sept. 14, 2020

### Genotyping Errors in RAD data

We will continue with the narrative from the week before, but starting
from estimating genotyping errors from departures from Hardy-Weinberg
equilibrium:

  - <https://eriqande.github.io/con-gen-2020/bayes-mcmc-gtyperr-narrative.nb.html#estimating-genotyping-error-rates-in-some-rad-datasets>

After that short presentation, we will have a break-out room, hands-on
practical session interlude:

#### Hands-on practical with `whoa`

1.  Log on to the RStudio server.
2.  At the R console do:

<!-- end list -->

``` r
library(whoa)
```

  - Then, in the RStudio Help panel (lower right), type `whoa` in the
    text search box and hit return.
  - Click the “Index” link at the bottom of the result.
  - The click the “User guides, package vignettes,…” link.
  - Choose the whoa tutorial and run through it.
  - (Note that this convoluted path to get to the vignette is necessary
    because of a limitation of RStudio Server…)

#### Further whoa fun

In the RStudio terminal from your home directory, do this:

    cp -r instructor_materials/Eric_Anderson/whoa-practical-session ./

Then open the RStudio project inside there and follow the directions in:
`001-whoa-first-steps.Rmd`.

### Amplicon Sequencing and Microhaplotypes

When you need really accurate genotype calls on many individuals,
approaches that yield high read depths at a smaller number of targets
are useful. I will talk about our use of microhaplotypes, following
these slides:

  - <https://eriqande.github.io/con-gen-2020/microhaps.pdf>
