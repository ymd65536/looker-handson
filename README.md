# Lookerの機能拡張について

## 概要

Lookerにはさまざまな機能拡張があります。
機能拡張は主にネイティブ機能として実装されているものとOSSとして提供されているものがあります。

## ネイティブ機能

ネイティブ機能というのはいわゆるLookerのGemini統合です。

https://cloud.google.com/gemini/docs/looker/overview?hl=ja

GenAIを活用したものはGemini in Lookerの一部として提供されています。具体的には以下のような機能があります。

- Conversational Analytics - 会話型クエリ
- Advanced Viz Assistant - 高度な可視化のアシスト
- LookML Assistant - LookMLのアシスト

なお、以下の機能はLooker Studio Proの機能として提供されているものです。
Gemini in Lookerが有効になっている場合に利用できます。

- Automatic Slide Generation - スライド自動生成
- Formula Assistant - 計算アシスト

## Lookerを取り巻くOSS

Google Cloudでは提供されていない機能はOSSのextensionを使うことによって導入することができます。
具体的には以下のとおりです。

- Explore Assistant (Looker Extension)
- Dashboard Summary (Looker Extension as Dashboard Tile)
- Query Insights (Looker Extension as Custom Viz)
- Vertex AI Data Action (Custom Action)
- Semantic Search Block (Looker Blocks)

## Explore Assistant

Explore AssistantはLookerのExploreという機能を自然言語によって操作するためのOSSです。
https://github.com/looker-open-source/looker-explore-assistant

何ができるか：
Exploreによるグラフの作成を自然言語で行うことができるため、Lookerの操作に慣れていないユーザでも簡単にグラフを作成できます。

## Dashboard Summary

Dashboard SummaryはLookerのダッシュボードに要約情報を表示するためのOSSです。
https://github.com/looker-open-source/dashboard-summarization

何ができるか：
ダッシュボードの内容を要約して表示することができるため、ダッシュボードの内容をより簡単に把握できます。

## Query Insights

Query InsightsはLookerのクエリの実行状況を可視化するためのOSSです。
