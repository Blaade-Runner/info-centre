![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=green)

---

## Delete existing key

+ $ `gpg --list-secret-keys`
+ $ `gpg --list-keys`
+ $ `gpg --list-secret-keys --keyid-format=long`
+ $ `gpg --delete-secret-key` **`<secret-key-id>`**
+ $ `gpg --delete-key` **`<key-id>`**

## Edit Key

- $ `gpg --edit-key` **`<key-id>`**
- `gpg> passwd`
- `gpg> save`

## Adding new key

- $ `gpg --full-generate-key`
- $ `gpg --list-secret-keys --keyid-format=long`
- $ `gpg --armor --export` **`<key-id>`**
    - > _**Prints the GPG key ID, in ASCII armor format.**_
    _**Copy key and add it to github account.**_ (`Settings`>`Access`>`SSH and GPG keys`>`New GPG key`)
- $ `git config --global user.signingkey` **`<key-id>`**

---
> `Noor Salim`

[gpg]: <https://>
