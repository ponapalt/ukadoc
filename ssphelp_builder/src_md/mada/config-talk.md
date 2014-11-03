<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE.html PUBLIC "-//W3C//DTD XHTML 1.0 Frameset//EN" "http://www.w3.org/TR/.htmll1/DTD/.html1-frameset.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="ja" xml:lang="ja">
<head>
  <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
  <meta http-equiv="content-style-type" content="text/css" />
  <title>設定：喋り/バルーン</title>
  <link rel="stylesheet" type="text/css" href="about.css" />
</head>
<body>
<div id="sidebar">
	<iframe src="contents.html" name="sidebar">
		フレーム非対応の環境では以下の目次ページからご覧ください。

[目次](contents.html)
	</iframe>
</div>
<div id="text">
<div id="breadcrumb">
	<span class="Upper">[目次](contents.html)</span>
	<span class="Upper">[設定](config.html)</span>
	<span class="Upper">本体設定</span>
	喋り/バルーン
</div>
<!-------------------------------------------------------------------------------------------------------------------------------->

# 設定：喋り/バルーン

	画像左側のリストを<span class="Doing">クリック</span>で、それぞれのダイアログのページに対応する解説のページへ移動します。

![本体設定ダイアログ喋り/バルーン](image/config-talk/0.png)
	<map name="configdialog" id="configdialog">
		<area shape="rect" coords="14,31,137,46" href="config-ippan.html" alt="一般">
		<area shape="rect" coords="14,47,137,66" href="config-ghost.html" alt="ゴースト(1)">
		<area shape="rect" coords="14,66,137,82" href="config-ghost2.html" alt="ゴースト(2)">
		<area shape="rect" coords="14,82,137,98" href="config-folder.html" alt="フォルダ">
		<area shape="rect" coords="14,98,137,114" href="config-disp.html" alt="表示">

		<area shape="rect" coords="14,115,137,133" href="config-talk.html" alt="喋り/バルーン">
		<area shape="rect" coords="14,134,137,152" href="config-conn1.html" alt="接続(1)">
		<area shape="rect" coords="14,150,137,168" href="config-conn2.html" alt="接続(2)">
		<area shape="rect" coords="14,167,137,185" href="config-pop.html" alt="POP">
		<area shape="rect" coords="14,184,137,202" href="config-extprog.html" alt="外部アプリ">

		<area shape="rect" coords="14,201,137,219" href="config-im.html" alt="IM">
		<area shape="rect" coords="14,218,137,236" href="config-ipmes.html" alt="IPMessenger">
		<area shape="rect" coords="14,235,137,253" href="config-i18n.html" alt="国際化">
		<area shape="rect" coords="14,252,137,270" href="config-dev.html" alt="開発/その他">
	</map>

このページでは右クリックメニューの「設定」サブメニューにある項目「本体設定」で開くダイアログの、「喋り/バルーン」ページについて解説しています。

## 各項目の解説

<dl>
   <dt>メッセージスピード</dt>
   <dd>
   喋り等を表示するスピードです。1文字ずつ表示していく間の待ち時間を設定します。

通常はゴースト側でも各自ウェイトを制御しているため、全てのゴーストが同じ速度で喋るようにはなりません。
   </dd>

   <dt>喋りタイムアウト/選択肢タイムアウト/クリックタイムアウト</dt>
   <dd>それぞれ通常喋り・選択肢表示時・クリック待ち時にどれだけの時間が経てばバルーンを自動的に閉じるか、またはクリックを待たずに読み進めるかを設定します。
    </dd>

   <dt>常にヘッドライン読み上げはウェイトなしで実行する</dt>
   <dd>
   ヘッドラインセンサの読み上げ文は長いので、これを設定しておくと、強制的に早送り指定で実行します。

特に問題がない限り設定しておくことをおすすめします。
   </dd>

   <dt>オンライン時に常にバルーンを表示する</dt>
   <dd>
   オンライン時に、ブレーク操作やオンライン状態の確認のために常にメイン側バルーンを表示します。

特に問題がない限り設定しておくことをおすすめします。
   </dd>

   <dt>早送りキーを有効にする</dt>
   <dd>
   これを有効にし、キーの種類を設定することで、設定したキーを押している間はスクリプトの再生を早送り（ウェイトを無視）することができます。
   </dd>

   <dt>バルーンにカーソルを重ねている時タイムアウトしない</dt>
   <dd>
   操作中などで、マウスカーソルが吹き出し内にある時には、一定時間経過で自動的にバルーンを消去する処理を無効にします。

ただし、ゴースト側で意図的に時間制限が設定されている場合はこの設定が無視されることがあります。
   </dd>
</dl>

### しゃべる時に鳴らす音の指定

何か吹き出しに表示される時に、音を慣らします。

喋りを見逃したくない場合に、音声ファイルを指定しておくと良いでしょう。

### バルーンの操作

吹き出しのマウスでの操作方法をカスタマイズできます。

従来的な動作は左ダブルクリックでスクリプトブレーク、右クリックでバルーン左右切替です。

<dl>   
   <dt>何もしない</dt>
   <dd>
   何もしません。
   </dd>

   <dt>左クリックと同じ</dt>
   <dd>
   左シングルクリックと同じ扱いにします。
   </dd>

   <dt>スクリプトブレーク</dt>
   <dd>
   スクリプトの表示を中断し、バルーンを閉じます。

ただし選択肢表示中など、閉じられない場合があります。
   </dd>

   <dt>バルーン左右切替</dt>
   <dd>
   バルーンの方向を左右で切替えます。

なお、通常バルーンが画面横から出そうになった場合は自動で左右が切り替わります。
   </dd>

   <dt>バルーン位置調整</dt>
   <dd>
   バルーンの位置調整モードに入ります。

バルーンを左クリックをするまでの間、バルーンがカーソルに追従するようになります。

普通のバルーンのドラッグ操作と同じですが、ドラッグがうまく行かないような環境で利用できます。
   </dd>

   <dt>メニュー表示</dt>
   <dd>
   毎回どのような動作をするかメニューから選ぶようにします。
   </dd>
</dl>

### 旧仕様サポート

ふるいゴーストを使用する場合に設定が必要な項目です。

<dl>   
   <dt>しゃべり頻度</dt>
   <dd>
   自発的に喋ってくれる頻度を調節します。

多くのゴーストは喋るタイミングをゴースト側で管理するため、無効です。
   </dd>

   <dt>ニュースをしゃべる</dt>
   <dd>
   ニュース機能（最新情報等を順繰りに読んでくれる機能）を使うかどうかを設定します。

通常、ONのままで問題ありません。

また、旧仕様のため、すでにサポート対象外です。
   </dd>
</dl>

## 下部のボタン

<dl>
	<dt>ヘルプ</dt>
	<dd>
		本体設定ダイアログの、設定中のページのヘルプ（つまりこのページ）を開きます。

ダイアログ右上の「？」マークも同様です。
	</dd>

	<dt>閉じる</dt>
	<dd>
		本体設定ダイアログを閉じます。

ダイアログ右上の「×」マークも同様です。
	</dd>
</dl>

<!-------------------------------------------------------------------------------------------------------------------------------->
<div id="navigation">
	<span class="Prev">[設定：表示](config-disp.html)</span>
	<span class="Return">[目次](contents.html)</span>
	<span class="Next">[設定：接続(1)](config-conn1.html)</span>
</div>