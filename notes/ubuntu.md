## ubuntu

### enable scroll lock

```shell
xmodmap -e 'add mod3 = Scroll_Lock'
```

### install via tar.gz

```shell
sudo tar --strip-components 1 -xvzf $fileLocation -C /usr/local
```

### install via tar.xz

```shell
sudo tar --strip-components 1 -xJvf $fileLocation -C /usr/local
```
