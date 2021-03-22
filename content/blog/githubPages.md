+++
title = "Github Pages"
date = 2021-03-22 11:00:00
+++
# ***9/8/1942***
---

Github allows you to have your own site [pages.github](https://pages.github.com/)

---

Currently I'm using a markdown file to write the page then I can convert it to html with [python-markdown](https://python-markdown.github.io/)

`markdown_py  index.md 1>index.html`

---

The nice thing is the ability to add html/css code directly inside the markdown file and it will still work correctly. (useful for css styles)

---

Checkout this page source [sigmaSd.github.io](https://github.com/sigmaSd/sigmaSd.github.io)

---

*Edit1*: Now that I use multiple pages, the new command is (*fish sell*):

```fish
for i in (ls | rg '\.md')
	set h (echo $i | sd '..$' 'html'); markdown_py $i 1>$h;
end
```

---

*Edit2*: The up-to-date command is located here [compile.fish](../compile.fish)
