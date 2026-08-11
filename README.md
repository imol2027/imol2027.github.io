# Beautiful Jekyll — Run locally

This repository is a Jekyll site (Beautiful Jekyll theme). Follow the steps below to run it locally.

Prerequisites
- Ruby (recommended 2.7+)
- Bundler (`gem install bundler`)

Install dependencies

```bash
bundle install
```

Serve locally (live reload)

```bash
bundle exec jekyll serve --livereload
```

Open your browser to `http://localhost:4000` (default).

Build only (output in `_site`)

```bash
bundle exec jekyll build
```

Notes
- If `bundle install` fails on Linux, ensure OS build tools and dev headers (e.g. `build-essential`, `libssl-dev`, `libreadline-dev`, `zlib1g-dev`) are installed.
- Use `--host 0.0.0.0` to serve to the network: `bundle exec jekyll serve --livereload --host 0.0.0.0`.

If you want, I can also add a tiny Docker setup or verify the site builds here.
