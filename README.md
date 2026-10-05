# R-intro

Website for course "Introduction to programming in R"

## 🚀 Try R in Your Browser

Launch an interactive RStudio environment with all course materials:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/xcit-courses/R-intro/main?urlpath=rstudio)

No installation required! Perfect for students who want to complete exercises without setting up R locally.

## 📚 Course Website

Visit the course website: https://xcit-courses.github.io/R-intro/

## 📝 Exercises

Interactive exercises are available in the `exercises/` folder. See [exercises/README.md](exercises/README.md) for details on using Binder.

## Repository Structure

- `about/` - Course information (overview, syllabus, schedule)
- `chapters/` - Course content organized by chapter
- `exercises/` - Interactive R exercises for students
- `assets/` - Styling, images, and themes
- `_site/` - Generated website (published to GitHub Pages)

## For Instructors

### Building the Website

```bash
quarto render
```

### Publishing to GitHub Pages

```bash
quarto publish gh-pages --no-prompt
```

### Updating the Binder Environment

Edit these files to customize the R environment for students:

- `runtime.txt` - Specifies R version and CRAN snapshot date
- `install.R` - List of R packages to pre-install

After committing changes, Binder will automatically rebuild the environment on next launch.

## Use of AI Tools

This project uses [Claude Code](https://claude.com/claude-code), an AI coding assistant, to help prepare and maintain course materials. All content has been reviewed by a human before being committed.
