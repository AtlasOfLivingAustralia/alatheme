# alatheme

R package storing ALA themes for plots (ggplot2), slides (xaringan) and web apps (shiny/bslib), as well as R Markdown templates for building html files that conform to the ALA style guide.

# Installation

Install the `alatemplates` package
```{r}
if (!requireNamespace("devtools")) install.packages("devtools")
devtools::install_github("AtlasOfLivingAustralia/alatheme")
```

# Using R Markdown templates

To create a new template R markdown file, select **File** --> **New File** --> **New R Markdown** to open the "New R Markdown" pane

In the "New R Markdown" pane, select **From Template** and choose from the list of {alatheme} templates.

The templates to choose from are:

* `rmarkdown-standalone` = A standalone `Rmd` file that renders to html. This is for documents intended to share with others (in webpage style html format), but will not be posted on the ALA Labs website
* `rmarkdown-website-post` = An article intended to be added as a Post on the ALA Labs website. This template uses a `distill` heading to work correctly with the ALA Labs website
  
  *Note: If this template does not render correctly, you may need install the Distill package using* `install.packages("distill")`
