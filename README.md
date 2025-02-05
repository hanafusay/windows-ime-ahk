# ctrl-ime-ahk

> forked from https://github.com/karakaram/alt-ime-ahk

## 概要

左右 Ctrl キーの空打ちで IME を OFF/ON する AutoHotKey スクリプトです。

* 左 Ctrl キーの空打ちで IME を「英数」に切り替え
* 右 Ctrl キーの空打ちで IME を「かな」に切り替え
* Ctrl キーを押している間に他のキーを打つと通常の Ctrl キーとして動作

## 動作環境

* Windows10,11

## 使い方

[ctrl-ime-ahk v1](https://github.com/hanafusay/ctrl-ime-ahk/releases/tag/v1.0.0) から ctrl-ime-ahk.zip をダウンロードして解凍し、ctrl-ime-ahk.exe を好きな場所に置き、起動してください。 タスクトレイに常駐します。

終了する場合はタスクトレイのアイコンを右クリックし、「終了」をクリックしてください。

アンインストールは ctrl-ime-ahk.exe を削除するだけで OK です。

## JetBrains 製の IDE で使う場合は Tool Buttons をオンに

IntelliJ IDEA など JetBrains 製の IDE をお使いの方は「上部メニューバー　＞　View　＞　Tool Buttons」をオンにしてください。

オフのまま使うと Ctrl キーを離した際に ctrl-ime-ahk.exe がエラー終了します。

## 参考
https://so-zou.jp/software/tool/system/auto-hot-key/tool/compiler.htm#context-menu