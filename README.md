"# rizminit" 
--------------------------------------------------------------------------------
ライセンス：GPL
商用利用：可
--------------------------------------------------------------------------------

ご覧頂きありがとうございます。
本プログラムはExcelで作成されたDB定義書を読み込み、DBのテーブル作成、サンプルデータ作成を行います。
現在、PostgreSQLにのみ対応しています。

■使い方
--------------------------------------------------------------------------------
Git cloneまたはダウンロードしたフォルダの中にある
main/executor.xlsm をMicrosoft Excel 2007で開きます。

マクロが実行できるようExcelのセキュリティ設定を確認／設定します。

【create文の作成】
対象ブックにDB定義書の絶対パスを指定します。
[一括create文作成]ボタン押下でDB定義書に定義されているテーブルすべてのcreate文を出力します。
一定の文字数まではブック内のSQL出力用テキストボックスに出力されますが
それ以上の文字数が生成された場合は同フォルダ内に"sql_export.txt"ファイルを作成し、
そのファイルに文字列を出力します。

【insert文の作成】
対象ブックにDB定義書の絶対パスを指定します。
[一括insert文作成]ボタン押下でDB定義書に定義されているテーブルすべてのinsert文を出力します。
一定の文字数まではブック内のSQL出力用テキストボックスに出力されますが
それ以上の文字数が生成された場合は同フォルダ内に"sql_export.txt"ファイルを作成し、
そのファイルに文字列を出力します。

--------------------------------------------------------------------------------

更新履歴
--------------------------------------------------------------------------------
ver-0.1.0     PostgreSQLにも対応
--------------------------------------------------------------------------------
--------------------------------------------------------------------------------
ver-0.0.1     新規作成
--------------------------------------------------------------------------------

