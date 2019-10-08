# Talks

Here are some of the talks I gave:

- [2019-09-25 - Passwords](./2019-09-passwords/passwords.html)

## Install

```shell
git clone
git submodule init
```

## Compile

### Output to reveal.js

```shell
pandoc --to=revealjs --standalone talk.md --output=talk.html
```

### Output to LaTeX Beamer

```shell
pandoc --to=beamer --standalone talk.md --output=talk.pdf
```
