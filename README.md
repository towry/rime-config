# Rime config

## Mac version.

Config folder path: `~/Library/Rime`

Soft link those files to config folder.

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

https://github.com/rime/rime-wubi

- luna-pinyin
- wubi
- emoji
- wubi_pinyin

```bash
cd plum
bash rime-install luna-pinyin wubi pinyin-simp
```
