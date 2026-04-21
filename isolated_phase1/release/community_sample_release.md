# Kamio AI Sample Release v0.1 (Community)

## 結論
kamio-ai のサンプルリリースとして、`isolated_phase1/` をコミュニティ公開する。

## 今回公開する内容
- `isolated_phase1/README.md`
- `isolated_phase1/context/*`
- `isolated_phase1/strategy/*`
- `isolated_phase1/style/*`
- `isolated_phase1/governance/*`
- `isolated_phase1/execution/tasks.md`

## 公開メッセージ（短文）
神尾AIのPhase1標準構成を、既存実装を壊さない隔離構成で公開しました。  
判断ルール・文体・委任範囲・実行タスクまで一式を含みます。  
実務で使えるたたき台として提供し、必要に応じてPhase2で補強します。

## 何ができるか
- 神尾スタイルの意思決定を再現しやすくする
- 下書き品質と初動速度を上げる
- 役員AIへの横展開の雛形にする

## 使い方
1. `isolated_phase1/README.md` を読む
2. `context/profile.md` と `strategy/decision_rules.md` を読む
3. `style/writing_style.md` と `style/writing_style_cases.md` を読む
4. `execution/tasks.md` から着手する

## 利用方法（実務運用）
1. 依頼を受けたら、まず `strategy/decision_rules.md` で判断方針を固定する
2. 文面作成時は `style/writing_style.md` と `style/writing_style_cases.md` を参照する
3. 判断が難しい案件は `strategy/decision_cases.md` の該当ケースに当てる
4. 委任可否は `governance/delegation_scope.md` と `governance/do_not_delegate.md` で線引きする
5. 実行は `execution/tasks.md` の優先順で進め、出力は「そのまま使える形」まで落とす

## 注意
- これは Phase1 のサンプル
- 法務・コンプラ・対外表現の最終確認は人間が行う
- 既存資産（ルート配下）は変更しない前提

## 次の展開
- Phase2で、実案件ログに基づくケース拡張
- KPI運用・レビュー運用の標準化
- 役員別プロンプト分岐

## 非デジタルネイティブ向け補足
- UI/UXガイド: `isolated_phase1/release/non_digital_native_ux_guidelines.md`
- 利用シーン集: `isolated_phase1/release/non_digital_native_usage_scenarios.md`

## 非デジタルネイティブ向け対応
- 利用シーン起点の説明を採用（機能説明より先に場面説明）
- 初回体験は3ステップ以内で完了する設計
- フォームが難しい方は `briefing@orca1.net` で受付
- 詳細ガイド: `isolated_phase1/release/non_digital_native_ux_guide.md`
