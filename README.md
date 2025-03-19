<img src="https://avatars.githubusercontent.com/u/1785912?s=96&v=4" alt="Cru logo" title="Cru" align="right" height="96" width="96"/>

# asdf-cru-cli
[cru-cli](https://github.com/CruGlobal/cru-cli) plugin for [asdf package manager](https://asdf-vm.com).

## Requirements
- [asdf version manager](https://asdf-vm.com/) `v0.16.0` or later
- [GitHub CLI](https://cli.github.com/) `v2.68.0` or later

## Install
Ensure you have [asdf](https://asdf-vm.com/guide/getting-started.html) installed and the [GitHub CLI](https://github.com/cli/cli#installation) installed.
Since the `cru-cli` repository is private, you will need to have the GitHub CLI authenticated with your GitHub account.
You can check GitHub CLI authentication status with `gh auth status` or re-authenticate with `gh auth login`.

#### Install plugin
```shell
asdf plugin add cru-cli https://github.com/CruGlobal/asdf-cru-cli
```

#### Install `cru-cli` version
```shell
# Show all installable versions
asdf list all cru-cli

# Install latest version
asdf install cru-cli latest

# Install specific version
asdf install cru-cli <version>

# Set a version globally (on your ~/.tool-versions file)
asdf set -u cru-cli latest
```
