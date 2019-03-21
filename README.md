# vcpython27

[![Build Status](https://travis-ci.com/fredrikaverpil/vcpython27.svg?branch=master)](https://travis-ci.com/fredrikaverpil/vcpython27)

A [Chocolatey](https://chocolatey.org) package which installs the Microsoft Visual C++ Compiler for Python 2.7 and its dependencies. Release notes are located [here](https://github.com/fredrikaverpil/vcpython27/releases). Please also see the official package page here: https://chocolatey.org/packages/vcpython27

<br>

Note: to avoid installing dependencies:

```
choco install python2 vcredist2008
choco install --ignore-dependencies vcpython27
```


### Development

For development and testing, see the official [quickstart guide](https://github.com/chocolatey/choco/wiki/CreatePackagesQuickStart#quick-start-guide).

#### Download and create the package

```cmd
git clone https://github.com/fredrikaverpil/vcpython27.git
cd vcpython27
choco pack
```

#### Install the local package

CMD.exe:

```cmd
choco install vcpython27 -s '%cd%' -f
```

Powershell:

```powershell
choco install vcpython27 -s "$pwd" -f
```

#### Uninstall

```cmd
choco uninstall vcpython27
```