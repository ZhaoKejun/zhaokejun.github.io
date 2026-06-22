# Zhao Kejun's website

Source for [zhaokejun.github.io](https://zhaokejun.github.io), built with Jekyll from the [AcadHomepage](https://github.com/RayeRen/acad-homepage.github.io) template.

## Publish with GitHub Pages

1. Commit and push this repository to `ZhaoKejun/zhaokejun.github.io` on the `main` branch.
2. In the repository on GitHub, open **Settings → Pages**.
3. Set **Source** to **Deploy from a branch**, then select `main` and `/(root)`.
4. After GitHub finishes building, the site will be available at [https://zhaokejun.github.io](https://zhaokejun.github.io).

## Edit the site

- Update personal details and links in [`_config.yml`](./_config.yml).
- Edit the homepage content in [`_pages/about.md`](./_pages/about.md).
- Change the header navigation in [`_data/navigation.yml`](./_data/navigation.yml).

To preview locally, install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Open `http://127.0.0.1:4000` in a browser.

The optional Google Scholar workflow stays inactive unless a `GOOGLE_SCHOLAR_ID` repository secret is configured.
