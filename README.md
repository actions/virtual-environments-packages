# virtual-environments-packages
This repository will (soon!) contain the code and scripts that we use to build tool packages used in [virtual-environments](https://github.com/actions/virtual-environments).  
Packages are uploaded and attached to the [GitHub Package Registry](https://github.com/actions/virtual-environments-packages/packages).

## Available tools
- Python (2.7, 3.5, 3.6, 3.7, 3.8)
- Ruby (2.4, 2.5, 2.6, 2.7)
- PyPy (2, 3)
- Boost (1.69, 1.72)

## Install packages
- Configure npm to associate `actions` scope with GitHub Package Registry:
```
$ npm config set @actions:registry https://npm.pkg.github.com/
```
- Install package
```
$ npm install @actions/<package_name>@<package_version>
```