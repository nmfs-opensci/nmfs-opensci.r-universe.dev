# nmfs-opensci.r-universe.dev

https://nmfs-opensci.r-universe.dev/packages: CRAN-like repository for NOAA Fisheries R packages. Binaries are available for Linux, Windows and MacOS.

To install packages from the NMFS-OpenSci R Package Repository:

```
options(repos = c(
    nmfs = 'https://nmfs-opensci.r-universe.dev',
    CRAN = 'https://cloud.r-project.org'))
```

Then you can install any of our packages. You should not have to build from source. After running the code above to add our repo to the options, install as

```
install.packages('pkgname')
```

or you can run
```
install.packages('pkgname', repos = c(nmfs = 'https://nmfs-opensci.r-universe.dev', CRAN = 'https://cloud.r-project.org'))
```

## To use the linux binaries

Help: https://github.com/r-universe-org/help#does-r-universe-have-linux-binaries

```
options(repos = c(
  linux = 'https://nmfs-opensci.r-universe.dev/bin/linux/jammy/4.3/',
  sources = 'https://nmfs-opensci.r-universe.dev',
  cran = 'https://packagemanager.rstudio.com/all/__linux__/focal/latest'
))
```

## Create your own r-universe

https://r-universe.dev/welcome/?installation_id=36737048&setup_action=install

https://ropensci.org/blog/2021/06/22/setup-runiverse/

