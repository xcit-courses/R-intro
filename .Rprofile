# Automatically set working directory to exercises folder when RStudio starts
# This runs when RStudio is launched in Binder

.First <- function() {
  # Get the current working directory
  current_dir <- getwd()
  
  # Check if exercises subdirectory exists from current location
  exercises_path <- file.path(current_dir, "exercises")
  
  if (dir.exists(exercises_path)) {
    # Set working directory to exercises
    setwd(exercises_path)
    cat("\n===========================================\n")
    cat("  Working directory set to: exercises/\n")
    cat("  Full path:", exercises_path, "\n")
    cat("===========================================\n\n")
    
    # List available exercise files
    exercise_files <- list.files(pattern = "\\.R$|\\.Rmd$")
    if (length(exercise_files) > 0) {
      cat("📝 Available exercises:\n")
      for (file in exercise_files) {
        cat("   •", file, "\n")
      }
      cat("\n💡 Open an exercise file from the Files panel to get started!\n")
    } else {
      cat("💡 Add your exercise files here to get started!\n")
    }
    cat("===========================================\n\n")
  } else {
    cat("\n⚠️  Warning: exercises directory not found at:", exercises_path, "\n")
    cat("   Current directory:", current_dir, "\n\n")
  }
}

