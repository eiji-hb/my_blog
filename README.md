## theme
[hugo-PaperMod](https://github.com/adityatelange/hugo-PaperMod/wiki/Installation)

## update theme
```
git submodule add https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod --depth=1
git submodule update --init --recursive # needed when you reclone your repo (submodules may not get cloned automatically)
```

## run server
```
hugo server
```
## demo
https://adityatelange.github.io/hugo-PaperMod/

## post
hugo new --kind post <name>