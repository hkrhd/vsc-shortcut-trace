## 概要
VS Codeでショートカット実行されたコマンドIDをステータスバーに表示する拡張機能を目指す。

## 現状
コマンド実行を監視するAPIが現行のVS Codeに存在しないため、APIが再実装されるまで実装を保留する。
過去には `onDidExecuteCommand` が proposed API として存在したが現在は削除されている。

## 予定
APIが再実装された場合は、提案APIを有効化して利用する。
配布は GitHub Releases に vsix を置く。
