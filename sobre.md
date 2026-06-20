---
layout: default
title: "sobre"
permalink: /sobre/
---

<article class="post">
  <header class="post-header">
    <h1>sobre</h1>
  </header>
  <div class="prose">
    <p>oiê, eu sou <strong>{{ site.author }}</strong>. Aqui eu escrevo
    publicações, posto tirinhas e faço reviews de filmes, livros e álbuns.</p>

    <p>você pode me encontrar no
    {%- if site.social.github != "" %} <a href="https://github.com/{{ site.social.github }}">GitHub</a>{% endif -%}.
    para acompanhar, assine o <a href="{{ '/feed.xml' | relative_url }}">RSS</a>.</p>
  </div>
</article>
