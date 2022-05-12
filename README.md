# R4DS Data Science at the Command Line Book Club

Welcome to the R4DS Data Science at the Command Line Book Club!

We are working together to read [_Data Science at the Command Line_](https://datascienceatthecommandline.com/2e/) by Jeroen Janssens ( O’Reilly Media, copyright October 2021, [978-1492087915](https://www.oreilly.com/library/view/data-science-at/9781492087908/)).
Join the #book_club-dscl channel on the [R4DS Slack](https://r4ds.io/join) to participate.
As we read, we are producing [notes about the book](https://r4ds.io/dscl).

## Meeting Schedule

If you would like to present, please add your name next to a chapter using the [GitHub Web Editor](https://youtu.be/d41oc2OMAuI)!

*Cohort 1: Wednesdays, 8:00am CST/CDT*

<details>
  <summary> Past Meetings </summary>
  
(none yet)
</details>

- 2022-05-11: Chapter 1 (Introduction) - Shamsuddeen Muhammad
- 2022-05-18: Chapter 2 (Getting Started) - Pavitra Chakravarty
- 2022-05-25: Chapter 3 (Obtaining Data) - PRESENTER TBD
- 2022-06-01: Chapter 4 (Creating Command-line Tools) - PRESENTER TBD
- 2022-06-08: Chapter 5 (Scrubbing Data) - PRESENTER TBD
- 2022-06-15: Chapter 6 (Project Management with Make) - PRESENTER TBD
- 2022-06-22: Chapter 7 (Exploring Data) - PRESENTER TBD
- 2022-06-29: Chapter 8 (Parallel Pipelines) - PRESENTER TBD
- 2022-07-06: Chapter 9 (Modeling Data) - PRESENTER TBD
- 2022-07-13: Chapter 10 (Polyglot Data Science) - PRESENTER TBD
- 2022-07-20: Chapter 11 (Conclusion) - PRESENTER TBD



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
