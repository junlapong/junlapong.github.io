Termux
======

## copy to clipboard

### 1. install termux api

```
pkg install termux-api
```

### 2. test

```
termux-clipboard-get
```

### 3. set alias as pbcopy

```
cd ~
echo 'alias pbcopy=termux-clipboard-set' >> .bashrc
echo 'alias pbpaste=termux-clipboard-get' >> .bashrc
source .bashrc
```

