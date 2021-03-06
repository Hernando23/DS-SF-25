# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) DS-SF-25 | Final Project, Part 3: Exploratory Data Analysis

> **Submission:**
>
> - Please submit your project via GitHub and send a private message on Slack to **both** George **and** Ivan with a link to it.

---

## PROMPT

Exploratory data analysis is a crucial and informative step in the data process.  It helps confirm or deny your initial hypotheses and helps visualize the relationships among your data.  Your exploratory data analysis also informs the kinds of data transformations that you will need to optimize for machine learning models.

In this assignment, you will explore and visualize your initial analysis in order to effectively tell your data's story.  You will create a Jupyter notebook that explores your data mathematically, using a visualiation package such as `matplotlib`.

**Goal:** Confirm your data and create an exploratory data analysis notebook with statistical analysis and visualization.

---

### DELIVERABLES

#### Exploratory Analysis Writeup

- **Requirements:**
  - Review the dataset and project with your associate instructor during office hours.
  - Practice importing (potentially unformatted) data into clean matrices/dataframes, and if necessary, export into a form that makes sense (e.g., text files or a database).
  - Explore the mathematical properties and visualize data through a visualization tool.  (e.g., `matplotlib` and `seaborn`)
  - Provide insight about the dataset and any impact on a hypothesis.

- **Detailed Breakdown:**
  - A well organized Jupyter notebook with code and output.
  - At least one visual for each independent variable and, if possible, its relationship to your dependent variable.
    - It's just as important to show what's not correlated as it is to show any actual correlations found.
    - Visuals should be well labeled and intuitive based on the data types.
      - For example, if your `x` variable is temperature and `y` is "did it rain," a reasonable visual would be two histograms of temperature, one where it rained, and one where it didn't.
    - Tables are a perfectly valid visualization tool!  Interweave them into your work.

- **Bonus:**
  - Surface and share your analysis online.  Jupyter makes this very simple and the setup should not take long.
  - Try experimenting with other visualization languages; python/`pandas`-highcharts, `shiny`/`R`, or for a real challenge, `D3` on its own.  Interactive data analysis opens the door for others to easily interpret your work and explore the data themselves!

---

## RESOURCES

### Suggestions for Getting Started

- Keep the project simple!  The "cool" part of the analysis will come; just looking at simple relationships between variables can be incredibly insightful.
- Consider building some helper functions that help you quickly visualize and interpret data.
   - Exploratory data analysis should be formulaic; the code should not be holding you back.  There are plenty of "starter code" examples from class materials.
- **DRY:** Don't Repeat Yourself!  If you see yourself copy and pasting code a lot, turn it into a function, and use the function instead!

### Specific Tips

- This deliverable should be similar to the work you did for Unit Project 2 earlier in the course.

---

## EVALUATION

The rubric is available [here](./rubric).
