---
title: Core committers
summary: The team of contributors that has merge access to our open source repositories
icon: users
---

# Core Committers
The Core Committers team is reviewed approximately annually, new members are added based on quality contributions to SilverStipe code and outstanding community participation. 

## Core Committer team

* [Aaron Carlino](https://github.com/unclecheese/)
* [Chris Joe](https://github.com/flamerohr/)
* [Daniel Hensby](https://github.com/dhensby)
* [Garion Herman](https://github.com/cheddam)
* [Guy Marriott](https://github.com/ScopeyNZ)
* [Ingo Schommer](https://github.com/chillu)
* [Loz Calver](https://github.com/kinglozzer)
* [Maxime Rainville](https://github.com/maxime-rainville)
* [Paul Clarke](https://github.com/clarkepaul)
* [Sam Minnée](https://github.com/sminnee)
* [Stevie Mayhew](https://github.com/stevie-mayhew/)
* [Will Rossiter](https://github.com/wilr/)

## What is Silverstripe Core?

The "core" of Silverstripe is a set of non-dev dependencies contained in
[silverstripe/recipe-cms](https://github.com/silverstripe/recipe-cms)
and [silverstripe/recipe-core](https://github.com/silverstripe/recipe-cms).
It is limited to dependencies owned by the "silverstripe" Packagist vendor,
but can include "dev" dependencies.
## House rules for the Core Committer team

The "Core Committers" consist of everybody with write permissions to Silverstripe Core.
With great power comes great responsibility, so we have agreed on certain expectations:

 * Be friendly, encouraging and constructive towards other community members
 * Frequently review pull requests and new issues (in particular, respond quickly to @mentions)
 * Treat issues according to our [issue guidelines](issues_and_bugs), and use the [triage resources](triage_resources)
 * Don't commit directly to a release branch, raise pull requests instead (except trivial fixes)
 * Only merge code you have tested and fully understand. If in doubt, ask for a second opinion.
 * Follow the [Supported Modules Standard](https://www.silverstripe.org/software/addons/supported-modules-definition/)
 * Ensure contributions have appropriate [test coverage](../developer_guides/testing), are documented, and pass our [coding conventions](/getting_started/coding_conventions)
 * Keep the codebase "releasable" at all times (check our [release process](release_process))
 * Follow [Semantic Versioning](code/#picking-the-right-version) by putting any changes into the correct branch
 * API changes and non-trivial features should not be merged into release branches. 
 * API changes on master should not be merged until they have the buy-in of at least two Core Committers (or better, through the [core mailing list](https://groups.google.com/forum/#!forum/silverstripe-dev))
 * Be inclusive. Ensure a wide range of SilverStripe developers can obtain an understanding of your code and docs, and you're not the only one who can maintain it.
 * Avoid `git push --force`, and be careful with your git remotes (no accidental pushes)
 * Use your own forks to create feature branches
 * We release using the standard process. See the [Making a SilverStripe Core Release](making_a_silverstripe_core_release)

## Roles

### Core Committer

Core Committers should have at least "Maintain" level access to Silverstripe Core,
which includes the ability to push changes and perform releases.

This role may be granted by a quorum of all Core Committers.

### Contributing Committers

Beyond the Core Committer role, there can be individuals which
focus on core development work - typically sponsored through full-time product development roles by SilverStripe Ltd.
These Contributing Committers require write access to core repositories to maintain their pace,
often working alongside Core Committers. They are guided by additional rules:

 * Contributing Committers have write access to core repositories in order to work effectively with Github issues. They are expected to use those permissions with good judgement regarding merges of pull requests.
 * Complex or impactful changes need to be reviewed and approved by one or more Core Committers. This includes any additions, removals or changes to commonly used APIs. If that's not possible in the team, ping `@silverstripe/core-team` to get other Core Committers involved.
 * For these complex or impactful changes, Core Committers should be given 1-2 working days to review. Ideally at this point, the API has already been agreed on through issue comments outlining the planned work (see [RFC Process](request_for_comment]).
 * More straightforward changes (e.g. documentation, styling) or areas which require quite specialised expertise (e.g. React) that's less available through most Core Committers can be approved or merged by team members who aren't Core Committers
 * Self-merges should be avoided, but are preferable to having work go stale or forcing other team members to waste time by context switching into a complex review (e.g. because the original reviewer went on leave). Any self-merge should be accompanied by a comment why this couldn't be handled in another way, and a (preferably written) approval from another team member.

This role may be granted by any Core Committer,
who should give other Core Committers an opportunity to weigh in on the decision.

### Triage

Triage of issues and pull request is an important activity: Reviewing issues, adding labels,
closing stale issues, etc. This does not require write access to the repository as a "Contributing Committer".
This is a great way for active community members to help out, and start a path towards becoming a Core Committer.

Triage roles may be granted by any Core Committer,
who should give other Core Committers an opportunity to weigh in on the decision.

## Supported Modules

In addition to Silverstripe Core, there are many [Supported Modules](https://www.silverstripe.org/software/addons/supported-modules-definition/)
which have the backing of Silverstripe Ltd. While it's a good idea to apply the rules outlined in this documented,
work on these modules is guided by the 
[Supported Modules Standard](https://www.silverstripe.org/software/addons/supported-modules-definition/).
Commit access in Supported Modules is handled by agreement of the repository maintainers,
or any additional guidelines outlined via a `CONTRIBUTING` file.
