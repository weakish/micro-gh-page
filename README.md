# Micro GitHub Page Template

## Features

0. No JavaScript.
1. Minimalistic 404 page.
2. Clean urls (`/page/` instead of `/page.html`).
3. SEO sitemap.
4. Use `/commits/master.atom` of source repository for RSS.
5. `application/git+http` rel tag.
6. Use [Primer] Jekyll theme, which is the default theme for GitHub Pages

[Primer]: https://github.com/pages-themes/primer

## Use

1. Create a new repository at GitHub based on template [weakish/micro-gh-page].

2. Edit `_config.yml`, for example:

    ```
    url: your-username.github.io
    title: your-site-title
    repo: your-username/your-username.github.io
    ```

3. (optional) Add a `favicon.ico` file.

4. (optional) Add a `CNAME` file to use your own domain.

5. Commit changes and push.

[weakish/micro-gh-page]: https://github.com/weakish/micro-gh-page

## Preview

Install the requirements:

```sh
bundle install
```

Preview locally:

```sh
bundle exec jekyll serve
```

## Examples

- [this site itself](https://mmap.page/micro-gh-page/)
- [mmap.page](https://mmap.page)
- [add your site](https://github.com/weakish/micro-gh-page/pulls)