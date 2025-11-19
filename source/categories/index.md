---
title 分类
date 2025-11-19
---

<ul>
  {{ range .Site.Taxonomies.categories }}
    <li><a href="{{ .Page.Permalink }}">{{ .Page.Title }}</a></li>
  {{ end }}
</ul>

