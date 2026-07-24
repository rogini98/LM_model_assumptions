# Model Formulation and Assumptions in the Linear Model

The teaching materials presented here are built around a single running example: predicting a
child's height from age, which we use to review the simple linear regression model. 
We then introduce the four assumptions of linear models (**LINE**: Linear, Independent, Normal, Equal variance).
Finally, we look at what happens when real growth data breaks each of those assumptions.

## Learning objectives

By the end of this mock lecture, you will be able to:

* **Analyze** the core concepts presented in [`slides/mock-lecture-rr.pdf`](slides/mock-lecture-rr.pdf)
* **Execute** and modify data workflows inside [`notebook/growth_LINE_notebook.Rmd`](notebook/growth_LINE_notebook.Rmd)
* **Validate** your understanding using the interactive [`quiz/mystery_plot_quiz.html`](quiz/mystery_plot_quiz.html)

## How to use each one

**Slides**: PDF renders directly in GitHub, no download needed.

**Notebook**: You can view the rendered version at
[`notebook/growth_LINE_notebook.html`](notebook/growth_LINE_notebook.html) directly in your browser (no installation is required).
To run and edit the code yourself, download the
[source (.Rmd)](notebook/growth_LINE_notebook.Rmd) and open it in
RStudio. Each section ends with a "Try it yourself" prompt.

**Quiz**: click [`quiz/mystery_plot_quiz.html`](quiz/mystery_plot_quiz.html),
answer all 8 questions, see your score at the end. No login or prior setup is required, it runs entirely in your browser.

## Data

Growth curves are anchored to real, published CDC growth-chart medians
(we specifically used: height-for-age and weight-for-age). Individual data points shown in the
figures are simulated around those real curves, not drawn from actual
patient records.

**Source:** https://www.cdc.gov/growthcharts/cdc-data-files.htm

***NOTE*** The **R notebook** fetches real CDC/NCHS 2000 Growth Chart medians directly from the official
CDC data files every time it runs. Whereas the **slide deck**'s static figures use representative approximations
of the same published growth curves rather than numbers pulled directly from the CDC files.

## License

Feel free to reuse or adapt for teaching purposes.
