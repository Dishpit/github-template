# Project Versioning

## How do we define our versions?

Per normal semantic versioning, versions are `<major>.<minor>.<patch>`.

## Branches

Currently our branches are as follows:

|        Name | Current Version | Notes
|------------:|-----------------|------------------------------------------------------------------------------
|        main | 0.2.0           | Receives markdown documentation or GitHub automation related changes
|     staging | 0.1.5           | Non-breaking or security bug fixes only (the actual stable branch)
| development | 0.1.3           | Non-breaking or security fixes and features only

## Breaking Changes

Breaking changes **are** any changes that alter/remove field, property, method, or class signatures, or alter or delete assemblies

Breaking changes **are not** any changes that introduce overloads or new signatures, but are still not permitted in the "main" branch
