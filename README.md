# **Comprehensive R for Data Analysis Tutorial**

Welcome\! This repository contains a series of tutorials designed to provide a comprehensive guide to using R for common data analysis tasks, based on the Tidyverse philosophy. Whether you're refreshing your knowledge or learning new concepts, these guides aim to be a practical and accessible resource.

## **About This Tutorial Series**

This collection covers fundamental R concepts, data manipulation, visualization, reporting, and essential helper packages, drawing heavily on the powerful tools within the Tidyverse ecosystem. **The Tidyverse is a collection of R packages (like dplyr, ggplot2, tidyr, readr) designed for data science that share an underlying design philosophy, grammar, and data structures.** The tutorials are designed to be hands-on, with clear explanations and executable code examples.

## **Structure**

The tutorials are broken down into logical modules, each in its own R Markdown (.Rmd) file:

1. [**01-R\_Basics.Rmd**](https://www.google.com/search?q=01-R_Basics.Rmd)  
   * Atomic Data Types (logical, integer, double, character, complex, raw)  
   * Core Data Structures (Vectors, Lists, Data Frames, Matrices)  
   * Inspection Functions (typeof, length, str, dim)  
2. [**02-Operators\_Conditionals\_Loops.Rmd**](https://www.google.com/search?q=02-Operators_Conditionals_Loops.Rmd)  
   * Arithmetic, Relational, Logical (& vs &&), Assignment, Misc. Operators  
   * The Pipe Operator (%\>%)  
   * Conditional Statements (if/else if/else, ifelse())  
   * Loops (for, while)  
3. [**03-Functions\_in\_R.Rmd**](https://www.google.com/search?q=03-Functions_in_R.Rmd)  
   * Defining Functions  
   * Arguments (Positional, Keyword, Default)  
   * Return Values  
   * Variable Scope  
4. [**04-Import\_Export\_Files.Rmd**](https://www.google.com/search?q=04-Import_Export_Files.Rmd)  
   * Loading Built-in Data (data())  
   * Importing CSVs (readr::read\_csv) and Excel Files (readxl::read\_excel)  
   * Saving Data Frames (CSV, RDS, XLSX)  
   * File System Interaction (file.create, file.copy, unlink, dir.create)  
   * Reproducible Paths (here::here)  
5. [**05-Data\_Wrangling\_dplyr.Rmd**](https://www.google.com/search?q=05-Data_Wrangling_dplyr.Rmd)  
   * Core dplyr Verbs (select, filter, arrange with desc, mutate, rename)  
   * Summarizing Data (group\_by, summarize)  
6. [**06-Data\_Reshaping\_tidyr.Rmd**](https://www.google.com/search?q=06-Data_Reshaping_tidyr.Rmd)  
   * Tidy Data Principles  
   * Making Data Longer (pivot\_longer)  
   * Making Data Wider (pivot\_wider)  
7. [**07-Data\_Visualization\_ggplot2.Rmd**](https://www.google.com/search?q=07-Data_Visualization_ggplot2.Rmd)  
   * The Grammar of Graphics (Layers: ggplot, geom\_\*, Aesthetics: aes)  
   * Faceting (facet\_wrap, facet\_grid)  
   * Labels and Annotations (labs, annotate)  
   * Adding Trend Lines (geom\_smooth)  
   * Saving Plots (ggsave, Graphics Devices)  
8. [**08-R\_Markdown.Rmd**](https://www.google.com/search?q=08-R_Markdown.Rmd)  
   * Basic Syntax (Markdown \+ R Code Chunks)  
   * YAML Header (Metadata, Output Formats)  
   * Knitting Process  
   * Templates  
   * Automated/Parameterized Reports (rmarkdown::render)  
9. [**09-Helper\_Packages.Rmd**](https://www.google.com/search?q=09-Helper_Packages.Rmd)  
   * Quick Data Summaries (skimr::skim)  
   * Data Cleaning Helpers (janitor::clean\_names, janitor::tabyl)  
10. [**10-Addressing\_Bias.Rmd**](https://www.google.com/search?q=10-Addressing_Bias.Rmd)  
    * Understanding Data Bias  
    * R Techniques (Randomization with sample, Oversampling with SMOTE, Undersampling with NearMiss)

## **How to Use**

1. **Clone the Repository:** Get a local copy of all the files.  
2. **Open in RStudio:** RStudio provides the best experience for working with .Rmd files.  
3. **Install Packages:** Make sure you have the tidyverse and other mentioned packages (here, skimr, janitor, palmerpenguins, SimDesign, readxl, writexl, etc.) installed. You can usually install them by running install.packages("package\_name") in the R console.  
4. **Run the Code:** Execute the R code chunks within each .Rmd file to see the results and experiment.  
5. **Knit the Documents:** Use the "Knit" button in RStudio to generate HTML or PDF versions of the tutorials.

## **Contributing**

Suggestions and improvements are welcome\! Please feel free to open an issue or submit a pull request.

*This tutorial series was generated based on collaborative discussions.*