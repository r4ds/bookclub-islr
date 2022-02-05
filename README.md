# R4DS Introduction to Statistical Learning Using R Book Club

Welcome to the R4DS Introduction to Statistical Learning Using R Book Club!

We are working together to read [_Introduction to Statistical Learning Using R_](https://www.statlearning.com) by Gareth James, Daniela Witten, Trevor Hastie, and Rob Tibshirani (Springer Science+Business Media, LLC, part of Springer Nature, copyright 2021, 978-1-0716-1418-1_1).
Join the #book_club-islr channel on the [R4DS Slack](https://r4ds.io/join) to participate.
As we read, we are producing [notes about the book](https://r4ds.github.io/bookclub-islr/).

## Meeting Schedule

If you would like to present, please add your name next to a chapter using the [GitHub Web Editor](https://youtu.be/d41oc2OMAuI)!

*Cohort 1: (started 2021-09-21) - Tuesdays, 10:00am EST/EDT*

<details>
  <summary> Past Meetings </summary>

- 2021-09-21: Chapter 1: Introduction - Jon Harmon
- 2021-09-28: Chapter 2: Statistical Learning (part 1) - Ray Balise
- 2021-10-05: Chapter 2: Statistical Learning (part 2) - Ray Balise and Jon Harmon
- 2021-10-12: Chapter 3: Linear Regression (part 1) - Jon Harmon
- 2021-10-19: Chapter 3: Linear Regression (part 2) - August
- 2021-10-26: Chapter 3: Linear Regression (lab) - Jon Harmon
- 2021-11-02: NO MEETING (Fallback Break)
- 2021-11-09: Chapter 4: Classification (part 1) - Mei Ling
- 2021-11-16: Chapter 4: Classification (lab) - Ray Balise
- 2021-11-23: Chapter 4: Classification (part 2) - Kim Martin
- 2021-11-30: Chapter 5: Resampling Methods (part 1) - Laura Rose
- 2021-12-07: Chapter 5: Resampling Methods (part 2) - Justin Dollman
- 2021-12-14: Chapter 6: Linear Model Selection and Regularization (part 1) - Justin Dollman
- 2021-12-28 & 2022-01-04: NO MEETINGS (Winter Break)
  
  </details>
  
- 2022-01-11: Chapter 6: Linear Model Selection and Regularization (part 2) - Justin Dollman
- 2022-01-18: Chapter 6: Linear Model Selection and Regularization (Lab) - Federica Gazzelloni
- 2022-01-25: Chapter 7: Moving Beyond Linearity (part 1) - Justin Dollman
- 2022-02-01: Chapter 7: Moving Beyond Linearity (part 2) - Justin Dollman
- 2022-02-08: Chapter 8: Tree-Based Methods (part 1) - TBD
- 2022-02-15: Chapter 8: Tree-Based Methods (part 2) - TBD
- 2022-02-22: Chapter 9: Support Vector Machines (part 1) - TBD
- 2022-03-01: Chapter 9: Support Vector Machines (part 2) - TBD
- 2022-03-08: Chapter 10: Deep Learning (part 1) - TBD
- 2022-03-15: Chapter 10: Deep Learning (part 2) - Federica Gazzelloni
- 2022-03-22: Chapter 11: Survival Analysis and Censored Data (part 1) - TBD
- 2022-03-29: Chapter 11: Survival Analysis and Censored Data (part 2) - TBD
- 2022-04-05: Chapter 12: Unsupervised Learning (part 1) - TBD
- 2022-04-12: Chapter 12: Unsupervised Learning (part 2) - TBD
- 2022-04-19: Chapter 13: Multiple Testing (part 1) - TBD
- 2022-04-26: Chapter 13: Multiple Testing (part 2) - TBD

*Cohort 2: (starts 2021-12-02) - Tuesdays, 10:00am CST*

<details>
  <summary> Past Meetings </summary>

- 2021-12-02	Chapter 1: Introduction	- Federica Gazzelloni
- 2021-12-09	Chapter 2: Statistical Learning	- Jim Gruman
- 2021-12-16	Chapter 2: Statistical Learning	(Lab) - Jim Gruman
- 2021-12-23	NO MEETING	
- 2021-12-30	NO MEETING	
- 2022-01-06	Chapter 3: Linear Regression - Ricardo J. Serrano
- 2022-01-13	Chapter 3: Linear Regression (Lab) - Ricardo J. Serrano
- 2022-01-20	Chapter 4: Classification	- Michael Haugen
- 2022-01-27	Chapter 4: Classification	(Lab) - Michael Haugen
  
</details>
  
- 2022-02-03	Chapter 5: Resampling Methods	- (Lab) Ricardo J. Serrano & Federica Gazzelloni
- 2022-02-10	Chapter 5: Resampling Methods	- TBC
- 2022-02-17	Chapter 6: Linear Model Selection and Regularization - Federica Gazzelloni
- 2022-02-24	Chapter 6: Linear Model Selection and Regularization (Lab) - Federica Gazzelloni
- 2022-03-03	Chapter 7: Moving Beyond Linearity - TBC
- 2022-03-10	Chapter 7: Moving Beyond Linearity (Lab) - TBC	
- 2022-03-17	Chapter 8: Tree-Based Methods	- Ricardo J. Serrano
- 2022-03-24	Chapter 8: Tree-Based Methods	(Lab) - Ricardo J. Serrano
- 2022-03-31	Chapter 9: Support Vector Machines - TBC
- 2022-04-07	Chapter 9: Support Vector Machines (Lab) - TBC
- 2022-04-14	Chapter 10: Deep Learning	- TBC
- 2022-04-21	Chapter 10: Deep Learning	(Lab) - TBC
- 2022-04-28	Chapter 11: Survival Analysis and Censored Data -	Michael Haugen
- 2022-05-05	Chapter 11: Survival Analysis and Censored Data	(Lab) - Michael Haugen
- 2022-05-12	Chapter 12: Unsupervised Learning	- TBC	
- 2022-05-19	Chapter 12: Unsupervised Learning	(Lab) - TBC	
- 2022-05-26	Chapter 13: Multiple Testing - Federica Gazzelloni	
- 2022-06-02	Chapter 13: Multiple Testing (Lab) - Federica Gazzelloni	
- 2022-06-09  Final Discussion and Q&A - All  

<hr>


## How to Present

This repository is structured as a [{bookdown}](https://CRAN.R-project.org/package=bookdown) site.
To present, follow these instructions:

1. [Setup Github Locally](https://www.youtube.com/watch?v=hNUNPkoledI)
2. Fork this repository.
3. Create a New Project in RStudio using your fork.
4. Install dependencies for this book with `devtools::install_dev_deps()` (technically optional but it's nice to be able to rebuild the full book).
5. Create a New Branch in your fork for your work.
6. Edit the appropriate chapter file, if necessary. Use `##` to indicate new slides (new sections).
7. If you use any packages that are not already in the `DESCRIPTION`, add them. You can use `usethis::use_package("myCoolPackage")` to add them quickly!
8. Commit your changes.
9. Push your changes to your branch.
10. Open a Pull Request (PR) to let us know that your slides are ready.

When your PR is checked into the main branch, the bookdown site will rebuild, adding your slides to [this site](https://r4ds.github.io/bookclub-islr/).
