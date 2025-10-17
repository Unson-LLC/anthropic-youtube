# Claude Coded: Sonnet 4.5、Claude Code 2.0 など。

URL: https://www.youtube.com/watch?v=Yct0MvNtdfU
数値: 98
時間: 5m

# Claude Coded アップデート要約

## 🚀 Claude Sonnet 4.5 リリース

- **世界最高のコーディングモデル**として登場
- SWE-bench Verifiedで**77.2%**のスコアを達成
- 複雑なタスクに**30時間以上**集中して取り組める性能
- コードだけでなく、推論、数学、コンピュータ操作も大幅改善
- OS Worldテストで4ヶ月前の42%から**61%超**に向上

## 🔧 Claude Code 2.0の主な改善

### VS Code拡張機能（ベータ版）

- IDEに直接統合可能
- サイドバーパネルでリアルタイムの変更をインライン差分表示
- ターミナルよりIDEを好む開発者向け

### ターミナルUI刷新

- インターフェース更新
- ステータス表示の改善
- 検索可能なプロンプト履歴

### 新機能: チェックポイント

- 大規模タスク実行時に**瞬時にロールバック**可能
- `/re`コマンドまたはEscキー2回で起動
- コード、会話、または両方を以前の状態に復元
- ※Claudeの編集のみが対象（ユーザー編集やbashコマンドは除外）

### その他の改善

- **Thinking機能**のオン/オフをワンタップで切り替え（設定は保存される）
- `/usage`コマンドでリアルタイム使用量追跡

## 🤖 Claude API の新機能

### Context Editing

- トークン制限に近づくと、古いツール呼び出しと結果を自動削除
- 会話の流れを保ちながらエージェントの実行時間を延長

### Memory Tool

- コンテキストウィンドウ外に情報を保存
- ファイルベースのシステム
- 専用メモリディレクトリでファイルのCRUD操作が可能
- クライアント側に保存され、会話をまたいで永続化

### Claude Agent SDK

- Claude Code SDKから改名
- エージェント構築用のコアツール、コンテキスト管理、権限フレームワークを提供

## 📊 Claudeアプリの新機能

- コードを使ったデータ分析、ファイル作成、インサイト可視化
- 自然言語プロンプトで以下を生成可能：
    - Excelスプレッドシート
    - PowerPointプレゼンテーション
    - Word文書
    - PDFファイル
- 有料プランでプレビュー利用可能

## 🌐 その他

- **Claude for Chrome拡張機能**がウェイトリスト全員に公開（cloud.ai/chrome）

## 原文文字起こし

- Welcome to Claude Coded, your update on what's new with Claude and Claude Code. First up, Claudson 4.5 is now available wherever you get your Claude and it is the best coding model in the world. It is leading on SweetBench verified with a score of 77.2% and we have actually seen it stay focused on complex tasks for well over 30 hours straight.
- As a developer, this is really exciting. But it is not just code that has been improved. We have seen substantial gains on reasoning, math, and computer use as well. On OS World, which is a test to see how well an AI can actually use a computer like a human would, Claude jumped from 42% 4 months ago to over 61% now.
- And you can actually see this in action for yourself with our recently launched Claw for Chrome extension, which has been expanded to everybody that was on the wait list. So go and give it a try today at cloud.ai/chrome. Cloud Code got a ton of new improvements as well, starting with a native VS Code extension that brings Cloud Code directly into your IDE.
- This is perfect for developers like myself who prefer programming in an IDE over the terminal. With this extension, you can see Clots's changes in real time through a dedicated sidebar panel that shows inline diffs of the changes made. This extension is currently in beta and you can get it in the VS Code marketplace.
- We didn't forget about the terminal and a refresh terminal UI with a bunk to version 2.0 of cloud code brings you updated interface features, improved status visibility and a searchable prompt history as well. But the feature that I am most excited about is a new checkpoints feature that lets you confidently run large tasks and roll back instantly to a previous state if needed.
- You can use the /re command or double hit the escape key to activate and can then choose to restore the code to conversation or both to a prior state. But do note that checkpoints only apply to edits made by Claude, not user edits or bash commands. So it is still recommended that you use this feature in combination with your version control system.
- We've also made an update to thinking where now you can enable or disable it with just a tap key. And the best part here is that it's going to save your preference across sessions. Finally, you can now track your usage in real time with the / usage command. You can also do this in the cloud app by going to settings and then usage to view your data.
- On the cloud API front, we have two new capabilities, enabling agents to handle even greater complexity. Context editing automatically clears stale tool calls and results from within the context window when approaching token limits. As your agent executes tasks and accumulates tool results, context editing removes stale content while preserving the conversation flow, effectively extending how long an agent can run without manual user intervention.
- The memory tool, on the other hand, enables Claude to store and consult information outside of the context window through a file-based system. Claude can create, read, update, and delete files in a dedicated memory directory, stored in your infrastructure that is entirely clientside, and persists across conversations. It's kind of like having a claw.
- md file for your agent API. You can see an example of these capabilities in our Claude plays katan video, but we also have a couple of cookbooks created to show you how to leverage these new capabilities. Additionally, the Cloud Agent SDK has been renamed from the Cloud Code SDK and gives you access to the same core tools, context management systems, and permissions frameworks that Power Cloud Code to help you build your own agents.
- We have learned a ton over the last 6 months and put it all in this Cloud Agent SDK for you to use. And finally, in the Claude app, Claude can now use code to analyze data, create files, and visualize insights in the files and formats that you are familiar with. You can prompt Claude using natural language to generate Excel spreadsheets, create PowerPoint presentations, draft up word documents, or create PDF files that you can instantly download and use.
- This capability is now available to all paid plans in preview. And that is it for cloudcoded. Happy coding and keep thinking.