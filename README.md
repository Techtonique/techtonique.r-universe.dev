If you want to install [Techtonique's R packages](https://r-packages.techtonique.net/), do: 

```R
options(repos = c(
                    techtonique = "https://r-packages.techtonique.net",
                    CRAN = "https://cloud.r-project.org"
                ))
                        

install.packages("package_name")
```
