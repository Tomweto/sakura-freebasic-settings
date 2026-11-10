# sakura-freebasic-settings

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Editor](https://img.shields.io/badge/Editor-Sakura_Editor-pink.svg)
![Language](https://img.shields.io/badge/Language-FreeBASIC-orange.svg)

FreeBASIC settings for Sakura Editor (kwd / ini files)

サクラエディタで [FreeBASIC](https://www.freebasic.net/) のソースコードを編集するためのタイプ別設定ファイル（`.ini`）および強調キーワード定義ファイル（`.kwd`）です。

---

## 📁 含まれているファイル

* `FreeBASIC.ini` : サクラエディタのタイプ別設定ファイル（拡張子関連付け、ブロックコメント等の設定含む）
* `FreeBASIC.kwd` : FreeBASIC のキーワード・組み込み関数・プリプロセッサ命令等を網羅した強調キーワードファイル

---

## 🚀 使い方（インポート手順）

### 方法 A: タイプ別設定（.ini）を丸ごと読み込む（推奨）

1. サクラエディタのメニューから **[設定] ＞ [タイプ別設定一覧]** を開きます。
2. 空いている行を選択し、下部の **[インポート]** ボタンをクリックします。
3. 本リポジトリの `FreeBASIC.ini` を選択して取り込みます。
4. 設定一覧に追加された「FreeBASIC」を選択して **[設定変更]** を開き、**[カラー]** タブの「強調キーワード1」の **[インポート]** から `FreeBASIC.kwd` を読み込みます。

### 方法 B: キーワードファイル（.kwd）のみ利用する

1. 既存の「Visual BASIC」等のタイプ別設定を開き、**[カラー]** タブを選択します。
2. 「強調キーワード」の **[インポート]** ボタンをクリックし、`FreeBASIC.kwd` を読み込みます。
3. 先頭の `// CASE=False`（または設定ダイアログ側）で**「大文字小文字を区別しない」**設定にしてご使用ください。

---

## 📝 補足・仕様

* **対象拡張子**: `.bas`, `.bi`
* **コメント指定**:
  * 単行コメント: `'`
  * ブロックコメント: `/'` 〜 `'/`
* **作成背景**: 本キーワードリスト（.kwd）は、FreeBASIC 公式ドキュメントの定義をもとに AI を活用して補完・整形・統合を行ったものです。

---

## 📄 ライセンス

[MIT License](LICENSE) のもとで自由にご利用・再配布していただけます。
