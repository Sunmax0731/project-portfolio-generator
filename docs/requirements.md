# 要件定義

## 目的

プロジェクトポートフォリオ生成 は、制作物の一覧や説明ページを毎回手で更新する必要がある。 という課題を、静的Webアプリ + CLI生成 で解決する。

## 利用者

- GitHub Pages / GitHub Release に向けて成果物を公開する制作者
- 手作業の確認を減らし、証跡を残したい開発者または運用者

## 必須要件

- portfolio item を JSON 入力で受け取り、必須項目を検証できる。
- 正常、必須項目不足、warning、混在バッチを自動テストできる。
- 検証結果を Markdown と JSON で出力できる。
- UI または配布面の骨格を持ち、手動テストで実際の利用導線を確認できる。
- QCDS metrics、回帰 baseline、release checklist、security/privacy、traceability を保持する。

## 対象外

- 外部サービスへの大量アクセス自動化。
- 認証情報や個人情報をリポジトリへ保存する運用。
- 手動テストを Codex 側で実施済みと見なすこと。
