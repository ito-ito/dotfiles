# dotfiles

<!-- イメージ等あればここに -->

## Overview

<!-- 概要はここに -->

macOS 用の dotfiles

&emsp;

## Requirement

<!-- 環境や、必要なライブラリなどはここに -->

- [macOS](https://www.apple.com/jp/macos/ventura/) - v13.3

&emsp;

## Usage

<!-- 使い方はここに -->

1. Clone

   ```shell
   git clone https://github.com/ito-ito/dotfiles.git ~/dotfiles
   ```

1. Install Homebrew
   [Homebrew](https://brew.sh/)

1. Install required packeges

   ```shell
   brew install stow
   ```

1. Make
   ```shell
   make
   ```

&emsp;

## Description

<!-- より詳細な説明や使い方について -->

### ghq

ghq はデフォルトで`$HOME/ghq`配下にリポジトリを配置します。
これを`$HOME/src`に変更します。

```shell
git config --global ghq.root '~/src'
```

&emsp;

## Reference

<!-- 参考URLがあればここに -->

&emsp;

## Author

[ito-ito](https://github.com/ito-ito)
