# Summary of Changes

## Link to Ticket

<!--
  Final PR (one line per Issue) / 最終 PR（1 Issue につき 1 行）:
    Deliver: #123
    Deliver: #456

  Intermediate PR (Stacked PR, etc.) / 中間 PR（Stacked PR 等）:
    Part of: #123
    Part of: #456

  * Deliver: triggers status sync on merge (Status → Acceptance Testing)
    マージ時に Issue が「受入検証中」に自動遷移し、担当者が受入検証者に変更されます
  * Part of: links only — no status change / ステータス変更なし（リンクのみ）
  * Do NOT use Closes / Fixes / Resolves (they close the Issue before acceptance testing)
    Closes 等は受入検証前に Issue がクローズされるため使わないでください
-->

## Stack (if stacked PR)

<!--
  For Stacked PRs, list all PRs in the stack in order. Mark the current PR with 👈.
  Delete this section for standalone PRs.
  Stacked PR の場合、スタック内の全 PR を順番にリストし、現在の PR に 👈 を付けてください。
  単独 PR の場合はこのセクションを削除してください。

  Use (planned) for PRs not yet created. If you start working on a follow-up branch,
  add it as (planned) BEFORE the current PR is merged.
  未作成の PR には (planned) を使用。後続ブランチの作業を開始したら、
  現在の PR がマージされる前に (planned) として追記してください。

  Example / 例:
  1. #101 feat: add user schema
  2. #102 feat: add user API 👈
  3. (planned) feat: add user UI
-->

## Deployment tasks (required if DB migration or script is needed)

<!-- Environment(s), command, timing, rollback, etc. -->

## 🐛Bug fixes: Root cause (required for bug fixes)

## 🐛Bug fixes: Fix (required for bug fixes)

## Screenshots / Screen recordings

## Optional: Issues or remaining work

## Optional: Notes for reviewers
