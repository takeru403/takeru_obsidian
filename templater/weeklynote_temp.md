---
tags:
  - weekly
  - <%
  - tp.file.title
  - "%>"
---

#### << [[<% moment(tp.file.title).add(-1, 'W').format('YYYY-[W]WW') %>|Last week]] | [[<% moment(tp.file.title).add(1, 'W').format('YYYY-[W]WW') %>|Next week]] >>

今年の残り週数：<% moment(`${moment(tp.file.title).endOf('year')}`).diff(tp.file.title, "w") %>週

## 週次レビューチェックリスト

- [ ] トリガーリストを見ながら気になっていることを殴り書き
- [ ] 日記を読みながら今週の発見を箇条書きする
- [ ] 来週の目標を箇条書きする
- [ ] 来週の目標をタスク化してcalendarに入れる
- [ ] 来週のスケジュール・天気確認

## 気になっていること・悩み

-

## 今週の発見

-

## 来週の目標

-

## 一週間のメモ

![[<% tp.date.weekday("YYYY-MM-DD", 0, tp.file.title, "YYYY-[W]ww") %>#Memo]]
![[<% tp.date.weekday("YYYY-MM-DD", 1, tp.file.title, "YYYY-[W]ww") %>#Memo]]
![[<% tp.date.weekday("YYYY-MM-DD", 2, tp.file.title, "YYYY-[W]ww") %>#Memo]]
![[<% tp.date.weekday("YYYY-MM-DD", 3, tp.file.title, "YYYY-[W]ww") %>#Memo]]
![[<% tp.date.weekday("YYYY-MM-DD", 4, tp.file.title, "YYYY-[W]ww") %>#Memo]]
![[<% tp.date.weekday("YYYY-MM-DD", 5, tp.file.title, "YYYY-[W]ww") %>#Memo]]
![[<% tp.date.weekday("YYYY-MM-DD", 6, tp.file.title, "YYYY-[W]ww") %>#Memo]]

## 一週間のタスク

![[<% tp.date.weekday("YYYY-MM-DD", 0, tp.file.title, "YYYY-[W]ww") %>#Diary：<% tp.date.weekday("YYYY-MM-DD (dd)", 0, tp.file.title, "YYYY-[W]ww") %>]]
![[<% tp.date.weekday("YYYY-MM-DD", 1, tp.file.title, "YYYY-[W]ww") %>#Diary：<% tp.date.weekday("YYYY-MM-DD (dd)", 1, tp.file.title, "YYYY-[W]ww") %>]]
![[<% tp.date.weekday("YYYY-MM-DD", 2, tp.file.title, "YYYY-[W]ww") %>#Diary：<% tp.date.weekday("YYYY-MM-DD (dd)", 2, tp.file.title, "YYYY-[W]ww") %>]]
![[<% tp.date.weekday("YYYY-MM-DD", 3, tp.file.title, "YYYY-[W]ww") %>#Diary：<% tp.date.weekday("YYYY-MM-DD (dd)", 3, tp.file.title, "YYYY-[W]ww") %>]]
![[<% tp.date.weekday("YYYY-MM-DD", 4, tp.file.title, "YYYY-[W]ww") %>#Diary：<% tp.date.weekday("YYYY-MM-DD (dd)", 4, tp.file.title, "YYYY-[W]ww") %>]]
![[<% tp.date.weekday("YYYY-MM-DD", 5, tp.file.title, "YYYY-[W]ww") %>#Diary：<% tp.date.weekday("YYYY-MM-DD (dd)", 5, tp.file.title, "YYYY-[W]ww") %>]]
![[<% tp.date.weekday("YYYY-MM-DD", 6, tp.file.title, "YYYY-[W]ww") %>#Diary：<% tp.date.weekday("YYYY-MM-DD (dd)", 6, tp.file.title, "YYYY-[W]ww") %>]]

