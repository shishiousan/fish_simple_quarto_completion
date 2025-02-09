# fish_simple_quarto_completion

Fish shell script to implement some completions for quarto-cli

Not fully configured (I am noob in Quarto and fish shell).
But you can extend this easily.

## How to install

- [fisher](https://github.com/jorgebucaran/fisher)

```shell
fisher install shishiousan/fish_simple_quarto_completion
```

- Manually
  Copy `/completions/quarto.fish` to your `~/.config/fish/completions/` folder and reload your fish shell.

## How to use

Press the `tab` key depending on the situation, for example,
after `quarto render -`.
Maybe you can achieve suggestion or auto-completion.

Supported commands are below.

## Which commands are supported

Several commands are supported
but not all options are included.
If you want to know the list of options, including not supported ones in this plugin,
please run `quarto commandname --help`.

- render
- publish
- preview
- create
- convert
