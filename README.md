# PlatformIndependentNuGetPackagesForks

NuGet packages that are forks of third-party libraries.
They are kept apart from [PlatformIndependentNuGetPackages](https://github.com/sunamo/PlatformIndependentNuGetPackages), which holds only first-party packages.

| Package | Original library |
|---|---|
| SunamoDotNetZip | DotNetZip by Dino Chiesa (MS-PL, BSD-3-Clause and Apache-2.0 parts), see `SunamoDotNetZip/THIRD-PARTY-NOTICES.md` |
| SunamoBitLockerManager | BitLockerManager by Roman Minyaylov (MIT), see `SunamoBitLockerManager/LICENSE` |

Rules for this repository:

- Every package keeps the original license and author credit in its `readme.md` and `.csproj`.
- Public API stays as close to the upstream source as possible, so `CS1591` (missing XML comments) is suppressed.
- Files are not split to follow the first-party file-size rule, to keep the diff against upstream small.
