# Github Actions
Quickstart:
* copy and paste `.github/` into your own projects
* merge in the commit with this inclusion to enable the actions

> Optional: read below for more configuration options available for you.

## Size Labeler
https://github.com/marketplace/actions/assign-size-label

Project specific changes can be done at `.github/workflows/size-labeler.yml` under the field `IGNORED`.<br>
All project sizes are taken from kubenetes repo found [here](https://github.com/kubernetes/kubernetes/labels?q=size).

## PR Labeler
https://github.com/marketplace/actions/pr-labeler

Project specific changes can be done at `.github/pr-labeler.yml` which contains labels to be tagged automatically.<br>
You can view the config file to see all labels that are auto labelled.

> Note: Only PR of the format `<type>--<your branch>` will be checked for auto labelling.

## Release Drafter
https://github.com/marketplace/actions/release-drafter

Project specific changes can be done at `.github/release-drafter.yml` which contains configuration for how the releases will be drafted.

> Note: only commits done after Release Drafter has been included will be included.
