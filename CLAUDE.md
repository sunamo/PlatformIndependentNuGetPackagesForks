# PlatformIndependentNuGetPackagesForks

Container for NuGet packages that are forks of third-party libraries (SunamoDotNetZip, SunamoBitLockerManager). First-party packages live in `PlatformIndependentNuGetPackages` (pinp).

- Each package is a submodule on branch `claude`; the folder `<repo>-claude` is always on `claude`, the folder without `-claude` only on `master`.
- Keep the original license and author credit in each package (`readme.md`, `Authors`, `PackageLicenseExpression`).
- Keep the public API and file layout close to upstream: no file splitting and no XML documentation requirement (`NoWarn CS1591`).
- Code and comments written by us are English only; commit messages are English `<type>: description`.
- Publishing follows the pinp rules (`ptgan` from the non-worktree checkout, versions `year.month.day.build`).
