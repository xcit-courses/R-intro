# R Course Exercises

Welcome to the R programming course exercises!

## Getting Started with Binder

Click the button below to launch an interactive RStudio environment in your browser:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/xcit-courses/R-intro/main?urlpath=rstudio)

**When RStudio opens, your working directory will automatically be set to the `exercises/` folder!**

This will open RStudio in your browser with all the necessary R packages pre-installed. 


### How RStudio Opens

**Important**: RStudio always opens at the repository root in Binder. However:
- Your **working directory is automatically set to `exercises/`** via the `.Rprofile` file
- When you run R commands like `getwd()`, you'll see you're in the exercises folder
- File operations (reading/writing) default to the exercises folder
- You can navigate the full repository in the Files panel, but your R session works in exercises/

The `filepath` parameter only works with Jupyter notebooks, not RStudio.

### Important Notes
- **Sessions are temporary** - Download your work before closing the browser
- **Inactivity timeout** - Sessions close after ~10 minutes of inactivity  
- **No persistent storage** - Everything resets when you close the tab
- **Free to use** - mybinder.org is a free service
- **No account needed** - Just click and start coding

