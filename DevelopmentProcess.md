# Development Process Guidelines

These guidelines are indended to be used by [@morganey-lang] community
members while working on [@morganey-lang]'s projects.

They are completely optional, because [per rules](README.md#becoming-a-project-leader):

> The Project Leaders are responsible for organizing the development process of the projects they lead.

So, before contributing anything to any of the [@morganey-lang]'s projects, ask a corresponding Project Leader about development process details. See [Projects.md](Projects.md) for the full list of [@morganey-lang] projects and their corresponding Project Leaders.

If you're a Project Leader, consider following these practices.

## Release Process

- [Semantic Versioning 2.0.0][semver] should be used for project releases versioning.
- The Project Leader is responsible for planning releases and publishing the released project artifacts. Only he/she can decide
  * what's going to be the version number of a release,
  * what issues are going to be included into a release,
  * what artifacts are part of a release.
- The released artifacts should be published at least via [GitHub Releases](github-releases) mechanism if applicable.
- If artifacts require extra distribution options they should be published to other places accordingly (e.g. Maven repos, plugin stores and such).
- It is strongly recommended to plan big and major releases via [GitHub Milestones](github-milestones) mechanism. For each such release there should a corresponding release milestone named as the version of the release.
- The Project Leader should be responsible for creating and organizing release milestones.

## Issue Tracker Hygiene

*TBD([#34])*

## Problem Reporting Format

*TBD([#35])*

## Label System

*TBD([#21])*

## Contribution Protocol

*TBD([#37])*

## Issue & PR templates

*TBD([#38])*

[@morganey-lang]: https://github.com/morganey-lang
[#34]: https://github.com/morganey-lang/community/issues/34
[#35]: https://github.com/morganey-lang/community/issues/35
[#21]: https://github.com/morganey-lang/community/issues/21
[#37]: https://github.com/morganey-lang/community/issues/37
[#38]: https://github.com/morganey-lang/community/issues/38
[semver]: http://semver.org/
[github-milestones]: https://help.github.com/articles/creating-and-editing-milestones-for-issues-and-pull-requests/
[github-releases]: https://help.github.com/articles/creating-releases/
