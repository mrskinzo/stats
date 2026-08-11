# stats

Generates the animated stat cards for [my profile README](https://github.com/mrskinzo).

Based on [jstrieb/github-stats](https://github.com/jstrieb/github-stats) (last Python version, vendored). The workflow runs weekly on Monday, or on manual dispatch, and commits fresh SVGs to `generated/`.

Runs on the built-in job token by default (public stats only). An optional `ACCESS_TOKEN` secret (classic PAT, `read:user` + `user:email` only) can replace it. Do not give the token the `repo` scope.
