# 20期科学部活動記録
## ブログ一覧
<ul>
  {% for post in site.posts %}
    <li><a href="/blog{{ post.url }}"> {{ post.title }}</a></li>
  {% endfor %}
</ul>

### Markdownヘルパー

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

