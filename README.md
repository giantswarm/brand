# Giant Swarm Brand Resources

Giant Swarm logo files and icons for download. When in doubt about the usage of an asset, please contact support@giantswarm.io or use the `#branddev` channel on Slack.

Copyright 2015 - 2020 Giant Swarm GmbH - All rights reserved

## Logo variations overview

### Standard

![Standard logo](https://raw.githubusercontent.com/giantswarm/brand/v1.0.0/logo/standard/giant-swarm-logo.svg)

Found in [`/logo/standard`](https://github.com/giantswarm/brand/tree/master/logo/standard).

### Greyscale

![Greyscale logo](https://raw.githubusercontent.com/giantswarm/brand/v1.0.0/logo/greyscale/giant-swarm-logo.svg)

Found in [`/logo/greyscale`](https://github.com/giantswarm/brand/tree/master/logo/greyscale).

### White

(Not visible on a white background)

![White logo](https://raw.githubusercontent.com/giantswarm/brand/v1.0.0/logo/white/giant-swarm-logo.svg)

Found in [`/logo/white`](https://github.com/giantswarm/brand/tree/master/logo/white).

### Special purpose

Logo variations for specific purposes can be found in [`/logo/special-purpose`](https://github.com/giantswarm/brand/tree/master/logo/special-purpose). The file name indicates the purpose.

## Publishing long-lived asset URLs

If you need to give access to an asset via a URL, please use the URL format as below, to ensure that the content served via this URL never changes:

    https://raw.githubusercontent.com/giantswarm/brand/<tag>/<path>

Example:

    https://raw.githubusercontent.com/giantswarm/brand/v1.0.0/logo/special-purpose/cncf-landscape-stacked.svg

Here, `<tag>` is a [release](https://github.com/giantswarm/brand/releases) tag and `<path>` is the path of the file in the repositorie's file tree.

## Releases

We create releases in this repository to facilitate versioning and publishing via URLs, as described above.

We use [Semver](https://semver.org/) versioning roughly in the following way:

- PATCH updates are made for changes that add a non-substantial asset, like a new file format for an existing asset.
- MINOR updates are made for changes that add a substantial asset, like a new logo variation.
- MAJOR updates are made for changes that remove any file or move any file to a different position in the file tree.
