# Automatically set working directory to exercises folder when RStudio starts
# This only runs if we're in the base directory (to avoid issues in subdirectories)

if (getwd() == "/home/rstudio") {
  setwd("/home/rstudio/exercises")
  cat("Working directory set to: exercises/\n")
  cat("Available exercises:\n")
  cat(paste("  -", list.files(pattern = "\\.R$|\\.Rmd$")), sep = "\n")
  cat("\n")
}
