---
title: Salesforce開発の生産性を最大化する拡張機能「SFDC Inspect」
tags:
  - Salesforce
  - ChromeExtension
  - 生産性向上
  - 開発ツール
private: false
updated_at: ''
id: null
organization_url_name: null
slide: false
ignorePublish: false
---

# Salesforce開発の生産性を最大化する拡張機能「SFDC Inspect」

Salesforceの開発者やシステム管理者として、日々「あっちのページに行きたい」「このレコードの裏側の値を確認したい」「SOQLをサクッと叩いてデータを更新したい」といった要望に追われていませんか？

**SFDC Inspect** は、これらのフラストレーションを解消し、業務効率を劇的に向上させるために開発されたモダンなChrome拡張機能です。既存の複数のツールを1つの洗練されたUIに統合しました。

[![Available in the Chrome Web Store](https://img.shields.io/badge/Chrome_Web_Store-Available-blue?logo=google-chrome&logoColor=white)](https://chromewebstore.google.com/detail/sfdc-inspect-salesforce-q/kmcdodpdhoomiedbfdkeglhfebbjgolf)

---

## 🎥 デモ動画
[SFDC Inspectの動作イメージはこちら](https://www.youtube.com/watch?v=rSYBvuoNOyY)

<iframe width="560" height="315" src="https://www.youtube.com/watch?v=rSYBvuoNOyY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

---

## 🚀 現場で役立つ6つのコア機能

### 1. クイックナビゲーション・パレット
**「ログインし直し」のストレスはもうありません。**
すでにお手元のブラウザでSalesforceにログインしていれば、`Ctrl+I` (Macは `Cmd+I`) を押すだけで、その組織の情報を即座に取得・操作できます。
* 700以上のリンクに対応（設定ページ、オブジェクト、Apexクラス、フロー、Lightningページなど）。
* 階層の深い設定メニューを検索して1クリックでアクセス。

![SFDC Inspect](https://lh3.googleusercontent.com/E_f5_akIM7dXnMbtYxCcIJzm5SNG0glqH69JzzgxbB3tSSbqp1qI4MNFy3eolYz59oznhoxhoQxuwNbZYDAd_7M8AA=s1280-w1280-h800)

### 2. レコード・クイックインスペクター
ページ遷移することなく、表示中のレコードの全項目値を確認・編集できます。
* **システム項目（作成日、ID等）やレイアウト未配置の項目**も即座に可視化。
* 開発中のデータ確認やデバッグ時間を大幅に短縮します。

### 3. データエキスパート (SOQL + Bulk操作)
Excelのような直感的なインターフェースでデータを操作できます。
* SOQLクエリの実行と結果のCSVエクスポート。
* **一括操作 (Insert / Update / Upsert / Delete)** に対応。
* 大量データ修正もブラウザ上で完結します。

![SFDC Inspect](https://lh3.googleusercontent.com/9mYzJ3OzvdlFzy1n_dvqQ5S9_eCR0damQ1pIL1qVI4gQRsx4U92edDz9Lb9oQa7x8bxz55jx_cWBzjpo-viT4swFplI=s1280-w1280-h800)


### 4. ER図ジェネレーター
Salesforceの複雑なデータモデルを自動で可視化します。
* 複数のオブジェクトを選択し、**Mermaid.js**形式で高品質なER図を生成。
* 仕様書の作成や、チーム内・顧客との要件定義のコミュニケーションに最適です。


### 5. ログエキスパート
Salesforceのデバッグログをストレスなく閲覧・分析できます。
* ユーザー、時間、ログレベルによる高度なフィルタリング。
* 重いログファイルもクリーンなUIでサクサク確認。

![SFDC Inspect](https://lh3.googleusercontent.com/AZLJPDqcO6AsNY3egmfyRPqS_x0SVrH3KlO3QKGD4Opq5LD84DlYDMPky9R9ejzDAXfx2667u85xYZlT6IpDdSlJ=s1280-w1280-h800)
![SFDC Inspect](https://lh3.googleusercontent.com/asqqHwAWkGGdfPqzchoLnmI9yL-todg9Lc5UVSrZ6HG-dRi-BwNcluSgO2fAYlSZDUztx695POBG5AmRoPpqe7of2Q=s1280-w1280-h800)

### 6. ドキュメンテーション＆アーキテクチャ
* フロー(Flow)のロジック解析。
* Apexクラス間の関係性をマップ化し、システム全体の構成を把握しやすくします。
![SFDC Inspect](https://lh3.googleusercontent.com/Jjl1tqKuEhb_KVqXCIXx24iqgQM3IW7K5GAjn5rvbIL3bdnj89u8xg8rAGVoMy7ZNEz0OYw4ShHfbSTJ5Kwb0MSt=s1280-w1280-h800)

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

👉 [**SFDC Inspectをインストールする**](https://chromewebstore.google.com/detail/sfdc-inspect-salesforce-q/kmcdodpdhoomiedbfdkeglhfebbjgolf)

---

## 🚀 開発の裏側とフィードバック
このツールは、**ChatGPT** および **Gemini** などの最新AIを活用してスピード感を持って開発されました。

* **Author**: exia.huang ([HomePage](https://salesforcexytools.com/))
* **フィードバック**: もしバグを見つけたり、新機能のご要望がありましたら、ぜひ以下のGitHub Issuesからお気軽にご連絡ください！

👉 [**GitHub Issues でフィードバックする**](https://github.com/exiahuang/sfdc-inspect/issues)

---

## 結びに
Salesforceの管理・開発は、プラットフォームの進化と共に複雑さを増しています。SFDC Inspectは、その複雑さを「シンプル」に変え、皆さんの貴重な時間を節約するためのパートナーです。

ぜひ一度お試しいただき、フィードバックをいただければ幸いです！

#Salesforce #SalesforceDeveloper #productivity #ChromeExtension #DX