Awake
=================
## Awake is custom template of roots.
Awakeは[@sadako_a_](http://twitter.com/sadako_a_)がwebサイトを制作するときに利用するrootsのカスタムテンプレートです。

## 導入方法
Awakeはrootsを元にしたカスタムテンプレートです。

rootsの環境はNode.jsベースなので環境構築の導入をお願いします。

### ダウンロード
テンプレートのダウンロードは以下のリンクからお願い致します。

[ダウンロードリンク](http://service.xxxx.jp/awake)

### 1.Node.jsを導入する。
以下のリンクよりNode.jsの環境を導入してください。

[ダウンロードリンク](http://nodejs.org/download/)


### 2.Rootsを導入する。
ターミナルを開いて以下のコマンドを叩いてください。

	npm install roots -g


### 3.Jadeを導入する。
rootsはHTMLの拡張言語としてJadeを採用しています。

ターミナルを開いて以下のコマンドを叩いてください。

	npm install -g jade

### 4.Stylusを導入する。
rootsはCSSの拡張言語としてStylusを採用しています。

ターミナルを開いて以下のコマンドを叩いてください。

	npm install -g stylus

### 5.CoffeeScriptを導入する。
rootsはJavaScriptの拡張言語としてCoffeeScriptを採用しています。

ターミナルを開いて以下のコマンドを叩いてください。

	npm install -g coffee-script
### 6.プロジェクトをコンパイルする。
コンパイルをする時は以下のコマンドを叩いてください。

publicフォルダが実際に納品などで利用するフォルダとなります。

	roots compile

### 6.5.プロジェクトを監視する。
プロジェクトの監視をする時は以下のコマンドを叩いてください。

	roots watch
	// 確認はlocalhost:1111 (初期)	
	

## ファイル説明
	awake
		┣ _app.coffee // 設定ファイル
		┣ assets // 作業ファイル
			┣css // スタイルシート
			┣favicon.ico // favicon
			┣img // 画像ファイル
			┣js // スクリプトファイル
		┣ humans.txt // ヒューマンズファイル
		┗ public // 出力ファイル。納品時はこのファイルを利用します。
		┗README.md // 説明ファイル
		┗Views // Jadeファイル

## SMACSSの採用
AwakeではCSSを高品質、低コスト管理にするのを目指すためにSMACSSを採用しています。

	  css
		┣ _base.styl // サイトのベースとなるスタイル
		┣ _grid.styl // グリッドの設定ファイル
		┣ _mixin.styl // Mixinの設定ファイル
		┣ _setting.styl // サイトの設定ファイル
		┣ _shame.styl // サイトの一時的スタイル置き場
		┣ _master.styl // サイトのスタイルの統合ファイル
		┣ layouts // レイアウトに関するファイル
			┣ _l-about.styl
			┣ _l-footer.styl
			┣ _l-header.styl
			┣ _l-main.styl
			┣ _l-side.styl
			┣ _l-pager.styl
		┣ module // モジュールに関するファイル
			┣ _m-about.styl
			┣ _m-acodion.styl
			┣ _m-button.styl
			┣ _m-form.styl
			┣ _m-icon.styl
			┣ _m-logo.styl
			┣ _m-modal.styl
			┣ _m-navigation.styl
			┣ _m-slide.styl
			┣ _m-tabs.styl
		┣ state // 状態に関するファイル
			┣ _s-state.styl
		┣ theme // テーマに関するファイル
			┣ _t-theme.styl


## HTMLの説明
AwakeではOGPの設定やSNS、アナリティクスの設定をあらかじめ導入しています。

ご利用に応じて、追加したり削除するなどお願い致します。

またJadeファイルはLayout.jadeにBody以外の情報を、

それ以外のファイルにBody内の情報を記入することによりファイルが多くなっても

更新の手間が省けるという利点があります。


## humans.txtについて
humans.txtとはWebに関与した人たちについての情報が入ったテキストファイルです。

これは必ず記入しなければいけないというものではありません。

しかし、ユーザーがが閲覧するサイトの作者を知る為に必要な大切なファイルです。
詳しくは以下のリンクをお読みください。

[humans.txtについて](http://humanstxt.org/JA)


## License
Awake is MIT LICENSE template.

* jQuery: MIT/GPL license
* Normalize.css: Public Domain
* roots: Jeff Escalante


## Changelog

### 2014/07/02
	公開

### 2014/07/09
	カラーパレットの調整
	require.jsのリンク削除
	htmlのmain.jsのリンク設定


## 作者情報
	貴島 衛 / Kijima Mamoru
	サイト / http://sadakoa.jp/
	連絡 / sadako0215@gmail.com
	テンプレートのご利用上のトラブルにつきましては、製作者は一切の責任を負いません。


