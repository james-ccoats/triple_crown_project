# Triple Crown Sports Data Scraping Project.

## Software and platform

```         
-   R version 4.4.1 (2024-06-14), running under: macOS 15.7.3

-   Attatched base packages: stats, graphics, grDevices, utils, datasets, methods, base

-   Other attatched packages: janitor_2.2.1, lubridate_1.9.4, forcats_1.0.0, dplyr_1.1.4, readr_2.1.5, tidyr_1.3.1, ggplot2_4.0.0, tidyverse_2.0.0 stringr_1.5.1, jsonlite_2.0.0, tibble_3.3.0, purrr_1.1.0, rvest_1.0.5, httr2_1.1.0    
```

## Template organization and function (based on TIER Protocol 4.0)

-   project/

    -   README.md

    -   data/

        -   imported_data/

            -   metadata/

                -   source.txt

                -   codebook.txt

        -   cleaned_data/

            -   metadata/

                -   source.txt

                -   codebook.txt

    -   scripts/

        -   import.qmd

        -   cleaning.qmd

    -   output/

        -   beverly_bandits_coaches_info.csv

## Reproduction

-   Begin by loading in all required packages. Packages which have not been installed before on a device will need to be. Use `install.packages('package_name')` to install a package.
-   In **import.qmd**, run the first code block to create and use the function to scrape the team names from the Beverly Bandits website.
-   Moving into **cleaning.qmd**, run the first code block in order to create a tibble and organize the scraped data.
-   Next, run the code block below, using the organized data to create scrapable links for coach information.
-   Move back into **import.qmd**. 
