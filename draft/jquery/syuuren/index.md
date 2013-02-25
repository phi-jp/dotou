# jQuery 怒濤の修練(100)


## 準備(Setup)
- ローカルのjQuery を読み込もう		[Demo](setup/010)
- CDNからjQueryを読み込もう			[Demo](setup/020)


## 基礎(Base)
	- コメントを書いてみよう							[Demo](base/000)
	- コメントを複数行で書いてみよう					[Demo](base/000)
- console.log() を使う						[Demo](base/010)
- alert() を使う								[Demo](base/020)
- jQueryをHTMLの読み込みが終了してから実行する		[Demo](base/030)
	- jQueryに出てくる $ について知ろう				[Demo](base/000)
	- jQueryに出てくる $(this) について知ろう			[Demo](base/000)
	- 最初にアニメーションのサンプルなど				[Demo](base/000)


## 要素(Selector)
- HTMLのタグを参照してみよう						[Demo](selector/010)
- idの要素を参照してみよう						[Demo](selector/020)
- classの要素を参照してみよう					[Demo](selector/030)
- タグ, id, classを組み合わせて参照してみよう		[Demo](selector/040)
- pタグの中身(HTML)を取得しよう					[Demo](selector/050)
- pタグの中身(text)を取得しよう					[Demo](selector/060)
	- 最初の要素を参照してみよう						[Demo](selector/000)
	- 最後の要素を参照してみよう						[Demo](selector/000)
	- 特定の文字列を含む要素を参照してみよう				[Demo](selector/000)
	- 偶数の要素を参照してみよう						[Demo](selector/000)
	- 奇数の要素を参照してみよう						[Demo](selector/000)
	- :header


## 属性(Attribute)
- 要素にclassを追加しよう					[Demo](attribute/010)
- 要素からclassを削除しよう					[Demo](attribute/020)
- 要素のクラスを追加/削除で交互に切り替えよう	[Demo](attribute/030)
- aタグのURLを取得しよう					[Demo](attribute/040)
- aタグのURLを変更しよう					[Demo](attribute/050)
- imgタグのsrcを取得しよう					[Demo](attribute/060)
- imgタグのsrcを変更しよう					[Demo](attribute/070)


## 操作(Traversing)
	- liのn番目の要素を参照してみよう					[Demo](traversing/000)
	- 偶数の要素を参照してみよう						[Demo](traversing/000)
	- 奇数の要素を参照してみよう						[Demo](traversing/000)
	- 偶数の要素と奇数の要素で色を変えてみよう			[Demo](traversing/000)
- n番目の要素を取得してみよう						[Demo](traversing/010)
- 子要素を取得しよう ( .children() )			[Demo](traversing/020)
- 子要素を取得しよう ( .find() )				[Demo](traversing/030)
- 1階層上の親要素を取得しよう ( .parent() )		[Demo](traversing/040)
- 2階層以上の親要素を取得しよう ( .parents() )	[Demo](traversing/050)
	- 要素の絞り込みをやってみよう					[Demo](traversing/000)
	- 最初の要素を取得してみよう						[Demo](traversing/000)
	- 最後の要素を取得しよう							[Demo](traversing/000)
- 特定の要素を持った要素のみを取得してみよう			[Demo](traversing/060)
- 条件と一致した要素を取得しよう					[Demo](traversing/070)
- 指定した要素以外の要素を取得しよう				[Demo](traversing/080)
- 指定した要素の直後の要素を取得しよう				[Demo](traversing/090)
- 指定した要素の後にあるすべての弟要素を取得しよう		[Demo](traversing/100)
- 指定した要素の直前の要素を取得しよう				[Demo](traversing/110)
- 指定した要素の前にあるすべての兄要素を取得しよう		[Demo](traversing/120)
- 指定した要素の全てに処理を実行してみよう			[Demo](traversing/130)


## 制御(Manipulation)
- 要素のwidth(横幅)を取得しよう									[Demo](manipulation/010)
- 要素のheight(高さ)を取得しよう									[Demo](manipulation/020)
- 要素のwidth(横幅) と height(高さ)を変更しよう					[Demo](manipulation/030)
	- 要素のheight(高さ)を変更しよう									[Demo](manipulation/000)
	- 要素にコンテンツを追加しよう(1.9対応)							[Demo](manipulation/000)
- 要素内の先頭に要素を追加しよう ( .prepend() )					[Demo](manipulation/040)
- 要素内の末尾にコンテンツを追加してみよう ( .append() )				[Demo](manipulation/050)
- 指定した要素Aを要素Bの末尾にコピーしてみよう ( .clone() )			[Demo](manipulation/060)
- 要素のすべての子要素を削除してみよう ( .empty() )					[Demo](manipulation/070)
- 要素を削除してみよう ( .remove() )								[Demo](manipulation/080)
- 要素を削除してみよう ( .detach() )								[Demo](manipulation/090)
- 指定した要素を置換してみよう ( .replaceAll() )					[Demo](manipulation/100)
- 要素を指定したコンテンツで置換してみよう ( .replaceWith() )		[Demo](manipulation/110)
- マッチした要素を指定した要素で囲む ( .wrap() )					[Demo](manipulation/120)
	- マッチした要素を指定した要素でまとめて囲む ( .wrapAll )			[Demo](manipulation/000) ※要検証
- マッチした要素内のコンテンツを指定した要素で囲む ( .wrapInner())		[Demo](manipulation/130)
- 要素内の親要素を削除します ( .unwrap )							[Demo](manipulation/140)
- 要素を指定した要素の前ろに追加します								[Demo](manipulation/000)
- 要素を指定した要素の前ろに移動します								[Demo](manipulation/000)
- 要素を指定した要素の後ろに追加します								[Demo](manipulation/000)
- 要素を指定した要素の後ろに移動します								[Demo](manipulation/000)


## CSS
- 要素のCSSを取得してみよう				[Demo](css/010)
- pタグの文字色を赤にしてみよう			[Demo](css/020)
- 要素を非表示にしよう					[Demo](css/030)
- 要素の横幅と高さを取得してみよう			[Demo](css/040)
- css("width") と width() の違い		[Demo](css/050)
- 2つの要素の高さを合わせてみよう			[Demo](css/000)
- 上からのスクロール量を取得してみよう		[Demo](css/000)
- 左からのスクロール量を取得してみよう		[Demo](css/000)
	- (.offset)
	- (.position)


## Event
	- イベントを監視してみよう					[Demo](event/000)
	- イベントの種類を知ろう						[Demo](event/000)
	- クリックのイベントを監視してみよう			[Demo](event/000)
	- クリックでアクションを起こしてみよう			[Demo](event/000)
	- マウスホバーのイベントを監視してみよう			[Demo](event/000)
- クリックイベントを検知してみよう				[Demo](event/000)
- マウスオーバーを検知してみよう				[Demo](event/000)
- マウスアウトを検知してみよう				[Demo](event/000)
- マウスオーバー/マウスアウトを .mouseover()/.mouseout() で検知してみよう			[Demo](event/000)
- マウスオーバー/マウスアウトを .mouseenter()/.mouseleave() で検知してみよう		[Demo](event/000)
	- 要素にイベントハンドラを紐付けます			[Demo](event/000)
	- .unbind
	- ダブルクリックイベントを検知してみよう			[Demo](event/000)
	- マウスの押し込みを検知してみよう				[Demo](event/000)
	- マウスの押上を検知してみよう				[Demo](event/000)
	- キーボードの押し込みを検知してみよう			[Demo](event/000)
	- キーボードの押上を検知してみよう				[Demo](event/000)
	- テキストの入力を検知してみよう				[Demo](event/000)
- .on() を使ってイベントをバインドしてみよう	[Demo](event/000)
	- .on("load")] - 要検証
	- .off
- ウインドウのリサイズを検知してみよう			[Demo](event/000)
- スクロールを検知してみよう					[Demo](event/000)
	- 要素に指定したイベントを発生させよう			[Demo](event/000)
	- .triggerHandler
		- .select
		- 要素の変更を検知してみよう					[Demo](event/000)
		- .focus
		- .focusin / .focusout
		- .blur
		- .submit
	- .delegate
	- .undelegate
	- .one
	- .ready


## Animation
- 要素を移動させてみよう							[Demo](animation/000)
- .animate() に複数の要素を指定しよう				[Demo](animation/000)
- アニメーションのスピードを指定してみよう			[Demo](animation/000)
- アニメーションのにイージングを指定してみよう		[Demo](animation/000)
- アニメーションを順番に動作させてみよう				[Demo](animation/000)
- アニメーション後の処理を指定しよう				[Demo](animation/000)
- 要素をフェードイン/フェードアウトさせてみよう		[Demo](animation/000)
- フェードの透過度を操作しよう					[Demo](animation/000)
- フェードの処理を切り替えよう					[Demo](animation/000)
- .animate() でフェードを再現してみよう			[Demo](animation/000)
- .show() で要素を表示しよう					[Demo](animation/000)
- .hide() で要素を非表示にしよう					[Demo](animation/000)
- .slideUp() で要素を表示しよう					[Demo](animation/000)
- .slideDown() で要素を表示しよう				[Demo](animation/000)
- .slideToggle() で表示を交互に切り替えよう		[Demo](animation/000)
- .toggle() で表示を交互に切り替えよう			[Demo](animation/000)
- .delay() でアニメーションを待機させてみよう		[Demo](animation/000)
	- aaaaaa		[Demo](.clearQueue)
	- aaaaaa		[Demo](.dequeue)
	- aaaaaa		[Demo](.queue)
- aaaaaa		[Demo](.stop)


## Ajax
- Ajaxで通信をしてみよう					[Demo](ajax/000)
- Ajaxで通信成功、失敗、完了を受け取ろう		[Demo](ajax/000)
- Ajaxでページを読み込んで表示してみよう		[Demo](ajax/000)
	- ($.ajax)
	- ($.ajaxPrefilter)
- ($.ajaxSetup)
	- ($.get)
- ($.getJSON)
	- ($.getScript)
	- ($.post)


## jQuery Core
- 他ライブラリと競合しないようにしよう		[Demo]($.noConflict)
	- ($.holdReady)
	- ($.when)
	- ($.error)
- 要素数を取得しよう					[Demo](.length)
- 要素が何番目か取得しよう				[Demo](.index)
	- (.toArray)
	- (.pushStack)
	- (.get)
	- (.context)