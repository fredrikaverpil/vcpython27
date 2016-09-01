# vcpython27

This is a working version of the broken Chocolatey package at https://chocolatey.org/packages/vcpython27

Please see instructions [here](https://github.com/fredrikaverpil/vcpython27/releases) on how to download and install this package.

<br>

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
