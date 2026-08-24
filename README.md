# Ziyi Liang — Academic Website

Source for [ziyiliang.github.io](https://ziyiliang.github.io), built with Jekyll and the al-folio runtime gems.

## Repository structure

- **_pages/about.md** — homepage and responsive profile layout
- **_pages/publications.md** — publications, preprints, and working papers
- **_pages/teaching.md** — teaching experience
- **_pages/repositories.md** — research software
- **_pages/404.md** — not-found page
- **assets/img/prof_pic.jpg** — profile portrait
- **assets/cv/Ziyi_Liang_CV.tex** — editable CV source
- **assets/pdf/Ziyi_Liang_CV.pdf** — CV linked from the website
- **_sass/_themes.scss** — site colors and theme-switch styling
- **_config.yml** — site metadata and Jekyll configuration

## Local preview

    bundle install
    bundle exec jekyll serve

Then open <http://127.0.0.1:4000/>.

## Updating the site

Edit the relevant file in **_pages**, then refresh the local preview. To update the CV, compile **assets/cv/Ziyi_Liang_CV.tex** and replace **assets/pdf/Ziyi_Liang_CV.pdf** with the new PDF.

Pushing to **main** runs the GitHub Pages deployment workflow.