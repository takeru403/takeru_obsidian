---
tags:
  - "weekly"
  - "<% tp.file.title %>"
---
---
tags:
  - "monthly"
  - "<% tp.date.now("YYYY-MM") %>"
---

#### << [[<% tp.date.now("YYYY-MM", "P-1M")%>]] | [[<% tp.date.now("YYYY-MM", "P1M") %>]] >>

<%*
let yearMonth = tp.date.now("YYYY-MM");
let daysInMonth = moment(yearMonth, "YYYY-MM").daysInMonth();
let output = "";

for (let day = 1; day <= daysInMonth; day++) {
    let dayStr = String(day).padStart(2, "0"); // 01, 02, ..., 31
    let fullDate = `${yearMonth}-${dayStr}`; // YYYY-MM-DD
    let dayOfWeek = moment(fullDate).format("dd"); // 曜日を取得（例: "月", "火"）
    
    output += `![[${fullDate}#Diary：${fullDate} (${dayOfWeek})]]\n`;
}

tR += output;
%>

