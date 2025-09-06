# Copymangle

A (very bad) attempt to improve the (even worse) [Copyparty](https://github.com/9001/copyparty) UI

# Usage

The easiest way to do this is via a single line in your conf or as a flag

```sh
copyparty --html-head='<link rel="stylesheet" href="https://blade04208.github.io/copymangle/main.css">'
```

```yaml
[global]
html-head: <link rel="stylesheet" href="https://blade04208.github.io/copymangle/main.css">
```

# development / manual install
(this will dump it into home, sorry for the clutter)
```sh
cd ~
git clone https://github.com/blade04208/copymangle.git
copyparty --html-head='<link rel="stylesheet" href="/copymangle/main.css">'
```
with this, every reload (even non-force ones) will reload the stylesheet if it has changed :)