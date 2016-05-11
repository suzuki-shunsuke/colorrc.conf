# colorrc.conf

ls コマンドの色設定

```
$ ln -s $PWD/.colorrc ~/.colorrc
```

ls のエイリアス設定をしておく。

```
alias ls='ls --color=auto'
```

## .colorrcの作り方

```
$ dircolors -p > ~/.colorrc
```

環境に合わせて設定を編集
