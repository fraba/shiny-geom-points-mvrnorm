# Simulated Multivariate Normal Distribution Shiny App

Shiny app plotting simulation from a multivariate normal distribution with varying means, SDs and correlations.

The app requires these packages:

```{r}
library(shiny)
library(ggplot2)
library(MASS)
```
To install

```{r}
install.packages("shiny")
install.packages("ggplot2")
install.packages("MASS")
```
To run the app
```{r}
shiny::runGitHub("shiny-geom-points-mvrnorm", "fraba")
```
