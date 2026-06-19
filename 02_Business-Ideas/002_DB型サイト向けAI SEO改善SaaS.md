---
type: business_idea
title: DB型サイト向けAI SEO改善SaaS
category: SEO SaaS
status: idea
priority: A
difficulty: medium
revenue_model: monthly
target_user: 求人・EC・物件・店舗検索・イベント検索などのDB型サイト運営者
related_projects:
  - ヨルスキ
  - ムシレス
  - EC-CUBE
  - Search Console運用
tags:
  - business
  - saas
  - seo
  - ai
  - dbサイト
created: 2026-06-19
updated: 2026-06-19
---

# DB型サイト向けAI SEO改善SaaS

## 一言でいうと

求人、EC、物件、店舗検索、イベント検索などのDB型サイトに対して、SEO改善案をAIで自動抽出・半自動反映するSaaS。

## 対象ユーザー

- 求人サイト運営者
- ECサイト運営者
- 店舗検索サイト運営者
- 不動産、物件検索サイト運営者
- イベント検索サイト運営者
- Web制作会社、SEO会社

## 課題

- DB型サイトはページ数が多く、title / description / FAQ / 内部リンク改善が手作業では追いつかない
- Search Consoleを見ても、改善施策に落とし込めない
- noindex候補や低品質ページの判断が難しい
- CVが出ているページの横展開が属人的

## 解決策

Search Console、GA4、サイトマップ、DB情報をもとに、AIがSEO改善案を出す。

可能であればCMSやLaravel管理画面と連携し、改善案を承認後に反映する。

## MVP機能

- Search Console連携
- URL別のクリック・表示回数・CTR・掲載順位取得
- title / description 改善案生成
- FAQ案生成
- 構造化データ案生成
- 内部リンク提案
- noindex候補抽出
- 低品質ページ検出
- CSV出力

## 収益化

- 月額 9,800円〜49,800円
- サイト規模別課金
- 初期設定費
- Web制作・SEO保守契約への上乗せ

## 集客方法

- 既存SEO相談・保守顧客へ提案
- EC-CUBE / WordPress / Laravel案件へ導入
- DB型サイト運営者向けLP
- Search Console異常検知レポートから営業導線を作る

## Claude Code / Codexで作りやすい部分

- API連携
- 管理画面
- バッチ処理
- CSV出力
- 改善案生成プロンプト
- URL一覧のスコアリング
- Laravel / Next.jsでのSaaS化

## 開発難易度

中。MVPは比較的作りやすいが、精度と反映フローが差別化ポイント。

## リスク

- AI生成の品質管理が必要
- SEO効果の保証はできない
- CMSごとの反映方法に差分がある
- Search Console APIの権限設定が導入ハードルになる

## 次アクション

- [ ] MVPで見る指標を決める
- [ ] URLスコアリング条件を決める
- [ ] 改善案テンプレートを作る
- [ ] Search Console API連携仕様を作る
- [ ] ヨルスキか住系ポータルで試す
