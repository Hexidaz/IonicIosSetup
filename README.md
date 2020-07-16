# NodeJS & NPM Installation
Install NVM (Node Version Manager)
```
$ curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.35.3/install.sh | bash
```
On your `.bashrc` or `.zshrc` there should be this line:
```
export NVM_DIR="$([ -z "${XDG_CONFIG_HOME-}" ] && printf %s "${HOME}/.nvm" || printf %s "${XDG_CONFIG_HOME}/nvm")"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh" # This loads nvm
```
Install node and npm
```
$ nvm install --lts=erbium
```

# Homebrew
Install Homebrew
```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

# Ionic and its dependencies
```
$ npm install -g ionic@4.12.0
$ npm isntall -g --save @angular/cli
$ npm install -g cordova
$ npm install -g ios-sim
$ brew install ios-deploy
$ gem install cocoapods
```

# XCode
If you install XCODE from appstore then this may be neglected
```
$ xcode-select --install
```
Go to Xcode » Preferences » Accounts, and add account
