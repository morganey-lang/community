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

## Issue Tracking

Issue tracking is the most important thing in any development process. Any project contains infinite amount of issues, the more we track, the better project we can build. Everything related to the project should be captured either in the code or in the issue tracker. Ideally 100% of project related communications should be done via Issue Tracker only. That ensures that communications are centralized and properly archived for future convenient reference.

### Issue Categories ###

*TBD*

### Issue Tracker Hygiene ###

Any issue tracker naturally becomes messy over time. That is completely normal. It is generally a good idea for the Project Leaders to periodically go through all of the issues of their projects and clean them up. Weekly or monthly depending on the size of the project and amount of development activity.

## Problem Reporting Format

*TBD([#35])*

## Label System

*TBD([#21])*

## Contribution Protocol

*TBD([#37])*

## Issue & PR templates

*TBD([#38])*

[@morganey-lang]: https://github.com/morganey-lang
[#35]: https://github.com/morganey-lang/community/issues/35
[#21]: https://github.com/morganey-lang/community/issues/21
[#37]: https://github.com/morganey-lang/community/issues/37
[#38]: https://github.com/morganey-lang/community/issues/38
[semver]: http://semver.org/
[github-milestones]: https://help.github.com/articles/creating-and-editing-milestones-for-issues-and-pull-requests/
[github-releases]: https://help.github.com/articles/creating-releases/
