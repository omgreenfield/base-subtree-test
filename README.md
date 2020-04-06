# Base subtree test

This repo is one of three used to test the functionality of GitHub subtrees and GitHub Actions used to automatically push to those subtrees.

The other repos are:
- /subtree-test
- /subtree-test2

# Testing GitHub Actions

Download nektos/act

Run 
`act -P ubuntu-latest=nektos/act-environments-ubuntu:18.04 -s GITHUB_USER=<your username> -s GITHUB_TOKEN=<your token>`
