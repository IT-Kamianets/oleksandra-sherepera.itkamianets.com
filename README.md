# Oleksandra Sherepera — personal website

A bilingual, one-page portfolio for **Oleksandra Sherepera / Олександра Шерепера**. The website itself is three files: `index.html`, `404.html`, and `CNAME`. CSS and JavaScript are included directly in `index.html`; there is no framework, package install, or build step.

## Preview locally

Open `index.html` in a browser. The language switch and mobile menu run directly in the page.

## Update content

- Edit the page structure and Ukrainian/English text in `index.html`.
- Edit interests, concept descriptions, translations, styles, and interactions in `index.html`.
- Add approved contact links when they are provided; the current site intentionally avoids false or placeholder links.
- A CV PDF is not included yet. Add a verified PDF at the site root once the CV details have been reviewed, then add its download link to the CV section in `index.html`.
- Add notes to the Notes section only after they are approved for publication.

## GitHub Pages

The workflow in `.github/workflows/deploy.yml` publishes the static site files after each push to `main`. The root `CNAME` file sets `oleksandra-sherepera.itkamianets.com`; the root `404.html` is the custom not-found page. GitHub Pages must be enabled with **GitHub Actions** as the deployment source, and DNS for the custom domain must point to GitHub Pages.

## Content integrity

The profile uses only details stated in the project brief. The three visual portfolio pieces are clearly presented as concepts created for this portfolio, not as commissioned client work. Education, employment history, public contact links, and other CV details remain unpublished until confirmed.
