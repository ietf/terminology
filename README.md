# Inclusive Terminology in IETF Documents

Please see the [IESG Statement on Inclusive
Language](https://www.ietf.org/about/groups/iesg/statements/on-inclusive-language/),
which documents the current IETF community consensus on encouraging to use the
guidance in [NISTIR
8366](https://nvlpubs.nist.gov/nistpubs/ir/2021/NIST.IR.8366.pdf) when making
contributions to the IETF.

## Automated checking on GitHub

This repo contains a [configuration file](.github/in-solidarity.yml) for
[in-solidarity-bot](https://github.com/apps/in-solidarity) that flags some of
the terms in [the NIST Technical Series Publications Author
Instructions](https://www.nist.gov/nist-research-library/nist-technical-series-publications-author-instructions#inclusive)
in new commits and pull requests.

If you want to use this configuration, you will of course need to install and
enable the [in-solidarity-bot](https://github.com/apps/in-solidarity) for your
repo or organization, so do that first by [clicking "Configure" on this
page](https://github.com/apps/in-solidarity) and then enabling the bot
accordingly.

After enabling [in-solidarity-bot](https://github.com/apps/in-solidarity),
execute these shell commands at the top-level directory of the target repo:

``` shell
mkdir .github
echo "_extends: ietf/terminology" > .github/in-solidarity.yml
git add .github/in-solidarity.yml
git commit -m "Add in-solidarity-bot config"
```

This will create and commit a `.github/in-solidarity.yml` file that uses the
configuration provided in this repo to check future commits and pull requests in
your repo.

Please note that there *will* be false positives due to the use of regular
expressions for the checks.
