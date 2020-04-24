# github settings

![](https://github.com/ingeno/.github/workflows/Validate%20YAML%20files/badge.svg)

This repository defines basic, shareable settings for Ingeno repositories.

It can also be used to [define default community files](https://help.github.com/en/github/building-a-strong-community/creating-a-default-community-health-file).
This can be useful to create issue or pull requests templates.


## Usage

Files defined in [.github](.github/) (excluding [settings.yml](.github/settings.yml)) contain configurations that can be
extended by other repositories in this organization. For more details, see [probot-config/recipes](https://github.com/probot/probot-config#recipes). 


## Contributing

### Validation

To validate settings, simply run `npm run lint`.

### Github workflows

To validate Github workflows before pushing a PR, simply run `npm run lint:workflows`.
