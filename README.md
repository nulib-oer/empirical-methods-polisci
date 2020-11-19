# Empirical Methods in Political Science: An Introduction

![Textbook Build](https://github.com/nulib-oer/empirical-methods-polisci/workflows/Bookdown%20Preview/badge.svg?branch=master)

Bookdown project for Jean Clipperton's textbook. This is the source text for the Political Science 210 textbook: https://nulib-oer.github.io/empirical-methods-polisci/

## Editing the Source

If you're new to Git and R Studio, here is [nice introduction to using these tools together](https://cfss.uchicago.edu/setup/git-with-rstudio/).

Wihtin R Studio, Click on `File` > `New Project` > `Version Control` > `Git`

Copy and Paste this in the `Project URL` field: `https://github.com/nulib-oer/empirical-methods-polisci.git`

This downloads a copy of the `empirical-methods-polisci` project folder and git history to your machine. 

- Install the [Bookdown](https://bookdown.org/) R package from an R Studio R console ([bookdown installation instructions](https://bookdown.org/yihui/bookdown/get-started.html)): `> install.packages('bookdown')`

- If you reload your R studio session or double-click the `empirical-methods-polisci.Rproj` file, the interface will change to include some Bookdown buttons, like `Build Book`.

- You can now edit each individual chapter file and preview the changes locally with Bookdown.

- Steps three and four in [this tutorial](https://cfss.uchicago.edu/setup/git-with-rstudio/#step-3-make-local-changes-save-commit) discuss committing changes to your local git repostory copy and pushing them back up to the GitHub version. 

- Any updates to the `main` branch in GitHub will automatically trigger a new version of the website (takes a few minutes for the update to go live): https://nulib-oer.github.io/empirical-methods-polisci/

## Resources

- [Webinar Introducing Bookdown](https://rstudio.com/resources/webinars/introducing-bookdown/)
