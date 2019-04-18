## R & RStudio Troubleshooting Guide

General tip: Almost all of the problems you confront were certainly experienced by other users in the world. You will find a solution by searching Google by typing the error message you see and describing your issues.

If you do not experience the problems shown below, you do not have to follow the corresponding suggestions.

---

* Error messages with ??? marks: This error is typically due to the fact that your Windows user name is not in Enlgish. A straightforward solution is to change your username to an English username or create a new account in English. Check this page if you want to know details: https://www.reddit.com/r/RStudio/comments/635qk8/rstudio_nonascii_windows_username_workaround/

* Auto completion in RStudio stops: Various reasons. First, update your RStudio to the most up-to-date version by visting https://www.rstudio.com/products/rstudio/download/ If you still confront the same problem after updating RStudio, try `compiler::setCompilerOptions(optimize = 1)`.
