This release is mainly to fix test errors caused by an update to the
htmlwidgets package.

## Test environments
* OS X El Capitan, R 3.3.0
* ubuntu 12.04 (on travis-ci), R 3.2.5, 3.3.0, R-devel
* Windows Server 2012 R2 (x64), R 3.3.0
* win-builder (devel and release)

## R CMD check results
There were no NOTEs, ERRORs or WARNINGs.

## Reverse dependencies

Covr is a development tool only so its code is not actually run when building
any downstream dependencies. Nonetheless I have run R CMD check on the 72
downstream dependencies. There were no relevant Errors.

  Summary at: https://github.com/jimhester/covr/tree/master/revdep
