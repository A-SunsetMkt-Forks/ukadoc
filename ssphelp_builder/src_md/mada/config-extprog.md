<?xml version="1.0" encoding="UTF-8"?>
<!DOCTYPE.html PUBLIC "-//W3C//DTD XHTML 1.0 Frameset//EN" "http://www.w3.org/TR/.htmll1/DTD/.html1-frameset.dtd">
<html xmlns="http://www.w3.org/1999/xhtml" lang="ja" xml:lang="ja">
<head>
  <meta http-equiv="content-type" content="text/html; charset=UTF-8" />
  <meta http-equiv="content-style-type" content="text/css" />
  <title>設定：外部アプリ</title>
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
	外部アプリ
</div>
<!-------------------------------------------------------------------------------------------------------------------------------->

# 設定：外部アプリ

	画像左側のリストを<span class="Doing">クリック</span>で、それぞれのダイアログのページに対応する解説のページへ移動します。

![本体設定ダイアログ外部アプリ](image/config-extprog/0.png)
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

このページでは右クリックメニューの「設定」サブメニューにある項目「本体設定」で開くダイアログの、「外部アプリ」ページについて解説しています。

SSPから必要に応じて起動するアプリケーションの設定です。通常は規定設定などが自動で判別されるので、必ずしも設定する必要はありません。

## 各項目の解説

### ブラウザの設定

おすすめ等からURLを参照する場合に使用するブラウザの設定です。

特別に他のブラウザを使用したい場合に設定してください。

通常、空欄の場合は標準に設定されたブラウザ（＝ほとんどの場合、Internet Explorer）が使用されますので、特に設定する必要はないでしょう。

### ファイラーの設定

エクスプローラーの右クリックメニューから「開く」を実行した時等、ファイル管理ソフトが必要になった際に起動するソフトの設定です。

通常、空欄の場合はWindows Explorerが起動しますので、特に設定する必要はありません。

### エディタの設定

キャラクターからテキストファイルを開く際に使用するアプリケーションの設定です。

通常、空欄の場合は、メモ帳など標準に設定されたものが使用されますので、特に設定する必要はないでしょう。

### メーラの設定

キャラクターからメールソフトを起動したり、新規メールを作成する命令が来た場合に使用するメールソフトの設定です。

通常、空欄の場合は標準に設定されたメールソフトが使用されますので、特に設定する必要はないでしょう。

「新規メール送信時に渡す引数」は、新規メールを作成する命令が来た時に、メールソフトにどのような形でメールアドレスを通知するかを設定します。メールソフトごとに設定が違うので、それぞれの説明書をご覧下さい。

なお、%1の部分は「"mailto:メールアドレス"」に置換されます。

EdMaxの指定例：　/A="%1"

Becky!Ver2の指定例：　"%1"

Outlook Expressの指定例：　/mailurl:%1

### バージョン管理ツール

SubversionやGitをSSPから実行することで、ふつうのキャラクターを更新するのと同じ操作で、バージョン管理ツールの更新を実行することができます。

ここでは、これらのツールのうち、実行したいものを手動で選択することができます。

通常は自動検索されますので、設定する必要はありません。

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
	<span class="Prev">[設定：POP](config-pop.html)</span>
	<span class="Return">[目次](contents.html)</span>
	<span class="Next">[設定：IM](config-im.html)</span>
</div>
</div>
</body>
</html>