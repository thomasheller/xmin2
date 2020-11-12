---
title: Home
---

[<img src="https://simpleicons.org/icons/github.svg" style="max-width:15%;min-width:40px;float:right;" alt="Github repo" />](https://github.com/yihui/hugo-xmin)

# Hugo theme xmin2

xmin2 is a super minimalistic theme for [Hugo](https://gohugo.io/)
based on [XMin](https://github.com/yihui/hugo-xmin)
by [Yihui Xie](https://yihui.org/).

What's changed compared to the original XMin theme:

- only up to 5 recent posts on home page
- different `<hr>` style
- no special styling for article meta information
- ISO 8601 date format
- less prominent date styling

```bash
find . -not -path '*/exampleSite/*' \( -name '*.html' -o -name '*.css' \) | xargs wc -l
```

```
   9 ./layouts/partials/footer.html
  20 ./layouts/partials/header.html
   0 ./layouts/partials/head_custom.html
   0 ./layouts/partials/foot_custom.html
  10 ./layouts/_default/single.html
  20 ./layouts/_default/list.html
  13 ./layouts/_default/terms.html
   5 ./layouts/404.html
   8 ./static/css/fonts.css
  98 ./static/css/style.css
 183 total
```

Check out the
[custom header](https://github.com/thomasheller/xmin2/blob/master/exampleSite/layouts/partials/head_custom.html)
file to see how to enable LaTeX support.
Rendered MathJax looks like this:

When $a \ne 0$, there are two solutions to \(ax^2 + bx + c = 0\) and they are
$$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

Here comes the list of recent posts:

## Latest posts

