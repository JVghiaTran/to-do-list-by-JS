## Stack

* [Grunt - task runner](https://gruntjs.com/)
* [SCSS - CSS preprocessor](http://sass-lang.com/)
* [ECT - template engine](http://ectjs.com/)
* [SCSS Lint](https://github.com/brigade/scss-lint)

## Installation

### Install brew - Mac OSX package manager
```
/usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
```

### Install SASS and SCSS Lint
```
gem install sass scss_lint
```

If you got permission denied error

```
sudo gem install sass scss_lint
```

### Install node and npm - javascript package manager
```
brew install node@6
```

### Install grunt - task runner
```
npm install -g grunt-cli
```

### Config npm path
```
echo 'export PATH="/usr/local/opt/node@6/bin:$PATH"' > ~/.bash_profile
source ~/.bash_profile
```

### Install dependencies
```
cd /path/to/html-starter && npm install
```

## Usage

### Start a server
```
npm run server
```

### Build scss and js files
```
grunt build
```

### Watch files change
```
grunt watch
```

### Check css style
```
npm run scss-lint
```
