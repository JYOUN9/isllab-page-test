---
title: News
date: 2024-01-01
type: landing

design:
  spacing: "6rem"

sections:
  - block: markdown
    id: news
    content:
      title: News
      text: |
        <p style="margin-bottom: 3rem;">Lab announcements, paper acceptances, Projects, awards, and events.</p>

        {{< news-cards >}}
    design:
      spacing:
        padding: ["2rem", 0, "2rem", 0]
      css_style: "max-width: 100% !important; width: 100% !important;"
      container: false
---

