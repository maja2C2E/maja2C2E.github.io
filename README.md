# mbanicek.github.io

Personal academic website of **Maja Baniček Shaqfa** — powered by [Jekyll](https://jekyllrb.com/) and hosted on [GitHub Pages](https://pages.github.com/).

Built on the [Academic Pages](https://academicpages.github.io/) theme (a fork of [Minimal Mistakes](https://mmistakes.github.io/minimal-mistakes/)).

## Quick Start — How to Edit This Site

1. **`_config.yml`** — Your name, social links, employer, email, avatar
2. **`_pages/about.md`** — Homepage bio, research gallery, contact info
3. **`_pages/cv.md`** — Full CV (education, awards, work, teaching, software)
4. **`_publications/`** — Add one `.md` file per publication (see template)
5. **`_talks/`** — Add one `.md` file per talk (see template)
6. **`_teaching/`** — Add one `.md` file per course (see template)
7. **`_posts/`** — Blog posts
8. **`images/`** — Replace `Academic_CV_pic.png` with your photo

## Run locally

```bash
bundle install
bundle exec jekyll serve --host 0.0.0.0 --port 4000
```

Or with Docker:

```bash
docker compose up
```

Open `http://localhost:4000`.
