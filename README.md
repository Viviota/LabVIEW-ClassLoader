# ClassLoader Library

This is a simple reuse library for loading classes dynamically from disk.
The primary use case is to load from either source code (.lvlib) or from compiled PPLs (.lvlibp)


## Packed Library Support
This library is built with PPL / Common-reuse patterns in mind.  It is split between a main library and the "API" library, which wraps functions from the main library.  Only the API library is used on the palettes.

This library is distributed with PPLs (currently only compiled for Windows).

This library is distributed as two different VIPM packages.  One of which has the LabVIEW Palettes setup to reference source code, and the others reference PPLs.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request

To contribute to this toolkit, you will need LabVIEW 2020.

## Credits

ClassLoader LabVIEW library is an open source project maintained by Viviota and licensed by the BSD 3-Clause license

## License

ClassLoader LabVIEW library is distributed under the open source BSD 3-Clause license providing everyone right to use and distribute both souce code and compiled versions of this toolkit. See LICENSE.md file for details.