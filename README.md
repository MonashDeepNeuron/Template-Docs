# Template Docs

Various templates of common documents and files used throughout Monash DeepNeuron's repositories. This includes licenses, templates for issues, contribution guidelines and more.

The files [`README.md`](README.md), [`CONTRIBUTING.md`](CONTRIBUTING.md), [`UNLICENSE`](UNLICENSE) and [`CODE_OF_CONDUCT.md`](CODE_OF_CONDUCT.md) pertain to the functioning of this repository and aren't strictly templates (but can be used as such if deemed useful).

This repository is Unlicensed.

## Table of Contents

- [Template Docs](#template-docs)
  - [Table of Contents](#table-of-contents)
  - [Templates](#templates)
    - [`README.md`](#readmemd)
    - [`LICENSE`](#license)
    - [`CODE_OF_CONDUCT.md`](#code_of_conductmd)
    - [`CONTRIBUTING.md`](#contributingmd)
    - [`.gitignore`](#gitignore)

## Templates

### `README.md`

This file acts as an overview of your repository. It is the first thing user view when looking at you repository. It should contain the most vital information pertaining to your project.

- [Basic](README-template.md) - A basic `README.md` template.

### `LICENSE`

This is the projects software license and governs the usage, distribution availability of a software project. Many licenses have info that must be filled in by the software owners such as dates and names.

- [AGPL-v3](licenses/AGPL-v3) - GNU Affero General Public License, a free copy left license similar to GPL-v3 but has an addition term to allow users who interact with the licensed software over a network to receive the source for that program.
- [Apache-2.0](licenses/) - A copyright license allow anyone modify the original source as long as the source retains its original Apache-2.0 license and as the modifications are listed in the distribution of the modified source. Authors of Apache-2.0 licensed source cannot be help liable under this license.
- [BSL-1.0](licenses/) - Simple copyright license allow anyone to do whatever they want with BSL-1.0 license software as long as the software retains it original BSL-1.0 license unless distributed as a compiled binary.
- [GPL-v2](licenses/GPL-v2) - GNU General Public License Version 2, a free copy left license.
- [GPL-v3](licenses/GPL-v3) - GNU General Public License Version 3, a free copy left license similar to GPL-v2 but with stricter copyleft requirements.
- [LGPL-v3](licenses/LGPL-v3) - GNU Lesser General Public License Version 3, a free copy left license similar to GPL-v3 but LGPL-v3 software is able to be used and modified with non-GPL-v3 license source as longe as th originally LGPL-v3 licensed source retains its original license and the LGPL-v3 source cna be replaced with other source with no effect on the end users usage of the compiled program.
- [MIT](licenses/) - Simple copyright license allow anyone to do whatever they want with MIT license software as long as the software retains it original MIT license. Authors of MIT licensed source cannot be help liable under this license.
- [MPL-2.0](licenses/) - Mozilla Public License Version 2.0, is a middle ground license that aims to balance the benefits of permissive licenses like MIT and copyleft licenses like GPL-v3.
- [Unlicense](licenses/) - A license that releases the software into the public domain.

### `CODE_OF_CONDUCT.md`

This file specifies how contributors to this repository must conduct themselves in relation to collaborating with other people.

- [Contributor Covenant](CODE_OF_CONDUCT-Contributor-Covenat.md) - The Contributor Covenant Code of Conduct
  - [Homepage](https://www.contributor-covenant.org/)

### `CONTRIBUTING.md`

This file is used to specify the contributing guidelines for a repository.

- [General](CONTRIBUTING-general-template.md) - Template for contributing guide for any kind of repository (ie. non-specific).
- [mdBook](CONTRIBUTING-mdbooks-template.md) - Template contributing guide for mdBook based repositories.

### `.gitignore`

`.gitignore` allow you to specify file patterns that should be ignored by Git.

- [`all.gitignore`](all.gitignore) - `.gitignore` with common ignores for many different languages.
- [GitHub `.gitignore` Repository](https://github.com/github/gitignore) - This is an archive of many different `.gitignore` templates specific to different languages and tools.
