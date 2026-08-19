<div align="center">

# WorkPilot

**バラバラのAI・ツール・データを、ひとつの操縦席に。あなた1人が"チーム"になる。**

[English README](./README.md)

[![Download](https://img.shields.io/badge/Download-macOS%20(Apple%20Silicon)-black?logo=apple)](https://github.com/boice-kazuya/workpilot-releases/releases/latest)
[![Release](https://img.shields.io/github/v/release/boice-kazuya/workpilot-releases?label=latest)](https://github.com/boice-kazuya/workpilot-releases/releases/latest)
![Notarized](https://img.shields.io/badge/Apple-公証取得済み-blue)

</div>

WorkPilotは、チャットでAIに指示して**動画・画像・記事・コード・音声**を「作り終える」ところまで運ぶMac用デスクトップアプリです。案を出して終わりのチャットではなく、仕事を最後まで進める**操縦席**。

## WorkPilotの特長

**🧠 全エンジンをひとつの操縦席で — 手持ちのサブスクがそのまま動く**
**Claude・ChatGPT・Kimi・Gemini** をスレッドごとに切り替え。「台本はClaudeで、サムネはGPTで、アップはClaudeで」と1つ指示すれば、工程を分解してエンジンを自動で使い分けます。各社の公式CLIログインで動くため **APIキー不要・従量課金なし**。プランの残量（5時間枠・週次枠）は画面下に常時表示されます。

**👥 1人のアシスタントではなく「AIのチーム」**
**17職種のプリセット**（企画・調査・ライター・レビュアー・マーケ・デザイナー・コーダー・動画ディレクター・分析・法務…）＋自作エージェントでチームを編成。指揮官が采配し、「1:テーマ決定 2:台本(GPT) 3:チェック…」と**工程表**を書けばそのとおりに実行します。分身エージェント **mee** はあなたの言い回しと判断を学習し、あなたらしい下書きを書き、目的に向かって自走もできます。

**🎒 一度「装備」すれば、説明し直さない**
スレッドに**ナレッジ**（資料・仕様・商品写真）、**スキル**（「この流れをスキル化して」の一言で保存できる手順書）、**外部接続**（MCP：動画・音声・音楽・ブラウザ・自社API）、**人格**を装着。組み合わせは**装備セット**としてワンタップで再現。ナレッジはファイル保存＋**OKF**（オープン標準）対応でロックインなし。

**🚢 「案」で終わらせない**
6モード：💬相談 / 🖼画像 / 🎬動画 / 📝記事 / 🎵音声 / 💻コード。
動画は生成→タイムライン編集→スマホ素材の合成→書き出しまで。記事はSEO構成→執筆→WordPress投稿。コードはClaude Code同等の環境（計画→実行・並列ジョブ・1クリック巻き戻し・環境別デプロイ権限）。アップロード・投稿・デプロイ・送信など**公開系だけ承認を挟み**、それ以外は自動で進みます。

**📱 スマホ操縦席**
外出先からスマホでMacのAIへ。**声だけで往復**（指示→作業→要約が返る）。撮った写真・動画もそのままプロジェクトへ。

**🤝 小さなチームの共有スペース**
ナレッジ・スレッド・コードを、ただのフォルダ/NASで共有——**サーバー不要**。コード1つで参加。本番デプロイはリーダー限定、スタッフはステージングまで、といった権限分けも。

## ダウンロードとインストール

**[⬇ 最新版をダウンロード（DMG）](https://github.com/boice-kazuya/workpilot-releases/releases/latest)**

1. DMGを開き、**WorkPilot** を **Applications** へドラッグ
2. ダブルクリックで起動（**Apple公証取得済み**＝警告は出ません）
3. 設定→接続でAIエンジンを1つつなげば使い始められます

更新はアプリ内のボタン1つ。**直近6週間で212回のアップデート**を重ねており、これからも速く良くなり続けます。

## 動作環境

- macOS（**Apple Silicon** / arm64）
- 以下のいずれか1つ以上（ご自身のアカウント）：
  - **Claude** サブスク（Anthropic）または APIキー
  - **ChatGPT** サブスク（OpenAI）または APIキー
  - **Kimi** サブスク（Moonshot AI）
  - **Gemini** APIキー（無料枠でOK）
- 任意：Higgsfield（動画生成）・ElevenLabs（音声）・Suno（音楽）

## プライバシーと安心

- **データはあなたのMacに。** 会話・ナレッジ・生成物はローカル保存。チーム共有も自分たちのフォルダ/NAS（外部サーバーに預けません）
- **勝手に公開しません。** アップロード・投稿・デプロイ・送信は必ず直前承認
- **勝手に課金されません。** API従量課金なし。月額サブスクの範囲で動き、残量は常時見えます
- **Apple公証取得済み**（Developer ID署名）

## このリポジトリについて

配布専用リポジトリです（ソースコードは含まれません）。
不具合報告・ご要望は [Issues](https://github.com/boice-kazuya/workpilot-releases/issues) へどうぞ。

---
© BOICE INC.
