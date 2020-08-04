# Impact Labs Website

## Setup

1.  Install [bundler](https://bundler.io/)
2.  Run `bundle install`
3.  Run `jekyll serve`

# Layout
```
.
├── _config.yml
├── _data
├── _includes -> Page elements that persist across the site (navbar, footer, head), inserted into main.html in /layouts
├── _layouts -> All pages are rendered through here
├── _sass -> main.scss (edit this and not /asset/scss/styles.scss)
├── _site -> Auto generated by Jekyll (ignore)
├── assets -> Static assets (images, CSS and JS files)
└── pages -> Body of each page, to be inserted in main.html in /layouts
```

## Acknowledgements

0.  [Blackrock Digital LLC Template](https://github.com/BlackrockDigital/startbootstrap-scrolling-nav/blob/gh-pages/LICENSE)
