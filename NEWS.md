# CHANGES IN VERSION 0.1.1

## NEW FEATURES

## BUG FIXES

## MAJOR CHANGES

## MINOR CHANGES

## MISC

-----

# CHANGES IN examplr VERSION 0.1.0.10

## NEW FEATURES

## BUG FIXES

## MAJOR CHANGES

## MINOR CHANGES

## MISC

- new patch version to comply with repo conventions

-----

# CHANGES IN examplr VERSION 0.1.0.9

## NEW FEATURES

## BUG FIXES

- `ensureExamplesDirectory()`:
  - corrected path of the files that should actually be written

## MAJOR CHANGES

## MINOR CHANGES

-----

# CHANGES IN examplr VERSION 0.1.0.8

## NEW FEATURES

## BUG FIXES

- `ensureExamplesDirectory()`:
  - ensured uniqueness of example file paths

## MAJOR CHANGES

## MINOR CHANGES

-----

# CHANGES IN examplr VERSION 0.1.0.7

## NEW FEATURES

## BUG FIXES

- Minor bugfixes

## MAJOR CHANGES

## MINOR CHANGES

-----

-----

# CHANGES IN examplr VERSION 0.1.0.6

## NEW FEATURES

## BUG FIXES

- fixed `ensureExamplesDirectory()`

## MAJOR CHANGES

## MINOR CHANGES

-----

# CHANGES IN knitr VERSION 0.1.0.5

## NEW FEATURES

- `ensureExamplesFiles()`
  - added argument `strict` (see next bullet point)
  - added validation of file extension for example file paths (`.r`).
    If file extension `.R` is found, argument `strict` controls if a warning or an error is issued
    If any other file extension than `.r` or `.R` is found, an error is issued

## BUG FIXES

- 'runExamples()'
  - fixed parsing issue for multiple code lines in example files that occurred when `dontrun = TRUE`.

## MAJOR CHANGES

## MINOR CHANGES
