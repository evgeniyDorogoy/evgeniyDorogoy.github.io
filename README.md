# evgeniyDorogoy.github.io

A personal blog of Evgeniy Dorogoy

## Dependencies
* ruby >= 2.6.10
* bundler >= 1.17.2

## Development

> **_NOTE:_** Only MacOS is supported for now.

1. Make sure you have `Ruby` installed (assuming you use `Homebrew`):

```bash
brew update && brew install chruby ruby-install
```

for more details of `Ruby` installation 
see [this](https://www.moncefbelyamani.com/how-to-install-xcode-homebrew-git-rvm-ruby-on-mac/) tutorial

2. `Bundler` is a [dependency manager](https://bundler.io/) for `Ruby`, 
it ships as part of `Rubi` installation from above. Make sure that you have it installed:

```bash
bundler -v
```

3. Init `bundler` inside the project root directory by executing next command, provide 
`bundler` install path:

```bash
bundler init && bundler config set --local path 'vendor/bundle'
```

4. Install `Jekyll:
```bash
bundler add jekyll
```

5. Create new `src` directory inside of the project directory, cd into it and init `Jekyll`:

```bash
mkdir src && cd src && jekyll new --skip-bundle .
```

## TODO

1. Rename this github repo with lowercase letters only

