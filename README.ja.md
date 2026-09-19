# Awesome AI-Powered Executive Dashboards（日本語）

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[English README](README.md)

**AIを活用したエグゼクティブ向けダッシュボード**、BIコパイロット、意思決定インテリジェンス、オープンソース分析基盤、KPIフレームワーク、関連ツールの厳選リストです。経営・FP&A・ピープルアナリティクス・データチーム向けに、ガバナンスされた指標と実務で使えるインサイトを重視しています（デモだけの製品は避けます）。

## 目次

- [AI BIプラットフォーム・コパイロット](#ai-biプラットフォームコパイロット)
- [オープンソースのダッシュボード・分析](#オープンソースのダッシュボード分析)
- [メトリクス層・セマンティックモデル](#メトリクス層セマンティックモデル)
- [人的資本の可視化（ピープルアナリティクス）](#人的資本の可視化ピープルアナリティクス)
- [不正・異常検知](#不正異常検知)
- [プロセスインテリジェンス・デジタルツイン](#プロセスインテリジェンスデジタルツイン)
- [業績予測・経営計画（FP&A）](#業績予測経営計画fpa)
- [KPIフレームワーク・意思決定インテリジェンス](#kpiフレームワーク意思決定インテリジェンス)
- [参考記事・調査レポート](#参考記事調査レポート)
- [コントリビューション](#コントリビューション)

---

## AI BIプラットフォーム・コパイロット

自然言語Q&A、生成AIによるレポート支援、メトリクスのプッシュ型ダイジェスト、ガバナンスされたモデルに根ざしたエージェント型インサイトを備えたエンタープライズBI。

- [Microsoft Power BI Copilot（英語）](https://learn.microsoft.com/en-us/power-bi/create-reports/copilot-introduction) - Power BI / Fabric向け生成AI。データとの対話、レポート要約、ナラティブビジュアル、DAX支援など（容量と管理者設定が必要）。
- [Tableau Pulse（英語）](https://www.tableau.com/products/tableau-pulse) - ガバナンスされたメトリクス層上のパーソナライズされたAIインサイトとダイジェスト（Slack・メール・Teams・モバイル）。Tableau Cloudに含まれる。
- [ThoughtSpot Spotter（英語）](https://www.thoughtspot.com/product/spotter) - 検索／エージェント先行型分析。自然言語の質問を検証可能なセマンティック層クエリにマッピング。
- [Looker Conversational Analytics（Gemini）（英語）](https://docs.cloud.google.com/looker/docs/conversational-analytics-overview) - LookMLセマンティックモデルに根ざした自然言語探索で、一貫した指標回答を返す。
- [Qlik Answers（英語）](https://www.qlik.com/us/products/qlik-answers) - Qlik分析（および非構造化ナレッジベース）向けエージェント型アシスタント。説明可能性と引用付き。
- [Omni Analytics（英語）](https://omni.co/) - ガバナンスされたセマンティックレイヤーとAI支援クエリを組み合わせたモダンBI。
- [Domo（英語）](https://www.domo.com/) - リアルタイム統合とAI機能を備えたクラウドBI／ダッシュボード。
- [Zoho Analytics（Ask Zia）（英語）](https://www.zoho.com/analytics/) - 中小規模向けBI。自然言語質問と自動インサイト。

---

## オープンソースのダッシュボード・分析

セルフホスト可能なダッシュボード／分析ツール。公式ドキュメントやプロジェクトサイトを優先。

- [Apache Superset（英語）](https://superset.apache.org/) - Apache-2.0の探索・ダッシュボード基盤（SQL Lab、40種以上の可視化、セマンティックデータセット）。（[GitHub](https://github.com/apache/superset)）
- [Metabase（英語）](https://www.metabase.com/) - 使いやすいオープンソースBI。ダッシュボード、アラート、埋め込み、AIクエリ（Metabot）。セルフホスト／Cloud。（[GitHub](https://github.com/metabase/metabase)）
- [Lightdash（英語）](https://www.lightdash.com/) - dbtネイティブのエージェント型BI。Git・CLI・MCP経由でガバナンスされた指標とダッシュボードを出荷。（[GitHub](https://github.com/lightdash/lightdash)）
- [Evidence（英語）](https://evidence.dev/) - SQL＋Markdownのコードファースト報告。静的で共有しやすいデータアプリを生成。（[GitHub](https://github.com/evidence-dev/evidence)）
- [Grafana（英語）](https://grafana.com/oss/grafana/) - オープンなオブザーバビリティ／ダッシュボード。リアルタイム運用・IoTの経営ビューにも。（[GitHub](https://github.com/grafana/grafana)）
- [Redash（英語）](https://redash.io/) - SQLから可視化・ダッシュボード共有（コミュニティ維持系譜）。（[GitHub](https://github.com/getredash/redash)）

---

## メトリクス層・セマンティックモデル

エグゼクティブ向けAIコパイロットの信頼性は、ガバナンスされた指標定義にかかっている。一度定義し、どこからでも同じ数字を問い合わせる。

- [dbt Semantic Layer / MetricFlow（英語）](https://docs.getdbt.com/docs/build/about-metricflow) - YAMLでメトリクスを定義。MetricFlowが一貫したSQLを生成。
- [LookML（英語）](https://cloud.google.com/looker/docs/what-is-lookml) - Lookerのモデリング言語。Conversational Analyticsの正本となるディメンション／メジャー／Explore。
- [Microsoft Power BI セマンティックモデル（英語）](https://learn.microsoft.com/en-us/power-bi/connect-data/service-datasets-understand) - Copilotとレポートが共有するセマンティックモデル（AI向けデータ準備の公式ガイドあり）。
- [Cube（英語）](https://cube.dev/) - アプリやAIエージェント埋め込み向けのヘッドレス・セマンティック層／メトリクスAPI。（[GitHub](https://github.com/cube-js/cube)）

---

## 人的資本の可視化（ピープルアナリティクス）

人材・組織・離職リスクなどを経営ダッシュボードに載せるための基盤。

- [Visier（英語）](https://www.visier.com/) - AI支援のワークフォースインサイトと人材計画を備えたピープルアナリティクス。
- [Workday（英語）](https://www.workday.com/) - クラウドHCM。予測分析を統合した人事・組織データ基盤。
- [ChartHop（英語）](https://www.charthop.com/) - 組織図、人員計画、ワークフォースアナリティクス。
- [Lattice（英語）](https://lattice.com/) - パフォーマンス・エンゲージメントなど、リーダー向けスコアカードに載りやすい人事データ。

---

## 不正・異常検知

取引・行動・本人確認などからリスクシグナルを抽出し、経営・統制ダッシュボードに供給する仕組み。

- [Fraud.net（英語）](https://www.fraud.net/) - 取引・アカウント横断のリアルタイム不正／リスク検知AI。
- [Sumsub Anomaly Detection（英語）](https://docs.sumsub.com/docs/ai-powered-anomaly-detection) - 本人確認フロー向けのAI異常検知。
- [Feedzai（英語）](https://www.feedzai.com/) - 金融犯罪・不正リスク向けエンタープライズAI（銀行・決済）。
- [Glassbox（英語）](https://www.glassbox.com/) - デジタル体験分析と異常検知（Anodotのビジネス監視技術を統合）。

---

## プロセスインテリジェンス・デジタルツイン

業務プロセスの可視化・シミュレーションにより、運用KPIが動いた「なぜ」を説明する。

- [Celonis（英語）](https://www.celonis.com/) - プロセスマイニング／プロセスインテリジェンス。ボトルネック発見と自動化の機会抽出。
- [iGrafx Process360 Live（英語）](https://www.igrafx.com/) - 業務プロセスのデジタルツイン構築・BPM・シミュレーション。
- [Simio（英語）](https://www.simio.com/) - 離散事象シミュレーションとデジタルシャドウ型の運用モデル。
- [AVEVA Digital Twin（英語）](https://www.aveva.com/en/solutions/digital-transformation/digital-twin/) - エンジニアリング・オペレーション・業績データを統合する産業向けデジタルツイン。
- [Skan AI（英語）](https://www.skan.ai/) - デスクトップ／システム活動からのプロセス発見・インテリジェンス（タスクマイニング系）。

---

## 業績予測・経営計画（FP&A）

ボード／経営ダッシュボードを裏打ちする計画・予測・シナリオツール。

- [Anaplan（英語）](https://www.anaplan.com/) - ML支援の予測とシナリオ最適化を備えたコネクテッドプランニング。
- [Workday Adaptive Planning（英語）](https://www.workday.com/en-us/products/adaptive-planning/overview.html) - AI支援の予測とWhat-ifを統合したクラウドFP&A。
- [Vena（英語）](https://www.venasolutions.com/) - ExcelネイティブのAI活用FP&A。
- [IBM Planning Analytics（英語）](https://www.ibm.com/products/planning-analytics) - TM1ベースの計画分析とAI予測。
- [Pigment（英語）](https://www.pigment.com/) - 財務・オペレーションのシナリオに使われるモダンな事業計画プラットフォーム。

---

## KPIフレームワーク・意思決定インテリジェンス

ベンダーUIに依存せず、経営が実際に使う5〜12指標の選び方・構造化。

- [Balanced Scorecard Institute（英語）](https://balancedscorecard.org/) - 戦略マップ／BSCによる財務・非財務KPIのバランス設計。
- [OKRリソース（Google re:Work）（英語）](https://rework.withgoogle.com/intl/en/guides/set-goals-with-okrs/) - 成果目標（OKR）と継続監視KPIの併用ガイド。
- [ClearPoint — Executive dashboard examples（英語）](https://www.clearpointstrategy.com/blog/executive-dashboard-examples) - 少数指標・オーナー・目標・トレンド・意思決定コンテキストの実践パターン。
- [Decision Intelligence（Gartner glossary）（英語）](https://www.gartner.com/en/information-technology/glossary/decision-intelligence) - データ・分析・意思決定ワークフローをつなぐ枠組み（ベンダー中立の用語解説）。

---

## 参考記事・調査レポート

耐久性のある入門・公式説明を優先（単発プレスよりエバーグリーンなガイド）。

- [What Are AI Dashboards? — ThoughtSpot（英語）](https://www.thoughtspot.com/data-trends/dashboard/ai-dashboard) - 静的レポートとAIダッシュボードのエンタープライズ向け概観。
- [Copilot for Power BI overview — Microsoft Learn（英語）](https://learn.microsoft.com/en-us/power-bi/create-reports/copilot-introduction) - Power BI Copilotの機能と要件の公式解説。
- [Tableau Pulse 製品ページ（英語）](https://www.tableau.com/products/tableau-pulse) - Pulseの公式機能（メトリクス、ダイジェスト、Enhanced Q&A）。
- [PwC AI predictions（英語）](https://www.pwc.com/us/en/tech-effect/ai-analytics/ai-predictions.html) - 経営文脈に使える年次の企業AI展望。
- [How to Use AI for Financial Forecasting — NetSuite（英語）](https://www.netsuite.com/portal/resource/articles/financial-management/financial-forecast-ai.shtml) - FP&A向けAI予測の入門。
- [How Digital Twins Are Changing Operational Efficiency — Skan AI（英語）](https://www.skan.ai/blogs/how-digital-twins-are-changing-operational-efficiency) - 運用ダッシュボード向けのプロセス／ツイン視点。

---

## コントリビューション

コントリビューション歓迎です。リソース追加、リンク切れ修正、カテゴリ提案はプルリクエストでどうぞ。

**公式／ドキュメントの耐久性のある URL**、短い説明、実際に出荷されている製品を優先してください。デモだけの製品やアフィリエイト専用ページは避けます。製品名はそのまま。オープンソースや言語・地域は分かるように書くと親切です。可能なら `README.md` と `README.ja.md` の両方を更新してください。

## ライセンス

[Apache License 2.0](LICENSE)
