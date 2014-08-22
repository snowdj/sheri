---
layout: blog-category
permalink: /blog/programming/index.html
title: "Programming"
image:
    feature: silhouette_f.jpg
---

<div>
  {% for post in site.categories.programming %} 
    <li>
      <div class="deets" itemscope itemtype="http://schema.org/BlogPosting" itemprop="blogPost">
        <h1><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></h1>
        <p class="date"><time datetime="{{ post.date | date_to_xmlschema }}" itemprop="datePublished">{{ post.date | date: "%B %d, %Y" }}</time></p>
        <p class="">{% if post.description %}{{ post.description  | strip_html | strip_newlines | truncate: 120 }}{% else %}{{ post.content | strip_html | strip_newlines | truncate: 120 }}{% endif %}</p>
      </div>
    </li>
  {% endfor %}
</div>