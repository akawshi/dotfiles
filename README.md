# dotfiles
config, settings, environment and other dotfiles for me

## Sheldon
If using pre-build binary package, you can get it on [the release page](https://github.com/rossmacarthur/sheldon/releases).

1. Move sheldon executable file to `/.local/bin`

```
mv sheldon ~/.local/bin
sheldon --version
```

2. First init

```
sheldon init --shell zsh
```

3. Install plugins

```
sheldon add hoge --github hoge/hogehoge
```