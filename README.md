This repository exists to test that various packages retain compatibility with
the latest version of [Flow](https://flow.org/).

This repository depends on flow-bin and various npm packages. The package.json
file defines a test script which runs flow to check the other dependencies.
[Greenkeeper](https://greenkeeper.io/) opens a PR to this repo whenever any of
the dependencies (including Flow) has a major update, and
[CircleCI](https://circleci.com/) tests the PR.
