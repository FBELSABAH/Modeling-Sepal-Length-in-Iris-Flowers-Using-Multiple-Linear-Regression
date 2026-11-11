# Modeling sepal length in iris flowers

Our five-person team used R’s built-in `iris` dataset to ask whether the relationship between petal length and sepal length varies by species. The report includes exploratory plots, regression diagnostics, and a comparison of two models fitted to 150 flowers.

[Read the illustrated report](https://fbelsabah.github.io/Modeling-Sepal-Length-in-Iris-Flowers-Using-Multiple-Linear-Regression/GroupL_Final_Submission.html) · [Open the R Markdown source](GroupL_Final_Submission.Rmd)

## Result

Adding species-specific slopes gave F(2, 144) = 1.683 and p = 0.1895. The fitted slopes vary, but the sample provides insufficient evidence for a species interaction at the 5% level. The November 2026 portfolio revision corrects the interpretation of Table 4. [Original group submission](https://github.com/FBELSABAH/Modeling-Sepal-Length-in-Iris-Flowers-Using-Multiple-Linear-Regression/tree/9fd400f95b5dc56e8ae717de343555213b36a79c)

## Reproduce the report

Open `GroupL_Final_Submission.Rmd` in RStudio and choose **Knit to HTML**. The data ship with R. To install the report packages and render from the R console, run these commands in the repository directory.

```r
install.packages(c("rmarkdown", "tidyverse", "janitor", "broom", "knitr"))
rmarkdown::render("GroupL_Final_Submission.Rmd")
```
