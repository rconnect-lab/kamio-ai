# Release Checklist (Community Sample)

## 公開前
- [ ] ブランチが `feat/isolated-phase1-standard` である
- [ ] `origin/main...HEAD` の差分が `isolated_phase1/` のみである
- [ ] 機密情報（鍵・個人情報・社内限定情報）が含まれていない
- [ ] READMEのFirst Readが最新

## 公開時
- [ ] GitHub PRを作成
- [ ] PR本文に目的・変更範囲・非破壊性を記載
- [ ] コミュニティ向け告知文を投稿
- [ ] リリースノートへのリンクを添付

## 公開後（48時間）
- [ ] 質問への一次回答テンプレで対応
- [ ] フィードバックを `Phase2候補` として記録
- [ ] 次の改善項目を3つに絞る

## PR本文テンプレ
### 目的
- kamio-aiのPhase1標準構成を、既存資産を壊さずに隔離追加する。

### 変更範囲
- `isolated_phase1/` 配下の新規追加のみ。

### 期待効果
- 神尾AIの判断・文体・優先順位の再現性を高める。
- 実務投入の初速を上げる。

### 非破壊性
- 既存ルートの `README/context/strategy/execution` は上書きしない。
