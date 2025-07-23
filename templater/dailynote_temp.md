---
aliases:
  - "<% moment(tp.file.title).format('MMDD') %>"
  - "<% moment(tp.file.title).format('YYYYMMDD') %>"
tags:
  - "daily"
  - "<% moment(tp.file.title).format('YYYY') %>"
  - "<% moment(tp.file.title).format('YYYY-MM') %>"
---
---
aliases:
  - "<% moment(tp.file.title).format('MMDD') %>"
  - "<% moment(tp.file.title).format('YYYYMMDD') %>"
tags:
  - "daily"
  - "<% moment(tp.file.title).format('YYYY') %>"
  - "<% moment(tp.file.title).format('YYYY-MM') %>"
---
#### << [[<% moment(tp.file.title).add(-1, 'd').format('YYYY-MM-DD') %>|Yesterday]] | [[<% moment(tp.file.title).add(-1, 'y').format('YYYY-MM-DD') %>|Last year]] | [[<% moment(tp.file.title).add(1, 'd').format('YYYY-MM-DD') %>|Tomorrow]] >>

今年の残り日数：<% moment(`${moment(tp.file.title).endOf('year')}`).diff(tp.file.title, "days") %>日

-----------------------------------

## Diary：<% moment(tp.file.title).format("YYYY-MM-DD (ddd)") %>

- 

## Memo

- 


