# memestash-privacy

Memestash のプライバシーポリシー公開用リポジトリ。GitHub Pages で `index.html`（Nightlime デザイン）を配信する。

## コミット・PR の言語ルール

- **subject / PR タイトル**: 英語の [Conventional Commits](https://www.conventionalcommits.org/) 形式 `type: description`
  - **type も description も小文字**、description は命令形、**末尾ピリオドなし**
  - 例: `docs: add commit conventions to CLAUDE.md` / `feat: redesign privacy page with Nightlime` / `fix: correct font loading`
  - よく使う type: `feat`（機能）/ `fix`（修正）/ `docs`（ドキュメント）/ `style`（見た目・整形）/ `refactor`（リファクタ）/ `chore`（雑務）
- **body / PR 本文**: 日本語
- **日英併記はしない**（読者が増えたら見直す。過去ログの遡及翻訳も不要）

理由: コミット・PR は開発者向けのメタ情報で、読むのは当面メンテナ本人。subject は英語のほうが `git log --oneline` で短く一覧でき命令形の型に乗る。body は「なぜそうしたか」を母語の日本語で正確に書く。アプリの表示言語（英語ローカライズ予定）とは別問題で、この方針には影響しない。
