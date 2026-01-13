# RI Eval Lab｜方式名『複素構造評価』 / Complex Structure Evaluation

本リポジトリは、RI Eval Lab が提唱する方式名『複素構造評価』/ Complex Structure Evaluation の「概要・用語・注意事項（無料範囲）」を整理するための公開リポジトリです。  
公式参照先（正本）は、当面は note 記事（入門編／実装編の「2．方式名『複素構造評価』とは？」）とします。将来、ブログ等へ移行する場合は本行および下記リンクを更新します（更新ポリシー：本READMEは原則静的運用。誤記修正等を除き、参照先リンクの差し替えに限ります。変更はコミット履歴として残ります）：
- 入門編：https://note.com/rievallab/n/n5fe94209edf2
- 実装編：https://note.com/rievallab/n/n4c040c966c08

公開範囲：本リポジトリは概要・用語・注意事項のみを対象とし、運用設計の詳細、テンプレート、例題、判断基準等は含めません。

## 概要（Definition / Overview）

方式名『複素構造評価』（以下、本方式）は、RI Eval Lab が提唱する評価設計の枠組みです。複素平面を可視化の比喩として援用し、対象の定量指標群（R軸: Recordable）と定性指標群（I軸: Interpretive）を正規化・加重して **v = (R, I)** の二次元ベクトルとして表現し、分野横断で比較可能な読み方へ整える評価プロトコル（標準手順）を扱います。  
※用語注記：本READMEの R/I は Recordable/Interpretive の略で、Real/Imaginary ではありません。  
矢印の長さ **‖v‖** と角度 **θ = atan2(I, R)** は、読み取りの補助指標として用います。  
“複素”は見せ方の比喩であり、複素解析の計算を前提としません。また、本方式は数学の「複素構造（complex structure）」とも別概念です。

### 一言（ひとこと）：直感的なイメージ（簡易説明）
R と I の2つの「ものさし」で対象を点（R, I）として表すイメージです。矢印の長さは“全体の大きさ”、角度は“どちら寄りか”を示します。  
※簡易説明です。正式・最新版の説明は note（正本）を参照してください。

## リンク（Official References）
- note（入門編）：https://note.com/rievallab/n/n5fe94209edf2
- note（実装編）：https://note.com/rievallab/n/n4c040c966c08
- 転載・引用ポリシー／名称の取り扱い：NOTICE.md
- 更新履歴：CHANGELOG.md
- 権利／許諾：LICENSE
