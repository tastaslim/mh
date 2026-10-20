# mh — MergeHarbor from your terminal

`mh` reviews the changes on your machine before you push them, shows the review status of your branch's pull request, sets up a repository, and validates `.mergeharbor` configuration.

This repository hosts release downloads only. Documentation: https://mergeharbor.com/docs/cli/

## Install

```sh
brew install tastaslim/tap/mh
```

Or download the archive for your platform from [Releases](https://github.com/tastaslim/mh/releases), check it against `checksums.txt`, and put `mh` on your `PATH`.

## Get started

```sh
mh login      # opens your browser to approve the sign-in
mh review     # review local changes before pushing
```

Use of `mh` is subject to the MergeHarbor Terms of Service: https://mergeharbor.com/legal/terms
