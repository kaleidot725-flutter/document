# 2020/03/15 State Management

# State management
- 特になし

# Think declaratively
- Flutter は宣言的な UI を持つ
- アプリの状態 が変化するとインタフェースの再描画される

# Ephemeral vs app state

## Ephemeral State

- １つの Widget に含められる状態のこと
- Page View の現在ページ、複雑なアニメーションの進捗、現在選択されているタブの状態

## App State

- 一時的ではなくアプリ全体で管理したい状態のこと
- ユーザー設定、ログイン情報、ソーシャル・ネットワーキングアプリでの通知

## Flutter には２つの状態がある

- Ephemeral な State と App State があるが、これらはアプリを作成するときにどちらを使うか意識する必要がある。どちらを選択するかはアプリの複雑度にもよるので要検討すること


# Simple app state management

- provider パッケージを利用して、アプリを作成していく
- provider を使ったサンプルは別途作ってみる。
-  
