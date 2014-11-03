<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE.html PUBLIC "-//W3C//DTD XHTML 1.0 Frameset//EN" "http://www.w3.org/TR/.htmll1/DTD/.html1-frameset.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="ja" xml:lang="ja">
<head>
  <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
  <meta http-equiv="content-style-type" content="text/css" />
  <title>設定：一般</title>
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
	一般
</div>
<!-------------------------------------------------------------------------------------------------------------------------------->

# 設定：一般

	画像左側のリストを<span class="Doing">クリック</span>で、それぞれのダイアログのページに対応する解説のページへ移動します。

![本体設定ダイアログ一般](image/config-ippan/0.png)
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

このページでは右クリックメニューの「設定」サブメニューにある項目「本体設定」で開くダイアログの、「一般」ページについて解説しています。

## 各項目の解説

<dl>

   <dt>SSPが更新されているか自動でチェックする</dt>   
   <dd>SSP更新チェック機能を自動で実行し、更新があった場合にのみ通知します。</dd>

   <dt>ファイルをSSPに関連付ける</dt>
   <dd>NAR（Nanika ARchive＝ゴーストやシェルなどのパッケージファイル）などのファイルをSSPに関連づけ、SSP起動中にそれをダブルクリックすることでインストールができるようになります。

   通常、ONで特に問題はないとは思われますが、他の「何か」処理系と共存する場合、もしくは、レジストリを操作されたくない場合にOFFにしてください。標準状態ではOFFです。
   </dd>

   <dt>正確なスクリプト再生タイミング</dt>
   <dd>スクリプト再生のタイミング調整の方法を変更します。

   通常は常にONで問題ありませんが、非力なマシンや、他に重い作業をしている場合にスクリプト再生が非常に不自然になる事があります（いきなりウェイト0でスクリプトが飛ばされたりする）。

   その場合にチェックを外すと、再生タイミングは正確ではありませんが、自然なスクリプト再生となります。
   </dd>

   <dt>アニメーション・スクリプト再生の優先度を下げる</dt>
   <dd>シェル（キャラクター）が常時行っているアニメーションや、スクリプト再生の優先度を下げることにより、他のアプリケーションやSSPのゴースト起動以外の部分に処理時間を多めに割り振ることができます。

   非力なマシンを利用中で、ゴーストを起動したまま何か作業も行いたい場合に便利です。
   </dd>

   <dt>常にアンインストールメニューを表示</dt>
   <dd>通常ゴースト側の指定に基づいてメニューがコントロールされますが、ONにしておくと、
   ゴーストをアンインストールするボタンを常時表示させます。
   </dd>

   <dt>常にタスクトレイアイコンを表示</dt>
   <dd>チェックしていない場合は、ゴーストが最小化された場合のみ、タスクトレイアイコンが表示されます。

   リソースが逼迫しているなどの問題がない限り、常にONで利用する方がよいでしょう。</dd>

  <dt>インストール時にREADMEを表示する</dt>
  <dd>インストールが完了した際に、ゴーストの取り扱い説明書を表示します。</dd>

  <dt>ホットキーを登録する</dt>
  <dd>Ctrl-Shiftではじまる、常に有効なホットキーを登録するかどうか設定します。

  他のソフトと衝突する場合は無効にしてください。</dd>

  <dt>開発者用機能を有効にする</dt>
  <dd>
  ゴースト開発者向けの、特定のロックを解除したり、エラー表示したりする機能を有効にします。

使い所を誤るとキャラクターの実行に不具合があったり、内部の情報が見えてしまうことでの重大なネタバレの原因になります。

通常はOFFでお使い下さい。
  </dd>

</dl>

### ユーザ情報

名前・呼ばれ方・誕生日・性別を設定しておくと、もしかしたら対応しているキャラクターでは何かいいことがあるかもしれません。

なお、この情報はキャラクターへユーザ情報として通知したり、スクリプトを処理したりする以外に利用される事はありません。

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
	<span class="Prev">[設定：ゴーストごとの設定](config-eachghost.html)</span>
	<span class="Return">[目次](contents.html)</span>
	<span class="Next">[設定：ゴースト(1)](config-ghost.html)</span>
</div>