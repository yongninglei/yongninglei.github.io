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
| CV page | `_pages/cv.md` |
| Publications | `_publications/*.md` — `category: manuscripts` or `inprep` |
| Talks & posters | `_talks/*.md` — `date` sorts, `date_display` is what is shown |
| Software / projects | `_portfolio/*.md` |
| Profile photo | `images/profile.png` |

## Local preview

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Pull template updates with `git fetch upstream && git merge upstream/master`.
