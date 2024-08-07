# Hugo UI Custom

Extended base theme for Hugo **SITE-0003**.

## Install

```sh
git submodule add 'https://github.com/s8956/ui-custom.git' 'themes/ui-custom'
```

## Update

```sh
git submodule update --recursive --remote --merge
```

## Uninstall

```sh
m='ui-custom'; git submodule deinit -f "themes/${m}"; git rm -r --cached "themes/${m}"; rm -rf ".git/modules/themes/${m}"; rm -rf "themes/${m}"
```
