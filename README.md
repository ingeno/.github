# github settings

![](https://github.com/ingeno/.github/workflows/Validate%20YAML%20files/badge.svg)

This repository defines basic, shareable settings for Ingeno repositories.

It can also be used to [define default community files](https://help.github.com/en/github/building-a-strong-community/creating-a-default-community-health-file).
This can be useful to create issue or pull requests templates.


## Usage

Files defined in [.github](.github/) (excluding [settings.yml](.github/settings.yml)) contain configurations that can be
extended by other repositories in this organization. For more details, see [probot-config/recipes](https://github.com/probot/probot-config#recipes).


## Repository Templates

The Ingeno Github organization defines a few [repository templates](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/creating-a-repository-from-a-template)
meant to make it easy to start a new project without dealing with some of the boilerplate.

The most basic one, from which most other templates are created from is [customer-template](https://github.com/ingeno/customer-template).
This is the best starting point if you want to create another template for a specific tech stack.

The following templates can be of interest:

- [customer-template](https://github.com/ingeno/customer-template)
- [typescript-template](https://github.com/ingeno/typescript-template)
- [javascript-react-template](https://github.com/ingeno/javascript-react-template)


## Contributing

### Validation

To validate settings, simply run `npm run lint`.

### Github workflows

To validate Github workflows before pushing a PR, simply run `npm run lint:workflows`.
