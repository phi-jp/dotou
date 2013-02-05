# jQuery 怒濤の修練(100)


## 準備
- [jQuery を読み込もう](setup/010)
- [jQuery をCDNから読み込もう](setup/020)


## 基礎
	- [コメントを書いてみよう](base/010)
	- [コメントを複数行で書いてみよう](base/020)
- [console.log() を使う](base/070)
- [alert() を使う](base/080)
- [pタグの中身(HTML)を取得しよう](base/030)
- [pタグの中身(text)を取得しよう](base/040)
- [jQueryに出てくる $ について知ろう](base/050)
- [jQueryに出てくる $(this) について知ろう]()
- [jQueryをHTMLの読み込みが終了してから実行する](base/060)
- [最初にアニメーションのサンプルなど]


## 要素(Selector)
- [HTMLのタグを参照してみよう](selector/010)
- [idの要素を参照してみよう](selector/020)
- [classの要素を参照してみよう](selector/030)
- [タグ, id, classを組み合わせて参照してみよう](selector/030)
	- [最初の要素を参照してみよう](selector/040)
	- [最後の要素を参照してみよう](selector/050)
	- [特定の文字列を含む要素を参照してみよう](selector/060)
	- [偶数の要素を参照してみよう](selector/070)
	- [奇数の要素を参照してみよう](selector/080)
	- [:header]


## 属性(Attribute)
- [要素にclassを追加しよう]
- [要素からclassを削除しよう]
- [要素のクラスを追加/削除で交互に切り替えよう]
- [.attr()]


## 操作(Traversing)
	- [liのn番目の要素を参照してみよう](aaa)
	- [偶数の要素を参照してみよう](aaa)
	- [奇数の要素を参照してみよう](aaa)
	- [偶数の要素と奇数の要素で色を変えてみよう](aaa)
- [子要素を取得しよう](.children)
- [子要素を取得しよう](.find())
- [親要素を取得しよう](.parent)
- [親要素を取得しよう](.parents)
- [n番目の要素を取得してみよう](.eq)
	- [要素の絞り込みをやってみよう](.filter)
	- [最初の要素を取得してみよう](.first)
	- [最後の要素を取得しよう](.last)
- [特定の要素を持った要素のみを取得してみよう](.has)
- [条件と一致した要素を取得しよう](.is)
- [指定した要素以外の要素を取得しよう](.not)
- [指定した要素の直後の要素を取得しよう](.next)
- [指定した要素の後にあるすべての弟要素を取得しよう](.nextAll)
- [指定した要素の直前の要素を取得しよう](.prev)
- [指定した要素の前にあるすべての兄要素を取得しよう](.prevAll)
- [指定した要素に対して処理を実行してみよう](.each)


## 制御(Manipulation)
- [要素のwidth(横幅)を取得しよう](.width)
- [要素のheight(高さ)を取得しよう](.height)
- [要素のwidth(横幅)を変更しよう](.width)
- [要素のheight(高さ)を変更しよう](.height)
	- [要素にコンテンツを追加しよう(1.9対応)](.add())
- [要素内の先頭に要素を追加しよう](.prepend)
- [要素内の末尾にコンテンツを追加してみよう](.append)
- [指定した要素Aを要素Bの末尾にコピーしてみよう](.clone)
- [要素のすべての子要素を削除してみよう](.empty)
- [要素を削除してみよう](.remove() イベントハンドラも削除する)
- [指定した要素を置換してみよう](.replaceAll)
- [要素を指定したコンテンツで置換してみよう](.replaceWith)


## CSS
- [要素のCSSを取得してみよう](.css)
- [pタグの文字色を赤にしてみよう](selector/010)
- [要素を非表示にしよう](aaa)
- [要素の横幅と高さを取得してみよう](aaa)
- [css("width") と width() の違い]
- [2つの要素の高さを合わせてみよう](aaa)
- [上からのスクロール量を取得してみよう](scrollTop)
- [左からのスクロール量を取得してみよう](scrollLeft)
	- [](.offset)
	- [](.position)


## Event
	- [イベントを監視してみよう](aaa)
	- [イベントの種類を知ろう](aaa)
	- [クリックのイベントを監視してみよう](aaa)
	- [クリックでアクションを起こしてみよう](aaa)
	- [マウスホバーのイベントを監視してみよう](aaa)
- [クリックイベントを検知してみよう](.click)
- [マウスオーバーを検知してみよう](.hover)
- [マウスアウトを検知してみよう](.hover)
- [マウスオーバー/マウスアウトを .mouseover()/.mouseout() で検知してみよう](.mouseover()/.mouseout())
- [マウスオーバー/マウスアウトを .mouseenter()/.mouseleave() で検知してみよう](.mouseenter()/.mouseleave())
	- [要素にイベントハンドラを紐付けます](.bind)
	- [.unbind]
	- [ダブルクリックイベントを検知してみよう](.dblclick)
	- [マウスの押し込みを検知してみよう](.mousedown)
	- [マウスの押上を検知してみよう](.mouseup)
	- [キーボードの押し込みを検知してみよう](.keydown)
	- [キーボードの押上を検知してみよう](.keyup)
	- [テキストの入力を検知してみよう](.keypress)
- [.on() を使ってイベントをバインドしてみよう](.on)
- [.on("load")] - 要検証
- [.off]
- [ウインドウのリサイズを検知してみよう](.resize)
- [スクロールを検知してみよう](.scroll)
	- [要素に指定したイベントを発生させよう](.trigger)
	- [.triggerHandler]
		- [.select]
		- [要素の変更を検知してみよう](.change)
		- [.focus]
		- [.focusin / .focusout]
		- [.blur]
		- [.submit]
	- [.delegate]
	- [.undelegate]
	- [.one]
	- [.ready]


## Animation
- [要素を移動させてみよう](animate)
- [.animate() に複数の要素を指定しよう](animate)
- [アニメーションのスピードを指定してみよう](aaa)
- [アニメーションのにイージングを指定してみよう](aaa)
- [アニメーションを順番に動作させてみよう](aaa)
- [アニメーション後の処理を指定しよう](aaa)
- [要素をフェードイン/フェードアウトさせてみよう](.fadeIn/.fadeOut)
- [フェードの透過度を操作しよう](.fadeTo)
- [フェードの処理を切り替えよう](.fadeToggle)
- [.animate() でフェードを再現してみよう](.animate)
- [.show() で要素を表示しよう](.show)
- [.hide() で要素を非表示にしよう](.hide)
- [.slideUp() で要素を表示しよう](.slideUp)
- [.slideDown() で要素を表示しよう](.slideDown)
- [.slideToggle() で表示を交互に切り替えよう](.slideToggle)
- [.toggle() で表示を交互に切り替えよう](.toggle)
- [.delay() でアニメーションを待機させてみよう](.delay)
	- [aaaaaa](.clearQueue)
	- [aaaaaa](.dequeue)
	- [aaaaaa](.queue)
- [aaaaaa](.stop)


## Ajax
- [Ajaxで通信をしてみよう](aaa)
- [Ajaxで通信成功、失敗、完了を受け取ろう](aaa)
- [Ajaxでページを読み込んで表示してみよう](aaa)
	- []($.ajax)
	- []($.ajaxPrefilter)
- []($.ajaxSetup)
	- []($.get)
- []($.getJSON)
	- []($.getScript)
	- []($.post)


## jQuery Core
- [他ライブラリと競合しないようにしよう]($.noConflict)
	- []($.holdReady)
	- []($.when)
	- []($.error)
- [要素数を取得しよう](.length)
- [要素が何番目か取得しよう](.index)
	- [](.toArray)
	- [](.pushStack)
	- [](.get)
	- [](.context)


## プラグイン制作
- [プラグインを作ってみよう](aaaa)


## プラグイン紹介
- [代表的なプラグインを紹介(特に国内の有名な人のを紹介すればお互い美味しいかも)](aaa)
- [スライドショー](aaa)
- [画像系](aaa)
- [スクロール系](aaa)
- [IE系](aaa)
- [文字列系](aaa)
- [ページネーション系](aaa)
	- [テーブル系](aaa)
	- [フォーム系](aaa)

## その他
	- [ブラウザを判定してみよう](aaa)
	- [ユーザーエージェントを判定してみよう](aaa)


## 実践
- [スライドショーを作ってみよう](aaa)
- [WordPressで使ってみよう](aaa)


## 拡張
- [jQueryを拡張してみよう]()
- 参考:
- [【クリスマスだし】用意しておくとちょっと便利なjQueryの拡張メソッドたち【25日目の４】 ｜ クラスメソッド開発ブログ](http://dev.classmethod.jp/client-side/language-client-side/extend-jquery-methods/)




## 環境
- [Chrome Developer Tools を起動しよう](aaa)
- [コンソール画面にログを表示しよう](aaa)


## memo
- jQuery しか使ってない人に JavaScript と jQuery の線引を説明できたら良いかも
- ウェブサイト制作編 / ウェブアプリ制作編 みたいに分けたほうが良いかも？

## 参考
jQuery1.9からの変更点日本語解説  
- [jQuery Core 1.9 Upgrade Guideの翻訳というか解説](http://wood-roots.com/web%E5%88%B6%E4%BD%9C/jqueryjavascript/jquery-core-1-9-upgrade-guide%E3%81%AE%E7%BF%BB%E8%A8%B3%E3%81%A8%E3%81%84%E3%81%86%E3%81%8B%E8%A7%A3%E8%AA%AC)
- [jQuery 1.9 に更新する際に注意すべき変更点の自分なりのまとめ](http://myjquery.blog.fc2.com/blog-entry-14.html)



