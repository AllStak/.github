# `AllStak/.github`

This repository hosts the AllStak organization's community health files —
the artifacts GitHub renders across every repo under this org and on the
organization profile page.

## Contents

| Path | Purpose |
|---|---|
| [`profile/README.md`](./profile/README.md) | Rendered at [github.com/AllStak](https://github.com/AllStak) as the organization profile. |

Additional community health files (`SECURITY.md`, `CODE_OF_CONDUCT.md`,
`CONTRIBUTING.md`, `SUPPORT.md`, issue / pull-request templates) will live
here as we adopt them. GitHub uses any file placed at the root of this
repository as the default for every org repo that doesn't ship its own
copy — see [GitHub's documentation on
default community health files](https://docs.github.com/en/communities/setting-up-your-project-for-healthy-contributions/creating-a-default-community-health-file)
for the full list and resolution order.

## Updating the organization profile

```bash
git clone https://github.com/AllStak/.github.git
cd .github
$EDITOR profile/README.md
git commit -am "profile: <what changed>"
git push
```

GitHub caches the rendered profile for a short period after each push.

## Where the rest lives

| | |
|---|---|
| Product website | <https://allstak.sa> |
| Documentation | <https://docs.allstak.sa> |
| Changelog | <https://changelog.allstak.sa> |
| Status | <https://allstak.sa/en/status> |
| Security | <https://allstak.sa/en/security> |
| Contact | [hello@allstak.sa](mailto:hello@allstak.sa) |

## License

The contents of this repository are AllStak organization assets. SDK and
product code lives in separate, per-project repositories under this org —
each repository carries its own license.
