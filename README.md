# R4DS Introduction to Statistical Learning Using R Book Club

Welcome to the R4DS Introduction to Statistical Learning Using R Book Club!

We are working together to read [_Introduction to Statistical Learning Using R_](https://www.statlearning.com) by Gareth James, Daniela Witten, Trevor Hastie, and Rob Tibshirani (Springer Science+Business Media, LLC, part of Springer Nature, copyright 2021, 978-1-0716-1418-1_1).
Join the [#book_club-islr](https://rfordatascience.slack.com/archives/C02CQ93F882) channel on the [R4DS Slack](https://r4ds.io/join) to participate.
As we read, we are producing [notes about the book](https://r4ds.github.io/bookclub-islr/).

## Meeting Schedule

If you would like to present, please see the sign-up sheet for your cohort pinned in the [#book_club-islr](https://rfordatascience.slack.com/archives/C02CQ93F882) channel on Slack!

- Cohort 1: (started 2021-09-21, ended 2022-05-24) - Tuesdays, 9:00am CST/CDT
- Cohort 2: (started 2021-12-02) - [Thursdays, 10:00am CST/CDT](https://www.timeanddate.com/worldclock/converter.html?iso=20211202T160000&p1=24)
- Cohort 3: (started 2022-02-07) - [Mondays, 9:00am CST/CDT](https://www.timeanddate.com/worldclock/converter.html?iso=20220207T150000&p1=24)
- Cohort 4: (started 2022-05-01) - [Sundays, 3:00pm CST/CDT](https://www.timeanddate.com/worldclock/converter.html?iso=20220501T200000&p1=24&p2=179)

<hr>


## How to Present

This repository is structured as a [{bookdown}](https://CRAN.R-project.org/package=bookdown) site.
To present, follow these instructions:

1. [Setup Github Locally](https://www.youtube.com/watch?v=hNUNPkoledI) (also see [_Happy Git and GitHub for the useR_](https://happygitwithr.com/github-acct.html))
2. Install {usethis} `install.packages("usethis")`
3. `usethis::create_from_github("r4ds/bookclub-islr")` (cleanly creates your own copy of this repository).
4. `usethis::pr_init("my-chapter")` (creates a branch for your work, to avoid confusion).
5. Edit the appropriate chapter file, if necessary. Use `##` to indicate new slides (new sections).
7. If you use any packages that are not already in the `DESCRIPTION`, add them. You can use `usethis::use_package("myCoolPackage")` to add them quickly!
8. Build the book! ctrl-shift-b (or command-shift-b) will render the full book, or ctrl-shift-k (command-shift-k) to render just your slide. Please do this to make sure it works before you push your changes up to the main repo!
9. Commit your changes (either through the command line or using Rstudio's Git tab).
10. `usethis::pr_push()` (pushes the changes up to github, and opens a "pull request" (PR) to let us know your work is ready).
11. (If we request changes, make them)
12. When your PR has been accepted ("merged"), `usethis::pr_finish()` to close out your branch and prepare your local repository for future work.

When your PR is checked into the main branch, the bookdown site will rebuild, adding your slides to [this site](https://r4ds.github.io/bookclub-islr/).
