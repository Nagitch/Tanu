SQLite-net
https://zenn.dev/shiena/articles/unity-sqlite-net
https://github.com/praeclarum/sqlite-net

ファイルフォーマット
- .tanu SQLite + バイナリファイル + テーブル表示
- .tanumark .tnm = .tanu + Markdown


- TANU CLI
- TANU Editor
- TANUMark Editor

クラウドホスティング
Googleスプレッドシートてきなやつ

tanumark バイナリファイル領域にマークダウンファイル
1シート1ファイル
設定値をTanuテーブルに保存

Tanumark ライブラリ js c# rust?

テーブル定義とエンティティ、スキーマをまとめたファイル？


スプレッドシート
DBMS+バイナリデータとインデックス
ダンプをファイルとして保存

要件
* コマンドパレット
* DBダンプ
* embulk転送
* Create文
* 複数人同時編集
* markdown
* VSCode拡張
* オーソドックスな用途
	* 決済表
	* テーブル定義
	* 仕様書
	* API仕様書
	* 勤務表
* ファイルに対するAPI JS, Python
* プログラマブルな一括編集
* C#オブジェクトとの互換性
* 定義に名前をつける　int
* コピペの変換ユーティリティ　カンマ区切り文字列をレコードに変換とか　自分で拡張もできる
* データ変換専用スクリプト言語、python js
  * const dataとかにオブジェクトいれる、foreachできる　let out とかに変換結果格納
* Enum, 選択式リスト
* データを.sql（クエリ）に外だしできる CREATE, INSERT (bulk insert)
  * Gitでコンフリクトおきにくくするため


スキーマビルダー的なところまで想定
ViewModelまでを自動生成

バリデーター　正規表現、カスタムロジック^_^


