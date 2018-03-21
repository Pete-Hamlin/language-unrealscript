# UnrealScript language support Atom #

Syntax highlighting for UnrealScript (.uc) files, used by Unreal Engine 3. Currently only supports basic C/C++ snippets, does not have any specific to UnrealScript itself.

I noticed Atom did not yet have a syntax package for the language, so I thought I'd make one.  It will load for any file with the .uc extension.

Contributions to the language are more than welcome, in fact I actively encourage others to Fork the repo and create pull requests.

## Install

Install the package `language-unrealscript` in Atom (Preferences->Packages) or Atom's package manager from a shell:

```bash
$ apm install language-unrealscript
```

## Issues/Bugs ##

As UnrealScript is based heavily on C++, this is package is essentially just a bare bones fork of the C++ language package for Atom with some added functions/classes used by only by UnrealEngine.

Please feel free to report any problems with the language package by opening an issue or by all means, fix it and make a pull request. Equally goes for any improvements that you wish to make, I will happily look through and merge.

## Contributors ##

poosh
