# R-intro

Website for course "Introduction to programming in R"

## 🚀 Try R in Your Browser

Launch an interactive RStudio environment with the lab exercises:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/xcit-courses/R-intro-labs/HEAD?urlpath=rstudio)

No installation required! Perfect for students who want to complete exercises without setting up R locally.

## 📚 Course Website

Visit the course website: https://xcit-courses.github.io/R-intro/

## 📝 Exercises

The lab exercises are in a separate repository: [xcit-courses/R-intro-labs](https://github.com/xcit-courses/R-intro-labs).

## Repository Structure

- `about/` - Course information (overview, syllabus, schedule)
- `chapters/` - Course content organized by chapter
- `assets/` - Styling, images, and themes
- `_site/` - Generated website (published to GitHub Pages)

## For Instructors

### Building the Website

```bash
quarto render
```

### Publishing to GitHub Pages

The site is published automatically: every push to `main` runs the workflow in `.github/workflows/publish.yml`, which renders the site and pushes it to the `gh-pages` branch. Progress is visible in the repository's Actions tab.

To publish manually instead:

```bash
quarto publish gh-pages --no-prompt
```

### Updating the Binder Environment

Binder launches the labs repository, so its R environment is set by `runtime.txt` and `install.R` in [R-intro-labs](https://github.com/xcit-courses/R-intro-labs).

## Use of AI Tools

This project uses [Claude Code](https://claude.com/claude-code), an AI coding assistant, to help prepare and maintain course materials. All content has been reviewed by a human before being committed.
