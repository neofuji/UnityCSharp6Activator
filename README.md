# UnityCSharp6Activator
Enables Mono compiler to use C# 6 in Unity 5.5+ (also supports Visual Studio 2015+ Tools for Unity).

[![license: MIT](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

## How to use
Add `Assets/mcs.rsp` to your `Assets` folder.

If you want to use VSTU, also add `Assets/Editor` folder. After deleting all `*.csproj` files, run `Assets > Open C# Project`.

## Restrictions
- Unity 5.5 does not support .NET Framework 4.5 but 3.5. Features which require .NET Framework 4.0+ cannot be used as they are (`async`, `await`, `dynamic`, and so on).

## Author
Toru Higuruma @neofuji
