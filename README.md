# Some usefull stuff for setting up my machines

## Setting up terminal

### Install oh-my-posh

you need Nerd font for this to work, more info here: https://ohmyposh.dev/docs/configuration/fonts 

Windows:
```
winget install oh-my-posh
```

MacOS:
```
brew install jandedobbeleer/oh-my-posh/oh-my-posh
```

### Configure oh-my-posh

Use this guide to configure your prefered terminal:
https://ohmyposh.dev/docs/installation/prompt

use oh-my-posh-profile.json in this repo as profile

```
oh-my-posh init pwsh --config 'https://raw.githubusercontent.com/haavardg/dev-resources/main/oh-my-posh-profile.json' | Invoke-Expression
```
