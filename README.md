Tugboat Dev Site
================

This repo is used to spin up a dev site for testing the latest changes to
Backdrop.

Contribute
----------

Follow these steps to contribute to the development and testing of this repo:

1. Register your own, free Tugboat account (you can sign up using your GitHub
   login): https://dashboard.tugboatqa.com/signup

1. Fork this repo, and add any changes you'd like to make to a new branch.

1. Create a new Tugboat project and add your fork to it.

1. Build a preview of your branch in Tugboat.

**Note that updates to this repo won't take effect until the
[`latest`](https://github.com/backdrop-ops/tugboat-demo-dev/releases/tag/latest)
tag has also been updated:**
```
git tag -f latest GIT_COMMIT_ID
git push origin latest -f
```
