# How to prepare your R environment

To complete most of the assignments you should make sure you have installed required software and R packages.

1. Start by downloading the latest version R: [here](https://cran.r-project.org).
2. The packages we will use require C++ compiler. Depending on your operating system:
- Windows: Install the recommended version of Rtools: [here](https://cran.rstudio.com/bin/windows/Rtools/).
- macOS: Open the Terminal, type `xcode-select --install`, press Install, and follow further instructions.
- Linux: It depends on the distribution, but most likely you have all the tools you need.
3. I strongly recommend to install the latest RStudio: [here](https://rstudio.com/products/rstudio/download/).
4. Open RStudio and install the required packages with this commands:
```
install.packages('tidyverse')
install.packages('emmeans')
install.packages('brms')
install.packages('tidybayes')
install.packages('bayestestR')
```
This list will possibly be extended, but for now these packages should do most of the work.
