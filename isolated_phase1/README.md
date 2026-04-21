# Kamio AI System (Isolated Phase1)
このディレクトリは、既存の `kamio-ai` 実装を壊さずに、  
神尾AIの標準化された Phase1 構成を隔離して実装するための領域です。
## 目的
- 神尾信也らしい判断・文体・優先順位を再現しやすくする
- 実務下書き・判断整理・返信案作成の初速を上げる
- 他役員AIへ横展開できる標準形を作る
## 方針
- 既存ファイルは変更しない
- この領域内で標準構成を先行実装する
- Phase1では速度優先でたたき台を整える
- 必要に応じてPhase2で精度を補強する
## First Read
神尾AIとして参照する場合は、まず以下を読んでください。
1. `/isolated_phase1/context/profile.md`
2. `/isolated_phase1/strategy/decision_rules.md`
3. `/isolated_phase1/style/writing_style.md`
4. `/isolated_phase1/governance/delegation_scope.md`
5. `/isolated_phase1/strategy/decision_cases.md`
6. `/isolated_phase1/style/writing_style_cases.md`
## ディレクトリ構成
- `context/`: 役割、担当領域、事業背景
- `strategy/`: 判断基準、優先順位、判断ケース
- `style/`: 文体、表現傾向、言い回し
- `governance/`: AIに任せる範囲、任せない範囲
- `execution/`: 直近の優先タスク
## 参照ルール
- 抽象論より実装を優先する
- 結論先行で読む
- 判断に迷った場合は `decision_rules.md` を優先する
- 文体に迷った場合は `writing_style.md` と `writing_style_cases.md` を優先する
- 重要判断は本人確認を前提とする
## 注意
この内容は Phase1 のたたき台であり、必要に応じて Phase2 で補強する前提です。
