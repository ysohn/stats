## R & RStudio Troubleshooting Guide

General tip:


If you do not experience the corresponding problems shown below, you do not have to follow the corresponding suggestions.

---

* Error messages with ??? marks: Typically due to the fact that your Windows user name is in not in Enlgish. A straightforward solution is to change your username to an English username or create a new account in English. Check this page if you want to know details: https://www.reddit.com/r/RStudio/comments/635qk8/rstudio_nonascii_windows_username_workaround/

* Auto completion in RStudio stops: Various reasons. First, update your RStudio to the most up-to-date version by visting https://www.rstudio.com/products/rstudio/download/ If you still confront the same problem after updating RStudio, try `r {compiler::setCompilerOptions(optimize = 1)}`.
