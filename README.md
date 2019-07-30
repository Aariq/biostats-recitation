# biostats-recitation
Course materials for recitation section of BIO132 at Tufts University, 2017.

This was the first year the course used R.  Previously it used SPSS.  This was also the first year for a required recitation section that contained lecture rather than just open hours for SPSS troubleshooting. Eric Scott and Natalie Kerr were responsible for creating all course materials in this repository.

Many of the data sets were taken from Analysis of Biological Data by Michael Whitlock. We provided students with .csv files, but these data sets are also available via the package `abd`.


# Notes for the Next Iteration:

## R Studio Cloud
Even though this year went smoother, in part due to a tidyverse-centric approach, there were still students frustrated by isntallation issues.  In particular there was confusion about whether to install from binary or compile from source when installing packages.  Since then I learned about [R Studio Cloud](https://rstudio.cloud/) which I **highly** recommend whoever TAs this class next uses.  You can set up a base project with all the packages you need installed and then students can run R Studio through a web browser and not have to install *anything*! Also, it's free (for now at least)

## Slides
Avalon and I made slides with the ioslides system (File > New File > R Markdown...), which is simple, but limited. But now you can knit R Markdown to powerpoint slides!  If it's easy to switch over to powerpoint (and I think it will be), I'd recommend doing that since it's easier to share with students.  You can also make a template powerpoint to use as a [reference document](https://support.rstudio.com/hc/en-us/articles/360004672913-Rendering-PowerPoint-Presentations-with-RStudio) if you want to change the theme.

## Code Highlighting
Avalon found a way to highlight code in ioslides presentations, but it was clunky and we didn't use it all that often.  Sinc then, the (still in early development) [`demoR` package](https://web.calpoly.edu/~kbodwin/demoR/articles/demoR.html) came out.  It lets you highlight bits of code in knitted output (for example on powerpoint slides).  It's worth knowing about and might be useful in early lessons when students are still wrapping their heads around which bits of code are arbitrary (names of objects) and which bits need to be typed verbatim (e.g. function names).