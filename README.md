# 16921

Reproduction for [issue #16921 on renovatebot/renovate](https://github.com/renovatebot/renovate/issues/16921).

## Current behavior:

Renovate does not use our `togithub.com` redirect domain for _all_ links in the pnpm `7.6.0` changelog.
This causes hundreds of backlinks to the `pnpm` project's own PRs.

## Expected behavior:

Renovate uses our `togithub.com` redirect domain for _all_ links in the pnpm `7.6.0` changelog.
