# xmin2

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

To preview this theme locally, run:

```bash
git clone https://github.com/thomasheller/xmin2
cd xmin2/exampleSite
hugo serve -t ../..
```

