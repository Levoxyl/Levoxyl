### ⚛️ Quantum Physics News
<% if (plugins.rss) { %>
<% for (const item of plugins.rss.items) { %>
- **<%= item.title %>** _Published on <%= f.date(item.pubDate, {date:true}) %>_
<% } %>
<% } %>

### 💻 LeetCode Progress
<% if (plugins.leetcode) { %>
Solved: <%= plugins.leetcode.solved.total %>
<% } %>
