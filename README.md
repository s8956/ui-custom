# Hugo UI Custom

Extended base theme for Hugo **SITE-0003**.

## Install

```
git submodule add 'https://github.com/site-0003/ui-custom.git' 'themes/ui-custom'
```

## Update

```
git submodule update --recursive --remote --merge
```

## Uninstall

```
m='ui-custom'; git submodule deinit -f "themes/${m}"; git rm -r --cached "themes/${m}"; rm -rf ".git/modules/themes/${m}"; rm -rf "themes/${m}"
```
