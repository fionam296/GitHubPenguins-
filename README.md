

A reproducible analysis of morphological measurements from the Palmer Penguins dataset, examining variation in body dimensions across penguin species in the Palmer Archipelago, Antarctica.

<img src="https://allisonhorst.github.io/palmerpenguins/reference/figures/lter_penguins.png" width=50%>
<img src="https://allisonhorst.github.io/palmerpenguins/reference/figures/lter_penguins.png" width=40%>
<img src="https://allisonhorst.github.io/palmerpenguins/reference/figures/lter_penguins.png" width=30%>
<img src="https://allisonhorst.github.io/palmerpenguins/reference/figures/lter_penguins.png" width=20%>
<img src="https://allisonhorst.github.io/palmerpenguins/reference/figures/lter_penguins.png" width=10%>



This project uses data collected by [Dr Kristen Gorman](https://www.uaf.edu/cfos/people/faculty/detail/kristen-gorman.php) at the [Palmer Station Long Term Ecological Research](https://pallter.marine.rutgers.edu/) site in Antarctica.

**Species studied:** Gentoo, Chinstrap, and Adelie penguins. 

**Research location:** 3 islands in the Palmer Archipelago, Antactica : Torgersen, Biscoe, Dream

**Sample size:** More than 10. 

**Years of data collection:** [TODO: What years were data collected? Hint: check the `year` column in the CSV]



The dataset includes the following morphological measurements:

| Variable | Range |
|----------|-------------|
| `bill_length_mm` | [TODO: Include range] |
| `bill_depth_mm` | [TODO: Include range] |
| `flipper_length_mm` | [TODO: Include range] |
| `body_mass_g` | [TODO: Include range] |



The R script `run_analysis_SOLUTIONS.R` performs the following steps:

1. **Data cleaning** -- [TODO: What does the cleaning step do to handle missing values? Hint: look at section 3 and 4 of the script]
2. **Exploratory boxplots** -- [TODO: Which variable is plotted against species in the first boxplot? Hint: look at section 5]
3. **Cluster analysis** -- [TODO: Which two measurements are used to show how species cluster? Hint: look at section 7]
4. **Regression analysis** -- [TODO: What relationship does the regression plot examine? Hint: look at section 7]



The analysis generates a multi-panel figure combining four plots:

- **Top left:** [TODO: What does this plot show?]
- **Top right:** [TODO: What does this plot show?]
- **Bottom left:** [TODO: What does this plot show?]
- **Bottom right:** [TODO: What does this plot show?]



```
penguin-analysis/
├── README.md              ← You are here!
├── .gitignore             ← [TODO: What does a .gitignore file do?]
├── data/
│   └── penguins_raw.csv   ← [TODO: Describe this file in one sentence]
├── functions/
│   ├── plotting_functions.R  ← [TODO: Describe what this file contains]
│   └── saving_functions.R    ← [TODO: Describe what this file contains]
└── run_analysis_SOLUTIONS.R  ← [TODO: Describe what this file does]
```



1. Open `run_analysis_SOLUTIONS.R` in RStudio
2. Install required packages: `tidyverse`, `janitor`, `palmerpenguins`, `patchwork`
3. Run the script from top to bottom
4. Outputs are saved to the `figures/` folder



Horst AM, Hill AP, Gorman KB (2020). *palmerpenguins: Palmer Archipelago (Antarctica) penguin data.* R package version 0.1.0. https://allisonhorst.github.io/palmerpenguins/



 By Ella

