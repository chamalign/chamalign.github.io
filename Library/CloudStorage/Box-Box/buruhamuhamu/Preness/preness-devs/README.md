# Preness Development

新しい開発用フォルダです。`architecture.md`に基づいたディレクトリ構造で開発を進めます。

## ディレクトリ構成

```
preness-devs/
├── backend/              # バックエンド
│   ├── ai/              # 【Sasaki担当】GPT API関連
│   └── app/             # 【Vannes担当】API & DB
├── frontend/            # 【Vannes担当】フロントエンド
├── infrastructure/      # 【Horiba担当】インフラ・外部サービス統合
├── docs/                # ドキュメント
├── scripts/            # スクリプト
└── generated_exams/     # 生成された問題の保存先（開発・テスト用）
```

## 開発の進め方

1. 各フェーズごとにブランチを切って開発
2. Pull Requestを作成してレビュー
3. 承認後にmainブランチにマージ

詳細は `docs/development/architecture.md` と `docs/development/development_roles.md` を参照してください。

