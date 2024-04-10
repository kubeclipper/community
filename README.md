# KubeClipper Community

Welcome to the KubeClipper community!

Thank you for your interest in KubeClipper! This document provides the guidelines for how to contribute to the KubeClipper project through issues and pull-requests.

## Contribution Rules

Before you start contributing, read our [Code of Conduct](code-of-conduct.md)

### Issue

#### Issue Types
here are usually 3 types of issues:

* `Bug report`: You’ve found a bug with the code, and want to report it, or create an issue to track the bug.
* `Feature Request`: You think we need a new feature, describe the new feature.
* `Proposal`: Used for items that propose a new idea or functionality. This allows feedback from others before code is written.

#### Before submitting

1. Is it the right repository?
2. Check for existing issues
   1. Before you create a new issue, please do a search in open issues to see if the issue or feature request has already been filed.
   2. If you find your issue already exists, make relevant comments and add your reaction. Use a reaction:
      1. 👍 up-vote
      2. 👎 down-vote
3. For bugs
   1. Check it’s not an environment issue.
   2. You have as much data as possible. This usually comes in the form of logs and/or stacktrace.
4. For proposals
   1. proposals are always required before implementing new features

### Pull Request

All contributions come through pull requests. To submit a proposed change, follow this workflow:

1. Make sure there’s an issue (bug or proposal) raised, which sets the expectations for the contribution you are about to make.
2. Fork the relevant repo and create a new branch
   1. See the Developing docs for more information about setting up a development environment.
3. Create your change
   1. Code changes require tests
4. Update relevant documentation for the change
5. Commit use `git commit --signoff` and open a PR
6. Wait for the CI process to finish and make sure all checks are green
7. A maintainer of the project will be assigned, and you can expect a review within a few days

## Roadmap

[Roadmap](Roadmap.md)

## Release-flow

[Release-flow](Release-flow.md)

## Members

[All KubeClipper members here](members.md)

## Inspire By

* [dapr/community](https://github.com/dapr/community)
* [kubesphere/community](https://github.com/kubesphere/community)

## Daily Work

1. We will check if there are any PR that need to be merged every week.
2. We will check if there are any issue that need to be solved every week.
3. We will regularly check the versions released by k8s,and do conformance test on KubeClipper and maintain it within the last 3 versions.
