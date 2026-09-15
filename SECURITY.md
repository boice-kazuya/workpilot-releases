# Security Policy

## Reporting a vulnerability

Please **do not** open a public issue for security problems.

Email **info@workpilot.space** with:

- what you found, and how to reproduce it
- the WorkPilot version (shown at the bottom of the app window)
- your macOS version

You'll get a reply within a few days. Fixes ship in a normal release, and — with your permission — we credit you in the release notes.

## Supported versions

Only the **latest release** is supported. WorkPilot updates in-app: one button, done.

## How WorkPilot handles your data

- Conversations, knowledge, and generated files are stored **on your Mac**. Team sharing writes to a folder or NAS **you** own — there is no WorkPilot server in the middle.
- Credentials (API keys, tokens) are stored with macOS **`safeStorage`** (Keychain-backed), not in plain text and not in the renderer.
- Anything that **publishes** — upload, post, deploy, send — stops and asks for your approval first.
- Exporting an agent or sharing code runs a **secret scan** first (API keys, personal paths, contact details).
- Builds are **signed with an Apple Developer ID and notarized by Apple**.

---

# セキュリティについて

## 脆弱性の報告

セキュリティに関わる問題は、**公開の Issue には書かないでください。**

**info@workpilot.space** 宛に、以下を添えてご連絡ください。

- 見つかった内容と、再現の手順
- WorkPilot のバージョン（アプリ画面の下に出ています）
- macOS のバージョン

数日以内に返信します。修正は通常のリリースに含めて配布し、ご了承いただければリリースノートにお名前を記載します。

## サポート対象

**最新版のみ**をサポートします。WorkPilot はアプリ内で更新できます（ボタン1つ）。

## データの扱い

- 会話・ナレッジ・生成したファイルは **あなたの Mac の中**に保存されます。チーム共有も**あなたの**フォルダや NAS を使い、当社のサーバーは経由しません。
- 認証情報（API キー・トークン）は macOS の **`safeStorage`**（Keychain）で保護して保存します。平文では保存しません。
- **外部に出す操作**（アップロード・投稿・デプロイ・送信）は、必ず確認してから実行します。
- エージェントの書き出しやコードの共有の前には、**機密情報の自動チェック**（API キー・個人のパス・連絡先）が走ります。
- 配布物は **Apple Developer ID で署名し、Apple の公証**を受けています。
