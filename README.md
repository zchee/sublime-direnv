# Sublime-direnv

[sublime-gulp](https://github.com/NicoSantangelo/sublime-gulp), [sublime-vagrant](https://github.com/Stubbs/sublime-vagrant), These are awesome package.  
But, I use direnv, so not working.

That is why I made this.

# Instration

## Package Control

If you have PackageControl installed, you can use it to install the package.

### Warning!
It has not been merged into Package Control still

## Manual
You can clone the repository in your `/Packages` folder.

```
git clone git@github.com:fainder/sublime-direnv.git ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/sublime-direnv
```

# Usage
When there is .envrc file to open project, choose `Direnv allow` from the command pallete.


## .envrc Sample
Do

```
export VAGRANT_IP=192.168.33.10
export THEME_DIR=_theme
export CSS_DIR=_theme/css
export JS_DIR=_theme/js
export SASS_DIR=_theme/sass
export IMG_DIR=_theme/img
```

Do not 

```
export VAGRANT_IP=192.168.33.10
export THEME_DIR=_theme
export CSS_DIR=$THEME_DIR/css
export JS_DIR=$THEME_DIR/js
export SASS_DIR=$THEME_DIR/sass
export IMG_DIR=$THEME_DIR/img
```

# Todo
It later to modify it because I wrote for myself!

- `direnv deny` support.
- `direnv reload` support.
- Refactoring.
