# aurci [![Build Status](https://travis-ci.com/Thalhalla/aurci.svg?branch=master)](https://travis-ci.com/Thalhalla/aurci)

Use [Travis CI] for building and packaging a few packages from [AUR] and deploy them to [GitHub Releases] so it can be used
as repository in [Arch Linux].

## Setup

On GitHub:
  - Generate a personal access token with scope `public_repo`.

On Travis CI:
  - Add a `GITHUB_TOKEN` environment variable with the personal access token code as value.

[GitHub Releases]: https://github.com/Thalhalla/aurci/releases
[Arch Linux]: https://www.archlinux.org
[Travis CI]: https://travis-ci.com/Thalhalla/aurci
[AUR]: https://aur.archlinux.org
