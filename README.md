# project-portfolio-generator

プロジェクトポートフォリオ生成 は、D:/AI配下や制作フォルダから公開用ポートフォリオを生成する。入力、確認、履歴保存、次アクションを同じ作業単位で扱えるようにする。

## 何を解決するか

制作物の一覧や説明ページを毎回手で更新する必要がある。

## 差別化

フォルダ情報とメタデータから静的サイトへ出力する。

## 公開先

- GitHub Pages / GitHub Release

## 現在の到達点

- core / validators / report / review-model / CLI に責務を分割済み
- 静的Webアプリ + CLI生成 の最小実装または配布用骨格を同梱済み
- 代表シナリオ `samples/representative-suite.json` で正常系、必須項目不足、warning、混在バッチを自動検証済み
- 厳格 QCDS は Quality、Cost、Delivery、Satisfaction の全観点 S+ で評価済み
- docs ZIP は `dist/project-portfolio-generator-docs.zip`

## 主要コマンド

```powershell
npm test
npm start
```

## 重要ドキュメント

- [要件定義](docs/requirements.md)
- [仕様](docs/specification.md)
- [設計](docs/design.md)
- [手動テスト](docs/manual-test.md)
- [厳格手動テスト追補](docs/strict-manual-test-addendum.md)
- [QCDS評価](docs/qcds-evaluation.md)
- [厳格QCDS metrics](docs/qcds-strict-metrics.json)
- [トレーサビリティ](docs/traceability-matrix.md)

## 参照したアイデアパック

- created_idea: `D:\AI\WebApp\created_idea_009_project-portfolio-generator`
- idea ZIP: `D:\AI\WebApp\created_idea_009_project-portfolio-generator\idea_009_project-portfolio-generator.zip`
- PICKUP rank: 22
- Domain: WebApp
