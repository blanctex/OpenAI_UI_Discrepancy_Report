# OpenAI_UI_Discrepancy_Report

このリポジトリは、OpenAI ChatGPTの **Web版** と **Desktopアプリ版** における  
UI機能・表示差異の観測結果を構造的に記録・報告するためのものです。

## 📌 背景

2025年6月時点において、同一アカウントにも関わらず、  
以下の機能群が **Web版のみで表示され、Desktopアプリでは非表示** である事象を確認。

OpenAI公式の回答によれば、これは **段階的展開（phased rollout）** によるものであり、  
Web → Desktop へと機能が徐々に展開されているとのこと。

## 🗂 ディレクトリ構成

OpenAI_UI_Discrepancy_Report/
├─ Connectors # Google Drive等の外部接続機能（表示差異あり）
├─ DeepSearch # Deep Research一覧の表示比較
└─ MyGPT # MyGPT（カスタムGPT）のSidebar表示差異


各フォルダには **スクリーンショット（PNG形式）** と、  
それぞれの状態に関する簡易コメントテキスト（`_note.txt` など）を格納。

## 📎 比較対象環境

| 環境区分       | バージョン         | 備考 |
|--------------|------------------|------|
| Web版         | 最新（2025年6月） | Edge経由でアクセス |
| Desktop版     | v1.2025.153      | Windows10環境、ChatGPT公式アプリ |

## 🔍 主な観測差異

### ✅ Connectors（Google Driveなど）
- Web版にて **「Connector」タブが表示**
- Desktop版では非表示（2025年6月時点）

### ✅ DeepSearch
- Web版にて DeepResearch一覧が展開される
- Desktop版では該当項目が確認できないか、一部のみ

### ✅ MyGPT Sidebar
- Web版ではサイドバーにカスタムGPTが展開される（一覧表示）
- Desktop版では表示されないケースがある

## 📝 OpenAIへの問い合わせ記録（要約）

> “These differences are due to **platform-based rollouts** and may appear at different times…”  
> “The Web version tends to receive updates first...”

（詳細は `/問い合わせ記録/` ディレクトリ等を作成し、全文記録を格納してもよい）

## 🔄 今後の運用方針

- 機能追加・表示復活・仕様変更が確認された場合、都度更新
- `revisions/` ディレクトリを作成し、履歴ごとに観測ログを記録
- 将来的に差分比較ツールや自動比較スクリプトとの連携も想定

---

📬 ご質問やPull Requestは歓迎です。  
構文的な差異観測に関する議論は `Issues` で行ってください。
