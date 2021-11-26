# My Brewfile

## Homebrew install 

```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
$ echo 'eval "$(/opt/homebrew/bin/brew shellenv)"' >> /Users/yoji/.zprofile
$ eval "$(/opt/homebrew/bin/brew shellenv)"
$ brew -h
```

see. https://brew.sh/index_ja

## Make sure git is installed

```
$ git -v
```

### if not..

```
$ brew update
$ brew install git
```

## Install appications with brew

```
$ git clone git@github.com:yojishiraki/Brewfile.git
$ cd Brewfile
$ brew bundle
```
