# License Link in Footer Showcase

This repo is used in a stackOverflow question:

## How to correctly include a LICENSE file in Quarto book footer with relative link that works on GitHub Pages?

Solution should:
- Work both when rendering locally (`quarto render`) and deploying to GitHub Pages (`quarto publish`)
- not rely on an external URL

## Example github page

link to this repos GitHub Page: https://julxi.github.io/license_in_github_page/

- **Left Footer Link:**  
  `href: LICENSE`:
    - Works locally with `quarto render`  
    - Fails on GitHub Pages

- **Right Footer Link:**  
  - `href: https://github.com/julxi/license_in_github_page/blob/main/LICENSE`  
    - Works on GitHub Pages
    - Uses external URL