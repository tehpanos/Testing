# Course setup

### First commit and push

-   After accepting the assignment clone the repository in a new project in RStudio.

-   Open the `course.qmd` file in the RStudio editor.

-   Enter your name in the YAML header of the file.

-   Save the file.

-   Commit `course.qmd` to your local git repository

-   Push the file to the classroom assignment repository.

### More content and R

-   Add a level three header to `course.qmd` about the height of trees

-   Write a sentence on the height of some trees.

-   Add a code chunk for R that contains\
    `library(tidyverse)`\
    `count(trees, Height)`

-   `trees` is an inbuilt data set of R

-   Save the `course.qmd` file.

-   Install the `renv` and the `yaml` package

-   Run `renv::activate()`. This will create a `renv.lock` file

-   Run `renv::hydrate()`

-   This should install the `tidyverse` package (why?).

-   Run `renv::snapshot()` , which will record the tidyverse package (and many other) in `renv.lock` .

-   Commit and push the `renv.lock` file to the classroom assignment repository.
