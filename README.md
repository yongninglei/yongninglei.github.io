# yongninglei.github.io

Personal academic website of Yongning Lei, live at <https://yongninglei.github.io>.

Built on the [Academic Pages](https://github.com/academicpages/academicpages.github.io)
Jekyll template and deployed by `.github/workflows/jekyll.yml` on every push to `master`.

## Where things live

| Content | Location |
|---|---|
| Sidebar profile, site metadata | `_config.yml` (`author:` block) |
| Header menu | `_data/navigation.yml` |
| Home page | `_pages/about.md` |
| Resume page (tabs) | `_pages/cv.md` |
| Publications, talks, posters | `_includes/publications.md` (shown on Publications and the Resume tab) |
| Page layout & styling | `_layouts/clean.html`, `assets/css/clean.css` |
| Blog posts | `_posts/YYYY-MM-DD-title.md` (start from `_drafts/example-post.md`) |
| Software / projects | `_pages/software.md` |
| Profile photo | `images/profile.png` |

## Local preview

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Pull template updates with `git fetch upstream && git merge upstream/master`.
