---
title: Salesforce開発の生産性を最大化する拡張機能「SFDC AI Inspect」
tags:
  - Salesforce
  - 開発ツール
  - ChromeExtension
  - 生産性向上
private: false
updated_at: '2026-02-17T19:26:25+09:00'
id: ac4db07845d840a5152d
organization_url_name: null
slide: false
ignorePublish: false
---

# Salesforce開発の生産性を最大化する拡張機能「SFDC AI Inspect」

Salesforceの開発者やシステム管理者として、日々「あっちのページに行きたい」「このレコードの裏側の値を確認したい」「SOQLをサクッと叩いてデータを更新したい」といった要望に追われていませんか？

**SFDC AI Inspect** は、これらのフラストレーションを解消し、業務効率を劇的に向上させるために開発されたモダンなChrome拡張機能です。既存の複数のツールを1つの洗練されたUIに統合しました。特に **AI Agent** を中心に、日々の運用・開発・調査を「会話ベース」で高速化できる点が大きな強みです。

[![Available in the Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Available-blue?logo=google-chrome&logoColor=white)](https://chromewebstore.google.com/detail/sfdc-inspect-salesforce-q/kmcdodpdhoomiedbfdkeglhfebbjgolf)

---

## 🚀 AIを中心にした8つのコア機能

### 1. 🤖 AI Agent Workspace
**Salesforceを自然言語で操作できるAIワークスペース。**
* **Natural Language for Salesforce:** 質問すると、そのまま実務で使える回答を返します。
* **75+ LLM Provider Ecosystem:** GPT / Claude / Gemini など **75+** のモデルプロバイダーに接続可能。
* **No Vendor Lock-in:** コスト・性能に合わせてモデル/プロバイダーをいつでも切り替え可能。
* **Local Model Ready:** Ollama などローカルモデル運用にも対応。
* **Custom MCP Integration:** 自社開発の Salesforce MCP サーバー [@exiahuang/salesforce-mcp](https://github.com/exiahuang/salesforce-mcp) と連携し、AI Agentの機能を拡張しやすい設計。
* **Easy to Extend:** MCPベースなので、将来の社内要件や業務フローに合わせてツール能力を段階的に追加可能。
* **Language-aware Replies:** アプリ言語設定に合わせてAI回答言語を自動調整。
* **Easy Setup:** 一度設定すれば、AI対応モジュールで再利用可能。

![sfdc-ai-inspect-agent](https://github.com/exiahuang/qiita-content/blob/main/public/images/sfdc-ai-inspect/sfdc-ai-inspect-agent.gif?raw=true)

![sfdc-ai-run-test-class](https://github.com/exiahuang/qiita-content/blob/main/public/images/sfdc-ai-inspect/sfdc-ai-run-test-class.gif?raw=true)

### 2. 📊 Data Expert
**データ管理をAIで加速する、Excelライクな実務UI。**
* **Excel-like UI:** 見やすくレスポンシブなテーブルでデータを検索・編集。
* **Bulk Operations:** Insert / Update / Upsert / Delete の一括操作に対応。
* **SOQL Helper:** フォーマットとフィールド補助でSOQL作成を高速化。
* **AI to SOQL:** 自然言語からSOQLを生成。SOQL非習熟メンバーでも安全・高速に保守可能。
* **Export:** 結果をCSVで出力して共有・分析。

![sfdc-ai-soql](https://github.com/exiahuang/qiita-content/blob/main/public/images/sfdc-ai-inspect/sfdc-ai-soql.gif?raw=true)

### 3. 📜 Log Expert + AI Analysis
**ログ調査をAIで短時間化し、原因特定を支援。**
* **Real-time Monitoring:** 最新デバッグログをすぐ取得・確認。
* **Advanced Filtering:** ユーザー、ステータス、時間など多軸で絞り込み。
* **AI Summary:** 根本原因の候補、証拠、改善案をAIが要約。

![sfdc-ai-log-analysis](https://github.com/exiahuang/qiita-content/blob/main/public/images/sfdc-ai-inspect/sfdc-ai-log-analysis.gif?raw=true)

### 4. 🛠️ Architecture & Documentation
**AIで設計把握とドキュメント生成を効率化。**
* **Flow Analysis:** Flowロジックを構造的に可視化。
* **AI Architecture Assistance:** オブジェクト関係をAIで分析し、設計観点の出力を生成。
* **Doc Assistance:** アーキテクチャ文書作成をAIで支援。


### 5. 🚀 Quick Navigation Palette
* **Hotkey:** Salesforce画面上のどこでも `Ctrl+I`（Macは `Cmd+I`）。
* **Search & Jump:** 設定リンク、オブジェクト、Apexクラス、ページ、各種ツールを即検索。
* **Simple Workflow:** キーワード入力ですぐに目的画面へ遷移。

![SFDC AI Inspect](https://lh3.googleusercontent.com/E_f5_akIM7dXnMbtYxCcIJzm5SNG0glqH69JzzgxbB3tSSbqp1qI4MNFy3eolYz59oznhoxhoQxuwNbZYDAd_7M8AA=s1280-w1280-h800)


### 6. 🔍 Record Quick Inspector
* **Instant Access:** 現在ページから直接レコード詳細を表示。
* **Deep Insight:** 重要なシステム項目を含むフィールド値を可視化。
* **Quick Edit:** 複数画面を行き来せず、その場で値を更新。

### 7. 🔌 REST Tool
* **Direct API Testing:** SalesforceエンドポイントへRESTリクエストを即送信。
* **Fast Debugging:** リクエスト/レスポンスを1画面で確認。
* **Practical for Daily Work:** API検証、連携確認、障害調査に最適。

![sfdc-rest-api](https://github.com/exiahuang/qiita-content/blob/main/public/images/sfdc-ai-inspect/sfdc-rest-api.gif?raw=true)

### 8. 🕸️ ER Diagram Generator
* **Visualize Data Models:** 選択したSalesforceオブジェクトからER図を生成。
* **Mermaid-based Output:** レビュー・共有しやすいMermaid形式で出力。
* **Architecture Friendly:** 設計レビューやドキュメント作成に有効。

![SFDC AI Inspect](https://lh3.googleusercontent.com/Jjl1tqKuEhb_KVqXCIXx24iqgQM3IW7K5GAjn5rvbIL3bdnj89u8xg8rAGVoMy7ZNEz0OYw4ShHfbSTJ5Kwb0MSt=s1280-w1280-h800)

---

## 👔 企業管理者・マネージャーの方へ：導入のメリット

個人開発者のツールとしてだけでなく、チームや組織全体での導入にも適しています。

1. **生産性(ROI)の向上**: 
   開発者やアドミニストレーターが「隠れた項目」を探したり、複雑なSOQLツールを立ち上げる時間を削減することで、コアなビジネスロジックの開発に集中できます。
2. **ナレッジの可視化**: 
   ER図やアーキテクチャマップを簡単に生成できるため、属人化を防ぎ、新メンバーのキャッチアップを加速させます。
3. **コスト削減**: 
   複数のアドオンを使い分ける必要がなくなり、学習コストとツール管理の手間を最小限に抑えられます。

---

## 🔒 安心のセキュリティとプライバシー

エンタープライズ環境での利用を想定し、セキュリティには最大限配慮しています。

* **ローカル動作**: すべての処理はブラウザ内で完結します。
* **外部送信なし**: 取得したデータや認証情報が外部サーバーに保存されたり送信されることはありません。
* **直接通信**: 拡張機能は認証された自身のSalesforce組織とのみ直接通信します。
* **標準APIの利用**: Salesforceの標準APIとセーフなセッション管理（chrome.cookies）を使用しています。

---

## 🛠 インストール方法

以下のリンクから、Chrome Web Store経由で簡単に追加できます。

👉 [**SFDC AI Inspectをインストールする**](https://chromewebstore.google.com/detail/sfdc-inspect-salesforce-q/kmcdodpdhoomiedbfdkeglhfebbjgolf)

---

## 🚀 開発の裏側とフィードバック
このツールは、**ChatGPT** および **Gemini** などの最新AIを活用してスピード感を持って開発されました。

また、AI Agent基盤として自社開発のMCPサーバーを採用しています。
* **Salesforce MCP Server**: [https://github.com/exiahuang/salesforce-mcp](https://github.com/exiahuang/salesforce-mcp)
* **方針**: 独自MCPをベースにすることで、業務に合わせた拡張・保守・機能追加を行いやすくしています。

* **Author**: exia.huang ([HomePage](https://salesforcexytools.com/))
* **フィードバック**: もしバグを見つけたり、新機能のご要望がありましたら、ぜひ以下のGitHub Issuesからお気軽にご連絡ください！

👉 [**GitHub Issues でフィードバックする**](https://github.com/exiahuang/sfdc-inspect/issues)

---

## 🎥 デモ動画
[SFDC AI Inspectの動作イメージはこちら](https://www.youtube.com/watch?v=rSYBvuoNOyY)

<iframe width="560" height="315" src="https://www.youtube.com/watch?v=rSYBvuoNOyY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## 結びに
Salesforceの管理・開発は、プラットフォームの進化と共に複雑さを増しています。SFDC AI Inspectは、その複雑さを「シンプル」に変え、皆さんの貴重な時間を節約するためのパートナーです。

ぜひ一度お試しいただき、フィードバックをいただければ幸いです！

#Salesforce #SalesforceDeveloper #productivity #ChromeExtension #DX
