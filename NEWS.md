# measureR 0.0.2

* Enhanced the Content Validity module with several methodological improvements:
  - Integrated official critical values of Aiken’s V (Aiken, 1985) for rating scales ranging from 3 to 7 categories.
  - Implemented scale-based Aiken’s V computation using user-selected theoretical rating ranges instead of observed minimum–maximum values.
  - Added dynamic selection of the item ID column for uploaded datasets.
  - Improved visual decision indicators for CVR, Aiken’s V, and CVI tables (color-coded validity status).
  - Disabled inferential evaluation of Aiken’s V for dichotomous (0/1) data.
* Improved data validation and robustness for uploaded content validity datasets.
* Minor UI refinements in Content Validity and CTT modules.

# measureR 0.0.1
* Initial release to CRAN.
* Includes a full Shiny-based graphical user interface for:
  - Content Validity (CV)
  - Exploratory Factor Analysis (EFA)
  - Confirmatory Factor Analysis (CFA)
  - Classical Test Theory (IRT)
  - Item Response Theory (IRT)
* Includes interactive visualizations, downloadable outputs, and built-in example datasets.
* Provides `run_measureR()` as the main entry point for launching the application.
