# asdf-cru-cli
[cru-cli](https://github.com/CruGlobal/cru-cli) plugin for [asdf package manager](https://asdf-vm.com).

## Install
Ensure you have asdf [installed](https://asdf-vm.com/guide/getting-started.html) and the [GitHub CLI](https://github.com/cli/cli#installation) installed.
Since the `cru-cli` repository is private, you will need to have the GitHub CLI authenticated with your GitHub account.

#### Install plugin
```shell
gh auth login
asdf plugin-add cru-cli https://github.com/CruGlobal/asdf-cru-cli
```

#### Install `cru-cli` version
```shell
# Show all installable versions
asdf list-all cru-cli

# Install latest version
asdf install cru-cli latest

# Install specific version
asdf install cru-cli <version>

# Set a version globally (on your ~/.tool-versions file)
asdf global cru-cli latest
```
