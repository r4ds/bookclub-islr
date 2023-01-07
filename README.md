# R4DS Introduction to Statistical Learning Using R Book Club

Welcome to the R4DS Introduction to Statistical Learning Using R Book Club!

We are working together to read [_Introduction to Statistical Learning Using R_](https://www.statlearning.com) by Gareth James, Daniela Witten, Trevor Hastie, and Rob Tibshirani (Springer Science+Business Media, LLC, part of Springer Nature, copyright 2021, 978-1-0716-1418-1_1).
Join the [#book_club-islr](https://rfordatascience.slack.com/archives/C02CQ93F882) channel on the [R4DS Slack](https://r4ds.io/join) to participate.
As we read, we are producing [notes about the book](https://r4ds.github.io/bookclub-islr/).

## Meeting Schedule

If you would like to present, please see the sign-up sheet for your cohort (linked below, and pinned in the [#book_club-islr](https://rfordatascience.slack.com/archives/C02CQ93F882) channel on Slack)!

- Cohort 1 (started 2021-09-21, ended 2022-05-24): [meeting videos](https://youtube.com/playlist?list=PL3x6DOfs2NGibdB0i2wveuFRDlXHbWaPD)
- Cohort 2 (started 2021-12-02, ended 2022-07-14): [meeting videos](https://youtube.com/playlist?list=PL3x6DOfs2NGhO5S1v53nQzil-OSRZIweH)
- Cohort 3 (started 2022-02-07, ended 2022-09-05): [meeting videos](https://youtube.com/playlist?list=PL3x6DOfs2NGisLSs09v1NQUQaxuE8nbOO)
- Cohort 4 (started 2022-05-01, ended 2022-12-04): [meeting videos](https://youtube.com/playlist?list=PL3x6DOfs2NGi9LAXM5kcyuN_bkN66TzUD)
- [Cohort 5](https://docs.google.com/spreadsheets/d/1QVH6GEusEFUNEsFj3idxGH7XFq8hDC7jFaCWdx0q164/edit#gid=0) (started 2023-01-15): [Sundays, 14:00 CST/CDT](https://www.timeanddate.com/worldclock/converter.html?iso=20230115T200000&p1=24&p2=131&p3=1440) | [meeting videos](https://youtube.com/playlist?list=PL3x6DOfs2NGjbefZellBVB306_z8Wz1Xd)

<hr>


## How to Present

This repository is structured as a [{bookdown}](https://CRAN.R-project.org/package=bookdown) site.
To present, follow these instructions:

Do these steps once:

1. [Setup Git and GitHub to work with RStudio](https://github.com/r4ds/bookclub-setup) (click through for detailed, step-by-step instructions; I recommend checking this out even if you're pretty sure you're all set).
2. `usethis::create_from_github("r4ds/bookclub-islr")` (cleanly creates your own copy of this repository).

Do these steps each time you present another chapter:

1. Open your project for this book.
2. `usethis::pr_init("my-chapter")` (creates a branch for your work, to avoid confusion, making sure that you have the latest changes from other contributors; replace `my-chapter` with a descriptive name, ideally).
3. `devtools::install_dev_deps()` (installs any packages used by the book that you don't already have installed).
4. Edit the appropriate chapter file, if necessary. Use `##` to indicate new slides (new sections).
5. If you use any packages that are not already in the `DESCRIPTION`, add them. You can use `usethis::use_package("myCoolPackage")` to add them quickly!
6. Build the book! ctrl-shift-b (or command-shift-b) will render the full book, or ctrl-shift-k (command-shift-k) to render just your slide. Please do this to make sure it works before you push your changes up to the main repo!
7. Commit your changes (either through the command line or using Rstudio's Git tab).
8. `usethis::pr_push()` (pushes the changes up to github, and opens a "pull request" (PR) to let us know your work is ready).
9. (If we request changes, make them)
10. When your PR has been accepted ("merged"), `usethis::pr_finish()` to close out your branch and prepare your local repository for future work.
11. Now that your local copy is up-to-date with the main repo, you need to update your remote fork. Run `gert::git_push("origin")` or click the `Push` button on the `Git` tab of Rstudio.

When your PR is checked into the main branch, the bookdown site will rebuild, adding your slides to [this site](https://r4ds.io/islr).
