# Automatically set working directory to exercises folder when RStudio starts
# This runs when RStudio is launched in Binder

# Check if we're at the repository root (where .Rprofile is located)
# and if an 'exercises' directory exists
if (dir.exists("exercises") && file.exists(".Rprofile")) {
  # We're at the repo root, change to exercises
  setwd("exercises")
  cat("\n===========================================\n")
  cat("  Working directory set to: exercises/\n")
  cat("===========================================\n\n")
  
  # List available exercise files
  exercise_files <- list.files(pattern = "\\.R$|\\.Rmd$")
  if (length(exercise_files) > 0) {
    cat("📝 Available exercises:\n")
    for (file in exercise_files) {
      cat("   •", file, "\n")
    }
  }
  cat("\n💡 Open an exercise file from the Files panel to get started!\n")
  cat("===========================================\n\n")
}

