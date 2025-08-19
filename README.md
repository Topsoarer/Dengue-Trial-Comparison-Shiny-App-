# Dengue Clinical Trial Comparison Simulator

A Shiny application to simulate and compare clinical trial designs for Dengue, focusing on antibody-based vs. infection-based endpoints.

**[➡️ View the Live Application Here](https://peiyuliu.shinyapps.io/anpp-trial-comparison/)**

---

## Description

This application is designed to help researchers and epidemiologists explore and compare the efficiency of different clinical trial designs. Users can adjust a range of antibody-based and infection-based parameters—such as mosquito biting rates, antibody dynamics, and intervention effectiveness—to simulate trial outcomes and estimate required sample sizes.

The tool provides a dynamic interface to visualize the impact of these parameters on key metrics, allowing for a more informed decision-making process when planning costly and complex clinical trials.

## Features

- **Parametric Simulation**: Flexibly adjust over 15 key parameters to customize simulation scenarios.
- **Dual Trial Models**: Simultaneously simulate both MSP antibody-based trials and infection-based trials.
- **Real-time Visualization**: Dynamically generates a variety of plots, including biting rates, antibody titer trajectories, infection hazards, and sample size requirements.
- **Scenario Recording**: Save, view, and compare multiple parameter configurations and their resulting outcomes in a clear, interactive table.

## How to Run Locally

1.  Ensure you have R and RStudio installed.
2.  Clone this repository to your local machine.
3.  Install the required packages by running the following command in the R console:
    ```R
    install.packages(c('shiny', 'shinydashboard', 'ggplot2', 'dplyr', 'pwr', 'DT'))
    ```
4.  Open the `app.R` file in RStudio.
5.  Click the "Run App" button.

## File Structure

-   `app.R`: The core script containing all UI (User Interface) and Server (Server Logic) for the Shiny application.
-   `www/`: A special directory for web assets.
    -   `model_description.html`: (Optional) A detailed mathematical description of the underlying model, generated from R Markdown.

## Author

-   **Peiyu Liu**
-   Department of Biostatistics, University of Florida
-   Contact: <pyliu0620@outlook.com>

## License

This project is licensed under the **MIT License**. See the `LICENSE` file for details.
