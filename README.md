# LJT-Homepage

Personal academic homepage of **Junteng Liu**, built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template (forked from [academicpages/academicpages.github.io](https://github.com/academicpages/academicpages.github.io)).

## Site contents

- **About** (`_pages/about.md`): personal details, academic background, research experience, publications, skills, honors, and contact information.
- **Publications** (`_pages/publications.html` and `_publications/`): the publication list.

## Site URL

When GitHub Pages is enabled for this repository, the site is served at:
`https://spallaselvylt934649.github.io/LJT-Homepage/`

## Publishing the site (one-time setup)

1. In this repository, go to **Settings > Pages**.
2. Under **Build and deployment**, set **Source** to **GitHub Actions**.
3. The workflow in `.github/workflows/jekyll.yml` builds and deploys the site on pushes to `master` (it can also be run manually from the Actions tab).

The workflow in `.github/workflows/build-validation.yml` can be run manually to verify that the site builds without deploying it.
