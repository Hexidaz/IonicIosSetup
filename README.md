# NodeJS & NPM Installation
$ curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash

On bashrc or zshrc
> export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
> [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm

```
$ nvm install --lts=erbium
```

# Ionic and its dependencies
$ npm install -g ionic@4.12.0
$ npm isntall -g --save @angular/cli
$ npm install -g cordova
$ npm install -g ios-sim
$ gem install cocoapods

# Homebrew
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
$ brew install ios-deploy


# XCode
$ xcode-select --install
```Go to Xcode » Preferences » Accounts, and add account
