# Maintenance notes

Not part of the public site (not linked from `index.md`/`README.md`) - for
whoever maintains this repo.

## Privacy policy sync

`privacy-policy.md` in this repo is **not edited here by hand**. Its single
source of truth is `app/src/main/assets/privacy_policy.md` in the
`nailbase-app` repository - the same file the app's offline Privacy Policy
screen loads. To update this page after that file changes:

1. In a local clone of `nailbase-app`, run `scripts/sync_privacy_policy.sh`
   (optionally pass the path to your local clone of this repo as the first
   argument - it defaults to `../nailbase-privacy`).
2. Review the diff here, commit and push.

This is a manual, on-demand step (run before publishing a policy update),
not automated CI/CD.
