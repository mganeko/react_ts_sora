# React.js - Sora Example

React.js exmaple for [Sora Labo](https://sora-labo.shiguredo.jp).

これは WebRTC SFU Sora の検証サービス [Sora Labo](https://sora-labo.shiguredo.jp) 向けの、React.jsによるサンプルです。

- [sora-js-sdk](https://github.com/shiguredo/sora-js-sdk) を利用しています(Apache 2.0 ライセンス)

## LICENSE / ライセンス

- MIT LICENSE / MITライセンス


# 利用方法

## 事前準備

- GitHub アカウントで、[Sora Labo](https://sora-labo.shiguredo.jp) にサインアップ
- シグナリングキーを取得

## GitHub Pages で実行

- ブラウザを2つ起動、それぞれ https://mganeko.github.io/reactjs_sora/ にアクセス
- Video Codec を選び、[Start Video]ボタンをクリック
- SignalingKey: に Sora Labo のシグナリングキーを入力
- Room: にルーム名(Channel名)を入力
  - Username@RoomID の形式 
- [Coonect]ボタンをクリックして接続

URLを次の形式で指定することで、シグナリングキーとルーム名を指定可能

- https://mganeko.github.io/reactjs_sora/?room=ルーム名&key=シグナリングキー


## 開発環境で実行

- $ git clone https://github.com/mganeko/reactjs_sora.git
- $ cd reactjs_sora
- $ npm install 
- $ npm start
- http:localhost:3000 にブラウザでアクセス
- その後は GitHub Pages の例と同様 

## 自分のサーバーで実行

- $ git clone https://github.com/mganeko/reactjs_sora.git
- $ cd reactjs_sora
- $ npm install 
- $ npm run build
- build/ 以下をWebサーバーに配置(要https)
- 配置したWebサーバーにブラウザーでアクセス
- その後は GitHub Pages の例と同様 

