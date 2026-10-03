# EIPI Lab Website

Website for the Evolutionary Intelligence for Science and Engineering research group at South China University of Technology, led by Prof. Jinghui Zhong.

- Website: https://scut-eipi.github.io/
- GitHub organization: https://github.com/SCUT-EIPI
- Organization profile: https://github.com/SCUT-EIPI/.github/blob/main/profile/README.md

## Content

The main pages are in `_pages/`: `about.md` (home), `publications.md`, `research.md`, `awards.md`, `members.md`, and `contact.md`. Site identity and navigation are configured in `_config.yml` and `_data/navigation.yml`.

See [content sources](docs/content-sources.md) for the factual audit and publication metadata. Keep the GitHub organization profile consistent when changing the introduction, research directions, or selected publications. Unused Academic Pages demo pages are excluded from the published site.

## Local Preview

Install Ruby, Bundler, and Node.js, then run:

```sh
bundle install
bundle exec jekyll serve
```

## Deployment

Pushes to `master` trigger `.github/workflows/deploy.yml`. The workflow builds the site with Jekyll and deploys it to GitHub Pages. Check the build and deployment with:

```sh
gh run list --workflow deploy.yml
gh run view <run-id>
```

The website uses the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll theme, based on Minimal Mistakes. See [LICENSE](LICENSE) for licensing information.
