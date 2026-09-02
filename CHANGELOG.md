# Changelog

このリポジトリは、Memoria Eletta（[Memoria](https://suiryo.booth.pm/items/8758856)用の
別売り組み写真プラグイン、VRC4Photos向け）のバージョン確認・更新履歴の掲示専用です。
**プラグイン本体（DLL）はここには置かれません**。最新版のダウンロードは、Memoria本体と同じ
[Boothの商品ページ](https://suiryo.booth.pm/items/8758856)内のバリエーションから
行ってください（Eletta単独の商品ページはありません）。

Memoria本体・Memoria Prismaのバージョン・更新履歴は別リポジトリ
（[MemoriaUpdateCheck](https://github.com/mo4ca/MemoriaUpdateCheck)・
[PrismaUpdateCheck](https://github.com/mo4ca/PrismaUpdateCheck)）で管理しています。
Elettaは本体・Prismaとは別売り・別バージョン管理のため、このリポジトリを分けています。

フォーマットは [Keep a Changelog](https://keepachangelog.com/ja/1.0.0/) に、
バージョニングは [Semantic Versioning](https://semver.org/lang/ja/) に、
（可能な限り）準拠します。

## [0.1.0] - 2026-09-03

初回リリース。Memoria本体 v1.1.0 以降が必要です。

### 追加

- 4枚の写真を1枚にまとめる組み写真の作成。Memoria本体のツールバーの「Eletta」ボタンから
  専用ウィンドウを開き、Memoriaに読み込み済みの写真から選ぶか、ファイルを直接ドラッグ＆
  ドロップでスロットへ入れられます
- 6種類のテンプレート（Monthly／Editorial Spread／Gallery Mat／Contact Sheet／
  Instant Scatter／Strip Poster）。撮影年月を見出しに、`#VRC4Photos`のタグを署名として
  自動で入れます
- 出力比率（1:1／4:5／3:4／9:16 など）とテンプレートに応じた書体の切り替え
  （書体が固定のテンプレートは選択不可）
- キャプションのカスタマイズ（見出しの年月・ハッシュタグ・撮影者クレジット。撮影者
  クレジットは初期状態ではオフ）
- スロットのドラッグ＆ドロップによる並べ替え、スロット右上の✕・右クリックメニューからの
  取り外し、「すべて外す」
- 「Memoriaから選ぶ」では選択順を番号で表示し、空いているスロット数までしか選べません
- 投稿用テキスト（`#VRChat #VRC4Photos`入り）のコピーと、PNG／JPEGでの書き出し
  （既定のファイル名は `VRC4Photos_{yyyy.MM}`）
- 起動時のバージョン確認（このリポジトリのReleasesを参照し、新しいバージョンがあれば
  Memoria本体のウィンドウ右下にトースト通知で知らせる）
