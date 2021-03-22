+++
title = "Github Pages (Part 2)"
date = 2021-03-22 17:00:00
+++
# ***9/8/1942***
---

Now this page uses [zola](https://www.getzola.org/)

---

It was pretty straight forward to set up, simply following [getting-started](https://www.getzola.org/documentation/getting-started/overview/)
should get you up and running.

---

The only thing I had to look for was formatting dates, here is how to do it:
`{{ page.date | date(format="%D ") }}`

---

