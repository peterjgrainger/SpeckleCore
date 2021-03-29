# SpeckleCore
[![Build status](https://ci.appveyor.com/api/projects/status/k0n0853v26f1thl4/branch/master?svg=true)](https://ci.appveyor.com/project/SpeckleWorks/specklecore/branch/master) [![DOI](https://zenodo.org/badge/100398062.svg)](https://zenodo.org/badge/latestdoi/100398062)



⚠️ **IMPORTANT** ⚠️

Speckle 2.0 is in the works, 👉 [check it out here](https://github.com/specklesystems)!
Speckle 1.0 is currently in LTS (lifetime support), read more about the announcemnt [here](https://speckle.systems/blog/speckle2-vision-and-faq) and [here](https://speckle.systems/blog/insider-speckle2).



## Overview

This is the core .NET client lib of Speckle. It provides: 
- async methods for calling the speckle [api](https://speckleworks.github.io/SpeckleOpenApi/) 
- methods for interacting with the speckle's websocket api
- the core conversion methods (`Serialise` and `Deserialise`) & other helper methods
- a base SpeckleObject from which you can inherit to create your own speckle kits

Pretty much all of speckle's connectors are using this library, including:
- Rhino
- Grasshopper
- Revit
- Dynamo
- Unity (with flavours)

## Usage

Add the NuGet to your project

```
dotnet add package pgcoredotnet5
```

## Creating a new NuGet

Tag this repository with the version you want the NuGet to be. Tag must have four `.` separated numbers `0.0.0.0`

## License 
MIT
