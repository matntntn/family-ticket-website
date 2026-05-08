# family-ticket-website

iOS アプリ「ファミリーチケット (Family Ticket)」のランディングページ・プライバシーポリシー・利用規約・サポートページを公開するリポジトリ。

> アプリ本体（private）のローカルディレクトリ `family-ticket/website/` で運用。親リポは `.gitignore` で `website/` を除外し、独立した git リポジトリとして扱う。

## 公開 URL

- トップ: https://matntntn.github.io/family-ticket-website/
- プライバシーポリシー: https://matntntn.github.io/family-ticket-website/privacy/
- 利用規約: https://matntntn.github.io/family-ticket-website/terms/
- サポート: https://matntntn.github.io/family-ticket-website/support/

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
