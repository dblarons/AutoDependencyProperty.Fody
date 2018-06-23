# AutoDependencyProperty.Fody

## Original Repo

https://bitbucket.org/megafinz/autodependencyproperty.fody

It's a Mercurial repo, so none of the original commits were retained here.

## What's different about this repo?

- Updated Visual Studio project (`ToolsVersion` 3.0->12.0, `TargetFrameworkVersion` 4.0->4.6.1)
- Updated Dependencies
- FodyHelpers is included instead of FodyCecil so that Mono.Cecil is on version 0.10.0.0 instead of 0.9.x.x

## Overview

Fody plugin that automatically generates DependencyProperty boilerplate from simple C# properties.

Documentation: [No more DependencyProperty with AutoDependencyProperty.Fody](https://blog.machinezoo.com/no-more-dependencyproperty-with)

## Run Tests

```
.\packages\NUnit.ConsoleRunner.3.8.0\tools\nunit3-console.exe .\Tests\bin\Debug\Tests.dll
```

## License

The original author included the MIT license in their repo, but a BSD3 license is listed in Nuget. Since I copied the repo, I included the MIT license here.
