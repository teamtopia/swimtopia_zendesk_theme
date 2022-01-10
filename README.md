# SwimTopia Zendesk Theme

This theme is a fork of the [Copenhagen Theme](https://github.com/zendesk/copenhagen_theme) provided as the default theme for Zendesk's help center. Our goal is to track that theme very closely with minimal changes. See the [local changelog](./LOCAL_CHANGELOG.md) for details.

## Releases & Local Tags
New releases should be done for any changes that we make and/or updates from upstream. The naming convention for our release tags is `vX.X.X-local`. Use the updated version from `manifest.json` and a `-local` postfix to help differentiate our releases from upstream tags/releases.

When doing a release, the following steps are required:
1. Update the version in `manifest.json` (follow semantic versioning)
2. Update the changelog
3. Commit all the changes
4. Create a release tag & release
5. Update the theme on Zendesk following [this guide](https://support.zendesk.com/hc/en-us/articles/4408844123162).
