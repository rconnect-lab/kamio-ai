# Community Post Templates

## X / Discord向け（短文）
kamio-ai のサンプルを公開しました。  
既存資産を壊さない `isolated_phase1/` 構成で、神尾AIの判断・文体・優先順位を実務で使える形に整理しています。  
Phase1のたたき台としてどうぞ。  
https://github.com/rconnect-lab/kamio-ai

## コミュニティ告知（中文）
kamio-ai のサンプルリリースを公開します。  
今回の公開は、既存実装とは分離した `isolated_phase1/` を追加する形式です。  

含まれるもの:
- 判断ルール（decision_rules）
- 判断ケース集（decision_cases）
- 文体ガイド（writing_style / writing_style_cases）
- 委任範囲（delegation_scope / do_not_delegate）
- 優先タスク（tasks）

狙いは、抽象論ではなく「今日から動ける」標準形を共有することです。  
Phase1は速度優先、必要に応じてPhase2で補強します。  
https://github.com/rconnect-lab/kamio-ai

### 利用方法（投稿に追記する行）
- 利用開始は `isolated_phase1/README.md` から
- 判断は `strategy/decision_rules.md` を基準に固定
- 文体は `style/writing_style.md` と `style/writing_style_cases.md` を参照
- 案件別の判断は `strategy/decision_cases.md` を使う
- 委任可否は `governance/*` で線引きする

## リリースノート誘導文
詳細は以下を参照してください。  
- `isolated_phase1/release/community_sample_release.md`
- `isolated_phase1/README.md`
