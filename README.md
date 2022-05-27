# R4DS Data Science at the Command Line Book Club

Welcome to the R4DS Data Science at the Command Line Book Club!

We are working together to read [_Data Science at the Command Line_](https://datascienceatthecommandline.com/2e/) by Jeroen Janssens ( O’Reilly Media, copyright October 2021, [978-1492087915](https://www.oreilly.com/library/view/data-science-at/9781492087908/)).
Join the [#book_club-dscl](https://rfordatascience.slack.com/archives/C03BC8VSTFH) channel on the [R4DS Slack](https://r4ds.io/join) to participate.
As we read, we are producing [notes about the book](https://r4ds.io/dscl).

## Meeting Schedule

If you would like to present, please see the sign-up sheet for your cohort (linked below, and pinned in the [#book_club-dscl](https://rfordatascience.slack.com/archives/C03BC8VSTFH) channel on Slack)!

- [Cohort 1](https://docs.google.com/spreadsheets/d/1dioHLiCEOOIvHUAuneOI_-0jqFzQGeO60TfGFQk3Dkk/edit?usp=sharing) (started 2022-05-04): [Wednesdays, 8:00am CST/CDT](https://www.timeanddate.com/worldclock/converter.html?iso=20220504T130000&p1=24&p2=133) | [meeting videos](https://www.youtube.com/playlist?list=PL3x6DOfs2NGggpv-3tcKBJ6-JKN5laj7K)


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

When your PR is checked into the main branch, the bookdown site will rebuild, adding your slides to [this site](https://r4ds.io/dscl).
