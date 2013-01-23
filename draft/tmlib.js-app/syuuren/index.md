# tmlib.js App 怒濤の修練(100)

参考

- <http://tmlife.net/programming/javascript/enchant-js-100-tips.html>


## Base
- [CanvasApp のテンプレートを作ろう](bbbbb)
- [読み込んだ画像を表示しよう](bbbbbbbbbb)
- [テキストを表示しよう](bbbbbbbbbb)
- [更新処理を登録しよう](bbbbbbbbbb)(app.update を使う)
- [マウスクリック or タッチに反応させてみよう](bbbbbbbbbb)(app.pointing を使う)


## Sprite
- [Sprite の位置を指定しよう(x, y, position, setPosition)](aaaaaaaaaaa)
- [Sprite を回転させてみよう](aaaaaaaaaaa)
- [Sprite を拡大, 縮小させてみよう](aaaaaaaaaaa)
- [Sprite に幅, 高さを指定しよう](bbbbbbbbbb)
- [Sprite を透明にしてみよう](aaaaaaaaaaa)
- [Sprite の表示/非表示を切り替えてみよう](aaaaaaaaaaa)
- [Sprite に更新処理を登録して移動させてみよう](aaaaaaaaaaa)
- [Sprite に更新処理を登録してフェードイン/フェードアウトさせてみよう](aaaaaaaaaaa)
- [Sprite をたくさん表示してみよう](aaaaaaaaa)
- [Sprite をたくさん表示してランダムに動かしてみよう](aaaaaaaaa)
- [Sprite が画面外に出ないよう制御してみよう](aaaaaaaaaaa)
- [Sprite で描画する画像の描画領域を指定してみよう](aaaaaaaaaaa)


## Shape
- [CircleShape を生成して表示しよう](aaaaaaaaa)
- [TriangleShape を生成して表示しよう](aaaaaaaaa)
- [RectangleShape を生成して表示しよう](aaaaaaaaa)
- [StarShape を生成して表示しよう](aaaaaaaaa)
- [PolygonShape を生成して表示しよう](aaaaaaaaa)
- [CircleShape に描画パラメータを指定しよう](aaaaaaaaa)
- [RectangleShape に描画パラメータを指定しよう](aaaaaaaaa)
- [StarShape に描画パラメータを指定しよう](aaaaaaaaa)
- [PolygonShape に描画パラメータを指定しよう](aaaaaaaaa)
- [Shape を使って自由に描画, 表示しよう](aaaaaaaaa)
- [remove を使って自身を削除しよう](aaaaaaaaa)


## Label
- [Label のフォントサイズを指定しよう](aaaaaaaaa)
- [Label のフォントファミリーを指定しよう](aaaaaaaaa)
- [Label のアラインを指定しよう](aaaaaaaaa)
- [Label のベースラインを指定しよう](aaaaaaaaa)
- [Label のフォントカラーを指定しよう](aaaaaaaaa)


## Button
- [LabelButton を生成して表示してみよう](aaaaaaaaa)
- [LabelButton を押した際の処理を登録してみよう](aaaaaaaaa)
- [IconButton を生成して表示してみよう](aaaaaaaaa)
- [GlossButton を生成して表示してみよう](aaaaaaaaa)
- [GlossButton の背景色を変更してみよう](aaaaaaaaa)


## Scene
- [独自シーンを作ってみよう](aaaaaaaaa)
- [独自シーンを切り替えてみよう](aaaaaaaaa)
- [シーンに Sprite と Shape を表示してみよう](aaaaaaaaa)
- [開始画面シーンを作ってみよう](aaaaaaaaa)
- [終了画面シーンを作ってみよう](aaaaaaaaa)
- [ポーズシーンを作ってみよう](aaaaaaaaa)
- [ポーズシーンを解除してみよう](aaaaaaaaa)


## Pointing(MouseClick or Touch)

tmlib.js ではマウスクリック, タッチをまとめてポインティング(pointing)と呼んでいます.

- [ポインティング開始]
- [ポインティングしている間]
- [ポインティング終了]
- [ポインティング開始位置に表示オブジェクトを移動させてみよう](AAAAAAAAAA)
- [ポインティング終了位置に表示オブジェクトを移動させてみよう](AAAAAAAAAA)
- [ポインティングしている位置に表示オブジェクトを移動させてみよう](AAAAAAAAAA)
- [ポインティングした位置からずらした分移動させてみよう](AAAAAAAAAA)
- [各ポインティングの情報を Label で画面に表示しよう](AAAAAAAAAA)(座標やタッチ回数など)


## Interaction
- [ポインティングオーバー時の処理を登録しよう](AAAAAAAAAA)
- [ポインティングアウト時の処理を登録しよう](AAAAAAAAAA)
- [ポインティングスタート時の処理を登録しよう](AAAAAAAAAA)
- [ポインティングエンド時の処理を登録しよう](AAAAAAAAAA)
- [ポインティングムーブ時の処理を登録しよう](AAAAAAAAAA)
- [ポインティングした Sprite を削除してみよう](AAAAAAAAAA)
- [判定領域を円にしよう](AAAAAAAAAA)
- [判定領域を矩形にしよう](AAAAAAAAAA)


## Animation
- [Tween Animation させてみよう](AAAAAAA)
- [移動アニメーションさせてみよう(絶対座標)](AAAAAA)
- [移動アニメーションさせてみよう(相対座標)](AAAAAAAA)
- [回転アニメーションさせてみよう](AAAAAAA)
- [拡大縮小アニメーションさせてみよう](AAAAAAAAA)
- [フェードイン, フェードアウトさせてみよう](AAAAAAAA)
- [アニメーション終了後に実行する処理を登録しよう](AAAAAAAAA)

## Collision
- [要素同士で衝突判定をしよう(矩形判定)](AAAAAAAAA)
- [要素同士で衝突判定をしよう(円形判定)](AAAAAAAAA)


## Keyboard

- [指定したキーを押した瞬間だけ反応させてみよう]
- [指定したキーを押している間反応させてみよう]
- [指定したキーを離した瞬間だけ反応させてみよう]
- [Arrow Key に応じて表示オブジェクトを移動させてみよう]
- [表示オブジェクトが画面外に出ないように制御してみよう]
- [キー入力に応じて表示オブジェクトをジャンプさせてみよう]
- [画面端に行ったら逆側にワープさせてみよう]


## Acceleration

- [傾いている方向に表示オブジェクトを移動させよう]
- [移動するオブジェクトに慣性をつけてみよう]


## Sound

- [音を読み込んで再生しよう]
- [読み込んだ音のキャッシュ数を指定しよう]
- [再生中の音を停止しよう]
- [再生中の音を中断, 再開してみよう]
- [音のボリュームを変更しよう]
- [音をループ再生させよう]


## AnimationSprite
- []()


## CanvasApp
- [CanvasApp の幅高さを変更してみよう](bbbbb)
- [CanvasApp を画面にフィットさせよう](bbbbb)
- [CanvasApp の背景色を変更してみよう](bbbbb)
- [CanvasApp の更新頻度を指定しよう(fps)](bbbbb)


## Other
- [fps を変更してみよう](aaaaaaaaa)
- [経過フレーム数を取得しよう](aaaaaaaaa)
- [経過秒数を取得しよう](aaaaaaaaa)
- [指定した時間以下になったら色を変えてみよう](aaaaaaaaa)
- [指定した時間以下になったら点滅させてみよう](aaaaaaaaa)
- [ゲーム共通のデータを作ろう](aaaaaaaaa)(tm.util.DataManager)


