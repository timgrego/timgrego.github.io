# Timothy Gregory

Personal site, published at [timgrego.github.io](https://timgrego.github.io).

Built with [Jekyll](https://jekyllrb.com/) on [Academic Pages](https://github.com/academicpages/academicpages.github.io), a fork of [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes). Theme bugs belong on those projects. This repository is the site itself.

## Content

| What | Where |
| --- | --- |
| Home page | `_pages/about.md` |
| Research page | `_pages/research.md` |
| Header links | `_data/navigation.yml` |
| Name, sidebar, and site URL | `_config.yml` |
| CV file | `files/` (linked from the sidebar) |

`_config.yml` is not reloaded by a running server. Restart Jekyll after editing it.

`markdown_generator/` can build publication or talk pages from a spreadsheet if those collections are added later. It is not part of the published site.

## Preview locally

Ruby 3.2 and Bundler:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

The site is at [http://localhost:4000](http://localhost:4000).

With Docker:

```bash
docker compose up
```

Open the same local URL. In VS Code or Cursor, **Dev Containers: Reopen in Container** uses `.devcontainer/` and serves the site the same way.
