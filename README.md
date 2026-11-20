# PlatformIndependentNuGetPackagesForks

NuGet packages that are forks of third-party libraries.
They are kept apart from [PlatformIndependentNuGetPackages](https://github.com/sunamo/PlatformIndependentNuGetPackages), which holds only first-party packages.

| Package | Original library |
|---|---|
| SunamoDotNetZip | DotNetZip (.NET 9 fork without the known security vulnerability) |
| SunamoBitLockerManager | BitLockerManager |

Rules for this repository:

- Every package keeps the original license and author credit in its `readme.md` and `.csproj`.
- Public API stays as close to the upstream source as possible, so `CS1591` (missing XML comments) is suppressed.
- Files are not split to follow the first-party file-size rule, to keep the diff against upstream small.
