Scoop-Portapps [![Build status](https://ci.appveyor.com/api/projects/status/v4qgqhrg809joajl?svg=true)](https://ci.appveyor.com/project/Velgus/scoop-portapps)
===

A Scoop bucket for the Portapps collection of portable applications for Windows. See the [Portapps website  ](https://portapps.io/) or [GitHub project](https://github.com/portapps) for more details.

Installation
--------

In PowerShell:
```
# Install Scoop
set-executionpolicy unrestricted -scope cu
iex (new-object net.webclient).downloadstring('https://get.scoop.sh')

# Add Bucket
scoop bucket add Portapps https://github.com/Velgus/Scoop-Portapps.git

# Install apps
scoop install <Scoop App Name>
```
