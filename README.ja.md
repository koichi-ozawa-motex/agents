# Contains Studio AI エージェント

迅速な開発のあらゆる側面を加速し、向上させるために設計された専門AIエージェントの包括的なコレクション。各エージェントはその分野の専門家であり、専門知識が必要な時に呼び出せる準備ができています。

## 📥 インストール

1. **このリポジトリをダウンロード:**
   ```bash
   git clone https://github.com/contains-studio/agents.git
   ```

2. **Claude Code エージェントディレクトリにコピー:**
   ```bash
   cp -r agents/* ~/.claude/agents/
   ```
   
   または、すべてのエージェントファイルを手動で `~/.claude/agents/` ディレクトリにコピーしてください。

3. **Claude Code を再起動**して新しいエージェントを読み込みます。

## 🚀 クイックスタート

エージェントは Claude Code で自動的に利用可能です。タスクを説明するだけで、適切なエージェントがトリガーされます。エージェントの名前を言及することで、明示的にエージェントを要求することもできます。

📚 **詳細情報:** [Claude Code サブエージェントドキュメント](https://docs.anthropic.com/en/docs/claude-code/sub-agents)

### 使用例
- "瞑想習慣を追跡する新しいアプリを作成して" → `rapid-prototyper`
- "TikTokで何がトレンドになっていて、私たちが構築できるものは？" → `trend-researcher`
- "アプリのレビューが下がっている、何が問題？" → `feedback-synthesizer`
- "このローディング画面をもっと楽しくして" → `whimsy-injector`

## 📁 ディレクトリ構造

エージェントは部門別に整理されており、簡単に見つけることができます：

```
contains-studio-agents/
├── design/
│   ├── brand-guardian.md
│   ├── ui-designer.md
│   ├── ux-researcher.md
│   ├── visual-storyteller.md
│   └── whimsy-injector.md
├── engineering/
│   ├── ai-engineer.md
│   ├── backend-architect.md
│   ├── devops-automator.md
│   ├── frontend-developer.md
│   ├── mobile-app-builder.md
│   ├── rapid-prototyper.md
│   └── test-writer-fixer.md
├── marketing/
│   ├── app-store-optimizer.md
│   ├── content-creator.md
│   ├── growth-hacker.md
│   ├── instagram-curator.md
│   ├── reddit-community-builder.md
│   ├── tiktok-strategist.md
│   └── twitter-engager.md
├── product/
│   ├── feedback-synthesizer.md
│   ├── sprint-prioritizer.md
│   └── trend-researcher.md
├── project-management/
│   ├── experiment-tracker.md
│   ├── project-shipper.md
│   └── studio-producer.md
├── studio-operations/
│   ├── analytics-reporter.md
│   ├── finance-tracker.md
│   ├── infrastructure-maintainer.md
│   ├── legal-compliance-checker.md
│   └── support-responder.md
├── testing/
│   ├── api-tester.md
│   ├── performance-benchmarker.md
│   ├── test-results-analyzer.md
│   ├── tool-evaluator.md
│   └── workflow-optimizer.md
└── bonus/
    ├── joker.md
    └── studio-coach.md
```

## 📋 完全なエージェントリスト

### エンジニアリング部門 (`engineering/`)
- **ai-engineer** - 実際にリリースされるAI/ML機能を統合
- **backend-architect** - スケーラブルなAPIとサーバーシステムを設計
- **devops-automator** - 何も壊さずに継続的にデプロイ
- **frontend-developer** - 高速なユーザーインターフェースを構築
- **mobile-app-builder** - ネイティブiOS/Android体験を作成
- **rapid-prototyper** - 数週間ではなく数日でMVPを構築
- **test-writer-fixer** - 実際のバグをキャッチするテストを書く

### プロダクト部門 (`product/`)
- **feedback-synthesizer** - 苦情を機能に変換
- **sprint-prioritizer** - 6日間で最大価値をリリース
- **trend-researcher** - バイラル機会を特定

### マーケティング部門 (`marketing/`)
- **app-store-optimizer** - アプリストア検索結果を支配
- **content-creator** - すべてのプラットフォームでコンテンツを生成
- **growth-hacker** - バイラル成長ループを見つけて活用
- **instagram-curator** - ビジュアルコンテンツゲームをマスター
- **reddit-community-builder** - 禁止されずにRedditで勝つ
- **tiktok-strategist** - シェア可能なマーケティング瞬間を作成
- **twitter-engager** - トレンドに乗ってバイラルエンゲージメントを獲得

### デザイン部門 (`design/`)
- **brand-guardian** - どこでも視覚的アイデンティティを一貫して保持
- **ui-designer** - 開発者が実際に構築できるインターフェースを設計
- **ux-researcher** - ユーザーインサイトをプロダクト改善に変換
- **visual-storyteller** - コンバージョンとシェアを促進するビジュアルを作成
- **whimsy-injector** - すべてのインタラクションに喜びを注入

### プロジェクト管理 (`project-management/`)
- **experiment-tracker** - データ駆動の機能検証
- **project-shipper** - クラッシュしないプロダクトをローンチ
- **studio-producer** - チームを会議ではなくリリースに集中させる

### スタジオ運営 (`studio-operations/`)
- **analytics-reporter** - データを実行可能なインサイトに変換
- **finance-tracker** - スタジオを利益を上げ続ける
- **infrastructure-maintainer** - 銀行を破綻させずにスケール
- **legal-compliance-checker** - 速く動きながら法的に適切に
- **support-responder** - 怒ったユーザーを擁護者に変える

### テスト・ベンチマーク (`testing/`)
- **api-tester** - APIが圧力下で動作することを保証
- **performance-benchmarker** - すべてをより高速に
- **test-results-analyzer** - テスト失敗のパターンを見つける
- **tool-evaluator** - 実際に役立つツールを選択
- **workflow-optimizer** - ワークフローのボトルネックを排除

## 🎁 ボーナスエージェント
- **studio-coach** - AI部隊を卓越性に向けて鼓舞
- **joker** - テックユーモアで雰囲気を明るく

## 🎯 プロアクティブエージェント

一部のエージェントは特定のコンテキストで自動的にトリガーされます：
- **studio-coach** - 複雑なマルチエージェントタスクが開始された時、またはエージェントがガイダンスを必要とする時
- **test-writer-fixer** - 機能実装、バグ修正、コード変更後
- **whimsy-injector** - UI/UX変更後
- **experiment-tracker** - 機能フラグが追加された時

## 💡 ベストプラクティス

1. **エージェントを協力させる** - 多くのタスクは複数のエージェントから恩恵を受ける
2. **具体的にする** - 明確なタスク説明はエージェントのパフォーマンス向上に役立つ
3. **専門知識を信頼する** - エージェントは特定の分野のために設計されている
4. **迅速に反復する** - エージェントは6日間スプリント哲学をサポート

## 🔧 技術詳細

### エージェント構造
各エージェントには以下が含まれます：
- **name**: 一意の識別子
- **description**: エージェントを使用するタイミングと例
- **color**: 視覚的識別
- **tools**: エージェントがアクセスできる特定のツール
- **System prompt**: 詳細な専門知識と指示

### 新しいエージェントの追加
1. 適切な部門フォルダに新しい `.md` ファイルを作成
2. YAMLフロントマターで既存のフォーマットに従う
3. 3-4の詳細な使用例を含める
4. 包括的なシステムプロンプトを書く（500語以上）
5. 実際のタスクでエージェントをテスト

## 📊 エージェントパフォーマンス

以下を通じてエージェントの効果を追跡：
- タスク完了時間
- ユーザー満足度
- エラー率
- 機能採用
- 開発速度

## 🚦 ステータス

- ✅ **アクティブ**: 完全に機能し、テスト済み
- 🚧 **Coming Soon**: 開発中
- 🧪 **ベータ**: 限定的な機能でテスト中

## 🛠️ あなたのスタジオ用にエージェントをカスタマイズ

### エージェントカスタマイズTodoリスト

あなたの特定のニーズに合わせてエージェントを作成または修正する際にこのチェックリストを使用してください：

#### 📋 必要なコンポーネント
- [ ] **YAMLフロントマター**
  - [ ] `name`: 一意のエージェント識別子（kebab-case）
  - [ ] `description`: 使用タイミング + コンテキスト/コメンタリー付きの3-4の詳細な例
  - [ ] `color`: 視覚的識別（例：blue, green, purple, indigo）
  - [ ] `tools`: エージェントがアクセスできる特定のツール（Write, Read, MultiEdit, Bash, など）

#### 📝 システムプロンプト要件（500語以上）
- [ ] **エージェントアイデンティティ**: 明確な役割定義と専門分野
- [ ] **主要責任**: 5-8の特定の主要な義務
- [ ] **分野専門知識**: 技術スキルと知識分野
- [ ] **スタジオ統合**: エージェントが6日間スプリントワークフローにどのように適合するか
- [ ] **ベストプラクティス**: 特定の方法論とアプローチ
- [ ] **制約**: エージェントがすべき/すべきでないこと
- [ ] **成功指標**: エージェントの効果を測定する方法

#### 🎯 エージェントタイプ別の必要な例

**エンジニアリングエージェント**は以下の例が必要：
- [ ] 機能実装要求
- [ ] バグ修正シナリオ
- [ ] コードリファクタリングタスク
- [ ] アーキテクチャ決定

**デザインエージェント**は以下の例が必要：
- [ ] 新しいUIコンポーネント作成
- [ ] デザインシステム作業
- [ ] ユーザー体験問題
- [ ] 視覚的アイデンティティタスク

**マーケティングエージェント**は以下の例が必要：
- [ ] キャンペーン作成要求
- [ ] プラットフォーム固有のコンテンツニーズ
- [ ] 成長機会特定
- [ ] ブランドポジショニングタスク

**プロダクトエージェント**は以下の例が必要：
- [ ] 機能優先順位決定
- [ ] ユーザーフィードバック分析
- [ ] 市場調査要求
- [ ] 戦略的計画ニーズ

**運営エージェント**は以下の例が必要：
- [ ] プロセス最適化
- [ ] ツール評価
- [ ] リソース管理
- [ ] パフォーマンス分析

#### ✅ テスト・検証チェックリスト
- [ ] **トリガーテスト**: エージェントが意図した使用ケースで正しくアクティブ化
- [ ] **ツールアクセス**: エージェントがすべての指定されたツールを適切に使用可能
- [ ] **出力品質**: レスポンスが有用で実行可能
- [ ] **エッジケース**: エージェントが予期しないまたは複雑なシナリオを処理
- [ ] **統合**: マルチエージェントワークフローで他のエージェントと良好に連携
- [ ] **パフォーマンス**: 合理的な時間枠内でタスクを完了
- [ ] **ドキュメント**: 例が実際の使用パターンを正確に反映

#### 🔧 エージェントファイル構造テンプレート

```markdown
---
name: your-agent-name
description: Use this agent when [scenario]. This agent specializes in [expertise]. Examples:\n\n<example>\nContext: [situation]\nuser: "[user request]"\nassistant: "[response approach]"\n<commentary>\n[why this example matters]\n</commentary>\n</example>\n\n[3 more examples...]
color: agent-color
tools: Tool1, Tool2, Tool3
---

You are a [role] who [primary function]. Your expertise spans [domains]. You understand that in 6-day sprints, [sprint constraint], so you [approach].

Your primary responsibilities:
1. [Responsibility 1]
2. [Responsibility 2]
...

[Detailed system prompt content...]

Your goal is to [ultimate objective]. You [key behavior traits]. Remember: [key philosophy for 6-day sprints].
```

#### 📂 部門別ガイドライン

**エンジニアリング** (`engineering/`): 実装速度、コード品質、テストに焦点
**デザイン** (`design/`): ユーザー体験、視覚的一貫性、迅速な反復を強調
**マーケティング** (`marketing/`): バイラル可能性、プラットフォーム専門知識、成長指標をターゲット
**プロダクト** (`product/`): ユーザー価値、データ駆動決定、市場適合性を優先
**運営** (`studio-operations/`): プロセス最適化、摩擦削減、システムスケール
**テスト** (`testing/`): 品質保証、ボトルネック発見、パフォーマンス検証
**プロジェクト管理** (`project-management/`): チーム調整、時間通りリリース、スコープ管理

#### 🎨 カスタマイズ

あなたのニーズに合わせてこれらの要素を修正：
- [ ] 例をあなたのプロダクトタイプに合わせて調整
- [ ] エージェントがアクセスできる特定のツールを追加
- [ ] あなたのKPIに合わせて成功指標を修正
- [ ] 必要に応じて部門構造を更新
- [ ] あなたのブランドに合わせてエージェントカラーをカスタマイズ

## 🤝 貢献

既存のエージェントを改善したり、新しいエージェントを提案するには：
1. 上記のカスタマイズチェックリストを使用
2. 実際のプロジェクトで徹底的にテスト
3. パフォーマンス改善を文書化
4. 成功したパターンをコミュニティと共有 