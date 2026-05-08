# family-ticket-legal

iOS アプリ「ファミリーチケット (Family Ticket)」のランディングページ・プライバシーポリシー・利用規約・サポートページを公開するリポジトリ。

## 公開 URL

- トップ: https://matntntn.github.io/family-ticket-legal/
- プライバシーポリシー: https://matntntn.github.io/family-ticket-legal/privacy/
- 利用規約: https://matntntn.github.io/family-ticket-legal/terms/
- サポート: https://matntntn.github.io/family-ticket-legal/support/

将来的にカスタムドメイン（例: `familyticket.app`）に切り替える場合は `CNAME` ファイルを追加し、DNS の A/CNAME レコードを GitHub Pages に向ける。

## ローカルプレビュー

```bash
bundle install
bundle exec jekyll serve
```

## 構成

- `_config.yml` — Jekyll 設定（cayman テーマ・permalink）
- `index.md` — ランディングページ
- `privacy.md` — プライバシーポリシー
- `terms.md` — 利用規約
- `support.md` — サポートページ
