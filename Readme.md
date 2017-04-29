react-ukagaka-shell-pixi
========================

Reactで伺かのシェルを描画するためのライブラリ

このライブラリは何か
------------------------

Reactやreact-pixiのような低レベルの描画ライブラリです。

伺かシェルの「スコープ」や「バルーン」という単位で描画を操作し、イベントを受け取ることが可能です。

このライブラリは何でないか
------------------------

- このライブラリは伺かのシェル「データ」を取り扱うライブラリではありません。
  narやその内容を簡単に描画する等の機能はありませんので、画像や位置を適切に読み込んだり計算した結果を用いて外部から描画操作して下さい。
- このライブラリは経時性をもつ仕様をサポートしません。
  アニメーションやクリック等経時変化する要素仕様を実現したい場合は、外部から経時的に描画操作してください。
- このライブラリは状態管理をしません。
  さくらスクリプトの\c、\C等それまでの状態を前提とするタグについては、外部でその操作の結果となる直接表示されるさくらスクリプトを計算した上で描画操作して下さい。

License
-------

This is released under [MIT License](https://narazaka.net/license/MIT?2017).
