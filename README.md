# Personal Website

Professional portfolio website built with the R Markdown website framework and deployed with GitHub Pages.

## Website Structure

- `index.Rmd`: Home page
- `about.Rmd`: About page
- `projects.Rmd`: Projects portfolio
- `pets.Rmd`: Personal page
- `_site.yml`: Site navigation and output configuration
- `styles.css`: Custom CSS styling
- `files/Resume.pdf`: Resume link target in navbar
- `files/poster.pdf`: Thesis poster linked on project page
- `docs/`: Rendered website output for GitHub Pages

## Run Locally

From the `Personal_website` directory:

```r
rmarkdown::render_site()
```

Or from terminal:

```bash
Rscript -e "setwd('Personal_website'); rmarkdown::render_site()"
``
