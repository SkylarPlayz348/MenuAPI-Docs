---
title: "Setup"
weight: 20
date: 2020-04-18T16:05:00+02:00
---

## Setup

_Note, this is only for resource developers, don't install this on your server manually if you're not making a resource with it._

You have 2 options:

1. Download the latest release zip and use the correct version (FiveM/RedM) for your resource. Simply include the DLL as a reference in your C# project and add `using MenuAPI;` to each file where you need to use MenuAPI.
2. Use the NuGet package, which can be found [here](https://www.nuget.org/packages/MenuAPI.FiveM/) for FiveM, and [here](https://www.nuget.org/packages/MenuAPI.RedM/) for RedM.

After doing either of the above and you're ready to build and publish your resource, add `files {'MenuAPI.dll'}` to your `fxmanifest.lua` or `__resource.lua` file, and make sure that you include the `MenuAPI.dll` file in the folder of your resource.

---

{{%expand "Old setup instructions" %}}

_These are the old instructions, they're still relevant but slightly outdated._

## 1. Adding the dependency

Just like any other API. Add it as a reference in your C# client project. Check the [FiveM docs](https://docs.fivem.net/) for info on how to setup a C# resource.

## 2. Using the API

Checkout the example menu provided in the download. It'll show you exactly what all the features are. The rest is up to you.

## 3. Where can I find a reference of all functions/classes/types/whatevers?

Coming soon on these docs. Currently, use the source code as a guide (there's comments in there for a reason). And use the example menu for some basic info. It's designed similar to NativeUI's structure, so if you're familiar with NativeUI (C# version) then this shouldn't be hard to switch to at all.

{{% /expand %}}
