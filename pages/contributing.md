---
layout: page
title: Contributing to Displore
permalink: /contributing/
---

An interesting read is [Contributing to a Github Project](http://jasonlewis.me/article/contributing-to-a-github-project) and [Github's guide](https://guides.github.com/activities/contributing-to-open-source/#contributing).

### Ways to contribute
* [Submitting issues](#submitting-issues)
* [Suggesting features](#suggesting-features)
* [Pull Requests](#pull-requests)
  * [Which branch?](#which-branch)
  * [Commit messages](#commit-messages)
* [Coding style](#coding-style)

#### Submitting issues
If you run into problems, do not hesitate to file an issue (check the existing issues first). Please be as descriptive and clear as possible. Describe for example what you did, what the results where and what you expected. Also include information on the versions you are using of Laravel, Displore, etc. and if possible code/demos are helpful too.

#### Suggesting features
If you want to suggest a new feature, you can file an issue and include the *[Proposal]* or *[Idea]* tag in the title. Try to elaborate your suggestion as much as possible.
Features should only be proposed in the Displore/core repository if they apply the general mechanics of both the Displore and Journal package.

#### Pull Requests
This workflow is inspired by [Github Flow](http://scottchacon.com/2011/08/31/github-flow.html)

##### Which branch?
* The `master` branch always contains the latest stable release. 
* Bug fixes should be sent to the `master` branch.
* Minor features that are fully backwards compatible with the latest release may be sent to the `master` branch as well.
* Incompatible features or bug fixes should be sent to the `develop` branch or relevant `feature-` branch.

##### Commit messages
Consider starting the commit message with an applicable prefix:

* *Fixed:* when fixing a bug, an issue could be referenced.
* *Updated:* when changing or improving code which did not necessarily cause bugs.
* *New:* when introducing a new file, function or cool feature.
* *Deleted:* when removing code or files.
* *Dev:* when committing experimental code, please describe in the extended description what it is and why it is experimental.

#### Coding style
In general, follow [Laravel's style](http://laravel.com/docs/contributions#coding-style).