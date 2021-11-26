# My Brewfile

## Homebrew install 

```
$ /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
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
