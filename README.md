# Chicago7 for Micro.blog

A Micro.blog-ready adaptation of the Chicago7 Hugo theme. It preserves the original System 7-inspired look and Chicago typeface, with the SCSS compiled into `static/css/main.css`; publishing does not require Sass, Hugo Pipes, Hugo Modules, or JavaScript.

## Install on Micro.blog

1. In Micro.blog, open **Posts → Design → Edit Custom Themes → New Theme**.
2. Import this theme from its GitHub repository, or upload the included ZIP if your theme editor offers file upload. The ZIP has the theme files at its root.
3. Save the theme, then select it on **Posts → Design**. Preview the result before publishing.
4. Set your blog title and optional logo/social links in your Micro.blog settings. The theme reads standard Hugo parameters such as `logo`, `author`, and `social`.

Micro.blog's documented import flow clones a GitHub repository. If ZIP upload is not available in your account, unzip this package, put the files in a GitHub repository, and import that repository as a custom theme.

## Navigation

The header displays Hugo's standard `main` menu. Add menu entries in your Hugo site configuration (or configure equivalent navigation in your Micro.blog theme settings), for example:

```toml
[[menu.main]]
name = "Home"
url = "/"
weight = 1

[[menu.main]]
name = "About"
url = "/about/"
weight = 2

[[menu.main]]
name = "Categories"
url = "/categories/"
weight = 3
```

## Included features

- Micro.blog posts on the homepage, including posts without titles
- Standard Hugo pages and main navigation
- RSS alternate link, using the site's RSS output format
- Categories and tags, when enabled by the site's taxonomies
- Date archive, pagination, social links, and optional logo
- Light and dark color schemes from the original design

The theme was built and checked locally with Hugo 0.91, 0.117, and 0.158. Choose the Hugo version available in your Micro.blog Design settings; the theme uses classic Hugo layouts and static assets, and does not require Hugo Pipes or Sass.

## Credits and license

Adapted from [Chicago7](https://github.com/akopdev/hugo-theme-chicago7) by akopdev. The original theme is MIT-licensed; see `LICENSE`.
