---
name: 🤖 AIタスク依頼
about: 山崎AI社員組織へのタスク依頼テンプレート（Codex・Co-Work両対応）
title: "[担当者名] タスクの概要をここに記入"
labels: "status:new"
assignees: golmon-hy
---

## 📋 タスク概要

<!-- タスクの目的と背景を簡潔に記入してください -->

## 👤 担当AI社員

<!-- 以下から選択してください（複数可） -->
- [ ] 佐藤（代表秘書） → `role:secretary`
- [ ] 高橋（Google広告） → `role:google-ads`
- [ ] 田中（Meta広告） → `role:meta-ads`
- [ ] 大西（AI整体note） → `role:health-content`
- [ ] 中島（note・X戦略） → `role:content-strategy`
- [ ] 川村（AIチャンネル） → `role:youtube`
- [ ] 黒田（整体心理CH） → `role:health-channel`
- [ ] 國井（コピーライター） → `role:copywriter`
- [ ] 中村（デザインプランナー） → `role:design`
- [ ] 木村（アートディレクター） → `role:art-direction`
- [ ] 吉田（品質管理QA） → `role:qa`
- [ ] 森田（ナレッジ管理） → `role:knowledge`
- [ ] 鈴木（スキル開発） → `role:training`
- [ ] 種市（法務レビュアー） → `role:legal`

## 🎯 成果物・期待するアウトプット

<!-- 何を作ってほしいか具体的に記入 -->

## 📅 期日

<!-- 例: 2026年6月10日まで -->

## 📎 参照資料・参考URL

<!-- 関連ドキュメント・URLがあれば記入 -->

## 🤖 AIエージェント使用方法

### Codex（OpenAI Codex / ChatGPT）を使う場合
```
1. このIssueのURLをCodexに渡す
2. 「このIssueを読んで、AGENTS.mdの[担当者名]として作業してください」と指示
3. agents/[担当者ファイル].md を参照するよう伝える
```

### Co-Work（GitHub Copilot Workspace）を使う場合
```
1. このIssueをGitHubで開く
2. Copilot Workspaceで「Start working」をクリック
3. .github/copilot-instructions.mdが自動読み込みされ、AI社員として作業開始
```

## ✅ 完了条件

- [ ] 成果物が作成された
- [ ] QA（吉田）のレビューを受けた
- [ ] 法務確認が必要な場合は種市に確認した
- [ ] ナレッジ管理（森田）に記録を共有した
