# co-thinking-lab

AIと共に思考を深めるための作業場。構造化された思考環境とClaudeCodeスキルを活用して、質の高い意思決定と問題解決をサポートします。

## 概要

co-thinking-labは、以下の3つの柱で思考を支援します:

1. **思考の憲法**: すべての思考の基盤となる原則と価値観
2. **多様なペルソナ**: 事業責任者、チームメンバー、エンドユーザーなど、複数の視点からのフィードバック
3. **構造化された思考パターン**: 問題分析、意思決定、ブレスト、学習、人事評価、会議アジェンダなど

## 特徴

### 憲法ベースの思考
`knowledge/constitution.md` に定義された原則に基づいて、一貫性のある質の高い思考を実現します。

- 誠実性: 事実と意見を区別し、不確実性を認識する
- 多様性: 複数の視点から物事を考える
- 構造化: 論理的で可視化された思考プロセス
- 実践性: 実行可能な解決策を目指す
- 継続的改善: 過去から学び、フィードバックを活用する

### ペルソナによる多角的視点
`knowledge/personas/` に定義された3つのペルソナが、思考に多様な視点を提供します:

- **事業責任者**: ビジネス価値、ROI、戦略適合性の視点
- **チームメンバー**: 実現可能性、リソース、保守性の視点
- **エンドユーザー**: 使いやすさ、価値、体験の質の視点

### 6つの思考パターン
様々なシーンで使える思考フレームワークとテンプレート:

1. **問題分析・課題整理** (`think-analyze`)
2. **意思決定・選択肢評価** (`think-decide`)
3. **アイデア発想・ブレスト** (`think-brainstorm`)
4. **学習・知識整理** (`think-learn`)
5. **人事評価の検討** (`think-hr`)
6. **会議のアジェンダ作成** (`think-agenda`)

## ディレクトリ構造

```
co-thinking-lab/
├── knowledge/              # 思考の基盤となる知識
│   ├── constitution.md    # 思考の憲法（原則・価値観）
│   ├── personas/          # 多様な視点を持つペルソナ
│   ├── frameworks/        # 各思考パターンのフレームワーク
│   └── references/        # 参考資料・背景知識
├── templates/             # 思考セッションのテンプレート
├── sessions/              # 思考セッションのログ（日付で整理）
└── .claude/skills/        # ClaudeCodeスキル
    └── co-thinking/       # 協働思考スキルパッケージ
```

## 使い方

### 1. 思考の憲法を読む
まず、`knowledge/constitution.md` を読んで、このプロジェクトで大切にする原則と価値観を理解します。
必要に応じて、あなた自身の価値観に合わせてカスタマイズしてください。

### 2. ペルソナを理解する
`knowledge/personas/` の各ファイルを読んで、3つのペルソナの特徴と視点を把握します。
思考の際に、これらの視点からフィードバックを得ることができます。

### 3. ClaudeCodeスキルを使う
`.claude/skills/co-thinking/` に定義されたスキルを使って、構造化された思考を開始します。

#### 思考実行スキル
- `think-analyze`: 問題を分析し、課題を整理する
- `think-decide`: 選択肢を評価し、意思決定する
- `think-brainstorm`: アイデアを発散的に生み出す
- `think-learn`: 新しい知識を学び、整理する
- `think-hr`: 人事評価を多角的に検討する
- `think-agenda`: 効果的な会議アジェンダを作成する

#### 思考管理スキル
- `think-feedback`: ペルソナからフィードバックを得る
- `think-review`: 思考ログをレビューし、要約する
- `think-search`: 過去の思考ログを検索する
- `think-report`: 思考プロセスを可視化・レポート化する

### 4. 思考ログを保存・参照する
思考セッションは `sessions/YYYY/` に日付付きで自動保存されます。
過去の思考を振り返り、継続的に改善していくことができます。

## ワークフロー例

### 新しいプロダクト機能の意思決定
1. `think-decide` スキルで意思決定プロセスを開始
2. 憲法の原則（特に誠実性、多様性）を意識しながら選択肢を整理
3. 3つのペルソナの視点からフィードバックを得る:
   - 事業責任者: ROIは妥当か？戦略に合致するか？
   - チームメンバー: 実装可能か？リソースは十分か？
   - エンドユーザー: 使いやすいか？価値があるか？
4. 各視点を統合して、バランスの取れた意思決定
5. 思考ログを `sessions/` に保存

### 問題の分析と解決策の検討
1. `think-analyze` スキルで問題分析を開始
2. 憲法の原則（構造化、実践性）に基づいて問題を整理
3. `think-brainstorm` で解決策のアイデアを発散
4. `think-feedback` で各ペルソナからの視点を取得
5. `think-decide` で最適な解決策を選択
6. 思考の全プロセスを `sessions/` に記録

## カスタマイズ

### 憲法のカスタマイズ
`knowledge/constitution.md` を編集して、あなた自身の価値観や判断基準を反映させてください。

### ペルソナの追加
`knowledge/personas/` に新しいマークダウンファイルを追加することで、独自のペルソナを作成できます。
例: マーケター、投資家、規制当局などの視点

### フレームワークの拡張
`knowledge/frameworks/` に新しいフレームワークを追加したり、既存のものをカスタマイズしたりできます。

### テンプレートの改善
`templates/` のテンプレートは、あなたの思考スタイルに合わせて自由に変更できます。

## ベストプラクティス

### 思考の原則を意識する
すべての思考セッションで、憲法の5つの原則を意識しましょう:
1. 誠実性 2. 多様性 3. 構造化 4. 実践性 5. 継続的改善

### 複数の視点を取り入れる
重要な意思決定では、必ず3つのペルソナすべての視点からフィードバックを得ましょう。

### 思考ログを活用する
定期的に過去の思考ログを振り返り、パターンや改善点を見つけましょう。

### 継続的に改善する
憲法、ペルソナ、フレームワーク、テンプレートは、経験に基づいて継続的に改善していくものです。

## ファイル一覧

### 重要なファイル
- `knowledge/constitution.md`: 思考の憲法
- `knowledge/personas/business-owner.md`: 事業責任者ペルソナ
- `knowledge/personas/team-member.md`: チームメンバーペルソナ
- `knowledge/personas/end-user.md`: エンドユーザーペルソナ
- `.claude/skills/co-thinking/skill.json`: スキル定義ファイル

### フレームワーク
- `knowledge/frameworks/problem-analysis.md`
- `knowledge/frameworks/decision-making.md`
- `knowledge/frameworks/brainstorming.md`
- `knowledge/frameworks/learning.md`
- `knowledge/frameworks/hr-evaluation.md`
- `knowledge/frameworks/agenda.md`

### テンプレート
- `templates/problem-analysis.md`
- `templates/decision-making.md`
- `templates/brainstorming.md`
- `templates/learning.md`
- `templates/hr-evaluation.md`
- `templates/agenda.md`

## ライセンス

このプロジェクトはあなた自身の思考を支援するためのものです。自由にカスタマイズしてご利用ください。

---

*AIと共に、より深く、より良い思考を。*
