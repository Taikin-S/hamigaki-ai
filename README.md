# HAMIGAKI AIエージェント組織

AIエージェントが直接読むための情報源。
人間が見る管理画面はNotion。AIの脳はここ。

## フォルダ構成

```
hamigaki-ai/
├── context/          AIの判断基準・会社の文脈情報
│   ├── philosophy.md   価値観・判断基準（全エージェント共通）
│   └── org.md          組織図・役割定義
│
├── agents/           各部門の指示書
│   ├── schraiber-dir.md  Schraiber事業部Dir
│   └── （今後追加）
│
├── handoff/          AI間の引き継ぎノート
│   └── latest.md      最新の引き継ぎ
│
├── decisions/        意思決定ログ
│   └── log.md          代表の判断履歴（COO育成の教科書）
│
└── brand/            ブランド・デザイン規約
    └── （今後追加）
```

## Notionとの使い分け

- Notion → タスクDB、CRM、営業オペ、議事録、クライアント情報
- このリポジトリ → AIの指示書、判断基準、引き継ぎ、意思決定ログ

## NotionのリソースID

- タスクDB: `1218432ccd348017b815f48f3390f455`
- 引き継ぎノート: `35b8432ccd3481a7a4bad67e070b8caa`
- 意思決定ログDB: data_source `27d55eeb-8a34-4c70-953f-b817aa48de94`
- 文脈エンジン: `35b8432ccd348134a25ecc1fb889f23e`
- 営業オペレーション（🦷ページ）: `2e78432ccd348070ad87c4e2995c7cd6`
