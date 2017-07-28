# Topics:

## finding help

- ... on stack exchange.

## files, and the command line (aka The Shell)

**What's there and what is it?**

- directories, paths, `ls`
- `file` type: binary, text, executable
- "the" working directory
- `cat`, `less`, `head`

**Moving things around.**

- `cp`, `rm`
- `ssh`, `rsync`
- `curl`

**Doing things with it.**

- intro to pipes: `column -t`, `tr`
- redirecting: `head data.csv > subsample.csv`
- run a script on the command line

**Would be nice to do but probably don't have time:**

- `sed`, regexps
- writing a bash script
- `awk`
- the rest of coreutils


## introduction to using R

**How to start with R.**

- help
- packages and CRAN task views
- assigning variables
- reading in data (files; working directory)
- vectorization: `x + y`
- subsetting and indexing (basic)
- distinction between command line and Rscript and Rstudio
- running an R script

**A bit more on programming: functions.**

- reusing code (DRY, not WET)
- functions!
- scope.
- `source("my_functions.R")`

**Would be nice to do also:**

- loops and flow control
- random number generation
- writing plots to files


**Wrap-up:**

Make a nice plot, e.g. a curve fitted to a histogram produced by random subsampling,
incrementally by adding options.

## collaboration, backups, and version control: git

Also, probably not time to do this.

- why? (see title)
- getting a repo from github
- the one-branch, one-user git workflow
- dealing with a merge conflict
- what not to do (rewrite history; check in large binary files that get changed a lot)
