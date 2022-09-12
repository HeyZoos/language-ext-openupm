## Nevermind this repo doesn't need to exist. Just use NuGet for Unity.

https://github.com/GlitchEnzo/NuGetForUnity

[![openupm](https://img.shields.io/npm/v/com.louthy.languageext?label=openupm&registry_uri=https://package.openupm.com)](https://openupm.com/packages/com.louthy.languageext/)

This package is just a wrapper for the `LanguageExt.Core.dll` provided by the [language-ext](https://github.com/louthy/language-ext) project. The wrapper exposes the `dll` as a package for [OpenUPM](https://openupm.com/).

# Getting Started

Install the package via OpenUPM.

```bash
openupm add com.louthy.languageext
```

Add this to the top of each `.cs` file you want to use the functional types for.

```cs
using LanguageExt;
using static LanguageExt.Prelude;
```

Then follow along with the rest of the [documentation](https://github.com/louthy/language-ext#getting-started).
