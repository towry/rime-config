# Rime config

## Mac version.

Config folder path: `~/Library/Rime`

After install the Rime, Use `plum` package manage to
install the input scheme. https://github.com/rime/plum

### Install plum

```bash
// this will clone to a local repo named `plum`
curl -fsSL https://git.io/rime-install | bash
```

#### Install a scheme

List of schemes:

https://github.com/rime/plum#phonetic-based-input-methods

- luna-pinyin
- wubi
- emoji

```bash
cd plum
bash rime-install luna-pinyin
```
