# Stencil (@mgsisk/stencil)

Opinionated template for generating new repositories.

[![Latest release][badge-release]][url-release]
[![Build status][badge-build]][url-build]
[![Code quality][badge-quality]][url-codacy]
[![Test coverage][badge-coverage]][url-codacy]
[![Maintainer funding][badge-funding]][url-funding]

Stencil is an opinionated template for generating new repositories. It provides
a basic directory structure and standardized set of [community health files][]
to jump start your project with the resources necessary to build a healthy and
effective environment for collaboration. Use as-is with minor customizations,
or create your own template with Stencil as the starting point.

## Installation

```sh
git clone https://github.com/mgsisk/.github.git project
cd project
rm -rf .git
git init
```

If you're hosting on [GitHub][], you can also [generate a new repository][]
directly from Stencil.

## Usage

You should review each of the files Stencil provides and customize them to your
liking. Refer to the [documentation][] for useful information on each file:
what they're for, why you should or shouldn't keep them, and how you might
want to customize them. Other [support resources][] are available if you need
help.

## Contributing

[Contributions][] are always welcome; please read the [code of conduct][]
before you begin. See the [changelog][] for notable project changes, and report
any [security][] concerns you find.

## Thanks

To the [contributors][] that help to build, fund, and maintain this project;
the [other works][] that have contributed to and inspired this project; and
anyone that has found this project useful.

## License

[ISC][]

[badge-build]: https://img.shields.io/github/workflow/status/mgsisk/.github/build
[badge-coverage]: https://img.shields.io/codacy/coverage/.github
[badge-funding]: https://img.shields.io/github/sponsors/mgsisk
[badge-quality]: https://img.shields.io/codacy/grade/.github
[badge-release]: https://img.shields.io/github/v/tag/mgsisk/.github?sort=semver
[changelog]: CHANGELOG.md
[code of conduct]: CODE_OF_CONDUCT.md
[community health files]: https://help.github.com/en/github/building-a-strong-community
[contributions]: CONTRIBUTING.md
[contributors]: AUTHORS.md
[documentation]: docs
[generate a new repository]: https://github.com/mgsisk/.github/generate
[github]: https://github.com
[isc]: LICENSE.md
[other works]: THANKS.md
[security]: SECURITY.md
[support resources]: SUPPORT.md
[url-build]: https://github.com/mgsisk/github-actions-test/actions?query=workflow%3Abuild
[url-codacy]: https://app.codacy.com/gh/mgsisk/.github
[url-funding]: CONTRIBUTING.md#funding
[url-release]: https://github.com/mgsisk/.github/releases
