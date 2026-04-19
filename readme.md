# NAME OF PAPER/STUDY
BLINDED

> [!IMPORTANT]
>
> This repository is blinded for peer-review at this time.

This repository contains materials related to the the paper:

*Name of Study*

# Guide

## What is available?

- Analytic code
  - Clink on [here](LINK)
  - Download the `Analysis.qmd` file.
- Output
  - Download the `Analysis.html` file.
- Model objects
  - See \*.Rds files under the `BLANK` folder.

## What is not available?

- Data
  - Participants did not consent to the public release of the data.

Here’s a revised version that’s friendlier for beginners while staying
concise:

------------------------------------------------------------------------

Here’s the revised section:

------------------------------------------------------------------------

## How to Reproduce the Analysis Using `{renv}`

This project uses `{renv}` to ensure you’re working with the exact same
R packages and versions used in the original analysis.

**1. Install R and RStudio**

- [Download R](https://cran.r-project.org/bin/windows/base/) — the core
  software needed to run the analysis
- [Download RStudio](https://posit.co/download/rstudio-desktop/) — a
  beginner-friendly interface for R (recommended)

**2. Get the project files**

**Option A — Git clone (if you use Git):**

Open a terminal, navigate to where you want the project saved, and run:

``` bash
git clone LINK-IS-BLINDED
```

This will download the project into a new folder in that location.

**Option B — Download ZIP:**

Click the green **Code** button at the top of this GitHub page, select
**Download ZIP**, and extract the folder somewhere you’ll remember
(e.g., your Desktop).

**3. Open the project in RStudio**

Inside the project folder, find and double-click the `.Rproj` file. This
opens RStudio in the correct working directory — don’t skip this step,
as it ensures everything runs correctly.

**4. Install `{renv}` (if you don’t have it)**

In the RStudio console, run:

``` r
install.packages("renv")
```

**5. Restore the package environment**

In the RStudio console, run:

``` r
renv::restore()
```

This reads the `renv.lock` file included in the project and
automatically installs all required packages at the correct versions. It
may take a few minutes the first time.

Once complete, you’re ready to run the analysis scripts.
