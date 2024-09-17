## `_config.yml` Left sidebar

  ```yaml
# Basic Information 
title: Name
position: Ph.D. Student
affiliation: affiliation:
email: example (at) example.edu

# Search Engine Optimization (SEO)
# The following information is used to improve the website traffic from search engines, e.g., Google.
keywords: minimal light # need not change
description: The Minimal Light is a simple and elegant jekyll theme for academic personal homepage. # need not change
canonical: https://minimal-light-theme.yliu.me/ # need not change

# Links 
# If don't need one of them, you may delete the corresponding line.
google_scholar: https://scholar.google.com/
research_gate: https://www.researchgate.net/
#cv_link: files/Curriculum_Vitae.pdf # put CV here `assets/files/Curriculum_Vitae.pdf`
#github_link: https://github.com/
#linkedin: https://www.linkedin.com/
#twitter: https://twitter.com/

# Images (e.g., your profile picture and your website's favicon) 
# "favicon" and "favicon_dark" are used for the light and dark modes, respectively. 
avatar: ./assets/img/avatar.png # profile picture
favicon: ./assets/img/favicon.png # need not change
favicon_dark: ./assets/img/favicon-dark.png # need not change

# Footnote
# You may use the option to disable the footnote, "Powered by Jekyll and Minimal Light theme."
enable_footnote: true # need not change

# Auto Dark Mode
# You may use the option to disable the automatic dark theme
auto_dark_mode: false # need not change

# Font
# You can use this option to choose between Serif or Sans Serif fonts.
font: "Serif" # or "Sans Serif" # need not change

# The following files will be removed from the generated website.
# need not change
exclude:
  - Gemfile
  - Gemfile.lock
  - README.md
  - README_zh_Hans.md
  - README_zh_Hant.md
  - README_de.md
  - LICENSE
  - minimal-light.gemspec
  - html_source_file/
  ```

## `index.md` Right contents

Change contents based on the style [minimal-light/index.md](https://github.com/yaoyao-liu/minimal-light/blob/main/index.md?plain=1).

### `About Me`

### `Research Interests`

### `News`

### `Contact`

### `Publication`  `{% include_relative _includes/publications.md %}`

#### `_includes/publications.md`

Only change the following:

- Selected Publications / Publications
- Link: Google Scholar, ORCID, Research Gate, ......

```html
<h2 id="publications" style="margin: 2px 0px -15px;">Selected Publications <temp style="font-size:15px;">[</temp><a href="https://scholar.google.com/citations?hl=en&user=AzL39ZoAAAAJ&view_op=list_works" target="_blank" style="font-size:15px;">Google Scholar</a><temp style="font-size:15px;">]</temp><temp style="font-size:15px;">[</temp><a href="https://www.researchgate.net/profile/Dong-Chen-68" target="_blank" style="font-size:15px;">Research Gate</a><temp style="font-size:15px;">]</temp></h2>
```

#### `_data/publications.yml`

```yaml
title: article title [Required]
author: authors, use <strong>your name</strong> to highlight your name [Required]
image: image in the left, for example, name as `teaser_example_2.png`, and put in `assets/img` , then write here, `./assets/img/teaser_example_2.png`  [optional]
conference_short: journal abbreviation/full name, it will be displayed in the upper left corner of the image [optional]
conference: journal full name, published year [Required]
pdf: pdf link, ① `www.google.com`; ② if `article.pdf` in `assets/files`, here `/assets/files/article.pdf` [optional]
code: code link [optional]
page: project link [optional]
bibtex: bibtex link [optional]
notes: article type, such as Oral Presentation, Research Article, Conference Article, ...... [optional]
others: anything, such as brief introduction of article [optional]
```

### `Service`  `{% include_relative _includes/services.md %}`

#### `_includes/services.md`

If do not need this session, just remove `{% include_relative _includes/services.md %}` at the `index.md`, or remove the content in`_includes/services.md`.
