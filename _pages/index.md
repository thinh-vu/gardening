---
layout: page
title: Home
id: home
permalink: /
---

# 🌱🪴🌻 Plant.Grow.Flourish

Danh mục phân loại các ghi chú trong 🌱 "khu vườn" của tôi.

 🇻🇳 Chào mừng đến với "Khu vườn kỹ thuật số" của tôi, một góc nhỏ trên cõi mạng nơi tôi chia sẻ công khai các ghi chú của mình trước khi hoàn thiện chúng thành các bài viết hoàn chỉnh trên [Thinh Vu Blog](https://thinhvu.com)
Tại đây, bạn sẽ tìm thấy các thông tin và suy nghĩ của tôi về các chủ đề mà tôi đam mê. Hãy khám phá và tham gia thảo luận để cùng  góp sức trồng và nuôi dưỡng khu vườn này.

Lưu ý: Những ghi chú này tập trung nhiều hơn vào việc giúp "tôi của ngày mai" hiểu và suy nghĩ hơn là cho bạn tìm đọc, do đó bạn cũng đừng bất ngờ nếu nó không trau chuốt như nội dung trên Blog.

Nếu chủ đề nào bạn cảm thấy thú vị, đừng ngại trao đổi thêm với tôi qua [Messenger](https://www.messenger.com/t/mr.thinh.ueh) hoặc [Linkedin](https://www.linkedin.com/in/thinh-vu)

---

🇬🇧 Greetings and welcome to my Digital Garden project, a space where I openly share my notes before refining them into permanent blog posts that can be found on my website, <a href="https://thinhvu.com/"> Thinh Vu Blog </a>. Here, you will find a collection of my musings and insights on various topics that I am passionate about. Feel free to explore and engage with me in discussions as we cultivate and nurture this digital garden together.
Let's get started from here: [[map]]

<p style="padding: 3em 1em; background: #f5f7ff; border-radius: 4px;">
  Bạn có thể dạo quan khu vườn này và bắt đầu khám phá với danh mục nội dung <span style="font-weight: bold">[[map]]</span>.
</p>

<strong>Các ghi chú mới nhất</strong>

<ul>
  {% assign recent_notes = site.notes | sort: "last_modified_at_timestamp" | reverse %}
  {% for note in recent_notes limit: 10 %}
    <li>
      {{ note.last_modified_at | date: "%Y-%m-%d" }} — <a class="internal-link" href="{{ note.url }}">{{ note.title }}</a>
    </li>
  {% endfor %}
</ul>

<style>
  .wrapper {
    max-width: 46em;
  }
</style>
