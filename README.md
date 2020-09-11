# Giant Swarm Brand Resources

Giant Swarm logo files and icons for download. When in doubt about the usage of an asset, please contact support@giantswarm.io or use the `#branddev` channel on Slack.

Copyright 2015 - 2020 Giant Swarm GmbH - All rights reserved

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
