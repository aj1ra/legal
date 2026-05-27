# legal

aj1ra が公開するアプリケーションの法務文書（プライバシーポリシー・利用規約等）を集約するリポジトリ。

GitHub Pages でホスティングされ、各アプリの App Store / Google Play 等の `Privacy Policy URL` から参照される。

## 構成

```
legal/
├── README.md
└── <app-name>/
    ├── privacy-policy.md
    └── terms.md  （必要なら）
```

## 公開アプリ

| アプリ | ドキュメント |
|--------|------------|
| TehaiLens | [プライバシーポリシー](./tehailens/privacy-policy.md) |

## 改定方針

- 改定は git commit を以て履歴とする
- 各ドキュメント内の「改定履歴」テーブルにも、利用者向けの要約を追記する
- 重要な変更がある場合は、各アプリのリリースノートでも告知する