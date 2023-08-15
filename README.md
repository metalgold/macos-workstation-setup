# How to set up a Mac Workstation

Install Homebrew:

```
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

Install casks (includes proprietary software):

```
brew install --cask mattermost slack visual-studio-code keepassxc thunderbird tunnelblick coconutbattery jetbrains-toolbox zoom rancher
```

Install everything else

```
brew install starship terraform saml2aws awscli k9s kubectx 
```

Install sdkman

```
curl -s "https://get.sdkman.io" | bash
```

Install nvm (node version manager):

```
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.4/install.sh | bash
```
