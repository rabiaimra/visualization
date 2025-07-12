# Data Visualization

## Assignment 3: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

    > What software did you use to create your data visualization?
    For the first visualization, I used Python with the Seaborn and Matplotlib libraries. For the second, I used Microsoft Excel.

    > Who is your intended audience? 
    The intended audience for both visualizations includes policymakers, business people, educators, economists, and the general public interested in understanding gender-based income disparities in Canada. The visualizations are also designed to support discussions around pay equity and workforce policy.

    > What information or message are you trying to convey with your visualization? 
    The Python visualization conveys the gender wage gap across different education levels and employment types (all employees, full-time, and part-time) for individuals aged 25–54 in Canada. It shows how both gender and education influence wage levels. It is a simple graph but I think it conveys a crucial information on the fact that for all employees, across all education levels, men consistently earn more than women. The wage gap is even more pronounced among higher education levels in full-time employment. Notably, the graph also shows that higher levels of education are associated with higher wages overall, regardless of gender. 

    The Excel line chart illustrates how gender wage trends have changed over time for full-time employees and age group of 25-54, considering additional dimensions with filters such as education, type of work, age group, and immigrant status. Again, this simple graph conveys an important message by showing a steady upward trend for both genders and also a persistent gender wage gap across all years, with men consistently earning more than women. This visualization can also support analysis of whether wage growth has kept pace with inflation over time. 

    > What aspects of design did you consider when making your visualization? How did you apply them? With what elements of your plots? 
    In the Python visualization:
    I used Seaborn’s colorblind-friendly palette to ensure accessibility.
    I sorted education levels logically and used consistent labeling to improve readability.
    Axis labels and titles were enlarged and clearly labeled to guide interpretation.
    Rotated x-axis labels and adjusted font sizes for better readability.
    The legend was placed outside the plot to avoid overlapping with data.

    In Excel:
    I chose a line chart to emphasize trends over time.
    Each line was clearly labeled for gender comparison.
    Color contrast and axis labels were optimized for clarity.

    > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 
    Reproducible work is “capable of being checked because the data, code, and methods of analysis are available to other researchers”, that is, someone could repeat the steps we took to generate a particular result or image from our data. Reproducibility helps to hold us accountable for those decisions.

    The Python chart is fully reproducible:
    I used publicly available Ontario's Open Data Catalogue.
    The code includes all cleaning, filtering, reshaping, and visualization steps.
    The .csv file path can be easily adjusted for replication on another machine.

    The Excel chart is less reproducible, as it involves manual data selection and chart design. This could introduce human error and makes it harder for others to replicate or validate the steps unless they are documented. To mitigate this, I saved the Excel file and ensured the chart is shared within the source file.
    
    > How did you ensure that your data visualization is accessible?  
    Four broad goals for what we should try to accomplish with accessible design:
    *Make information clear, concise and easy to use
    *Present information in predictable, barrier‑free ways
    *Provide barrier‑free ways for people to interact with you
    *Make sure technology-based products work with assistive technologies and devices

    Also, including data source (substantive qualities), using an appropriate plot type for the purpose of the viz, and limiting its color scheme are important for accessibility. 

    In Python visualization:
    Information is presented in a clear and concise way considering colors, text (labels and legends), image descriptions, and getting the visualizations to the intended audiences. 
    I used the colorblind palette in Seaborn for inclusivity and accessibility.
    Font sizes and axis labels were carefully adjusted to be legible for diverse audiences.
    The layout avoids clutter, and the legend is clearly separated from the plot.
    Since the purpose in this viz is to show wage gap for each education level and employment type, bar chart is used. 

    In Excel visualization:
    Information is again presented in a clear and concise way considering colors, text (labels and legends), image descriptions, and getting the visualizations to the intended audiences.
    I used distinct colors for the lines to support users with low vision or color vision deficiency.
    The chart includes gridlines to make trends easier to interpret.
    Since the purpose in this viz is to show the wage trend over years, I used a line chart with years on x axis and wage in y axis. 

    > Who are the individuals and communities who might be impacted by your visualization?  
    Both visualizations impact:
    *Women, regardless of their education level, who are most affected by wage gaps. 
    *Policymakers and employers, who may use this data to inform equity-focused initiatives.
    *Researchers and educators, who may use these visualizations for teaching or advocacy.

    Also for Excel visualization:
    *Immigrants, who were also a dimension in the Excel chart, and who often face wage disparities.
    *Economists may use Excel visualization to compare wage trend vs inflation.  
    
    > How did you choose which features of your chosen dataset to include or exclude from your visualization? 
    In Python:
    I focused on median wages (to reduce outlier effects) and on the 25–54 age group because these are prime working years.
    I excluded overly granular or inconsistent education categories to keep the plot readable and meaningful.
    Only "Men" and "Women" categories were used as gender identifiers due to dataset limitations. It is important to keep in mind that it is a limited representation of other genders. 

    In Excel:
    I included year as a key variable to study trends.
    I focused on full-time work because it shows a better picture of dedicated employment & 25–54 age group because these are prime working years.
    I added filters for education, immigrant status, type of work, and age group to enrich context and to allow flexibility for the audience to filter the requested categories (of course, for this purpose, the source Excel file is needed. The viz picture only shows the filtered viz by the creator.) 
    Only "Men" and "Women" categories were used as gender identifiers due to dataset limitations. It is important to keep in mind that it is a limited representation of other genders.

    > What ‘underwater labour’ contributed to your final data visualization product?
    Government of Ontario and organizers who facilitated data collection 
    Employees of Government of Ontario who conducted data cleaning
    Designers creating colour palettes for visualizations in Python
    My husband who takes care of our child and cooks for us while I am doing this assignment :) 


- This assignment is intentionally open-ended - you are free to create static or dynamic data visualizations, maps, or whatever form of data visualization you think best communicates your information to your audience of choice! 
- Total word count should not exceed **(as a maximum) 1000 words** 
 
### Why am I doing this assignment?:  
- This ongoing assignment ensures active participation in the course, and assesses the learning outcomes: 
* Create and customize data visualizations from start to finish in Python
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story  
- This would be a great project to include in your GitHub Portfolio – put in the effort to make it something worthy of showing prospective employers!

### Rubric:

| Component         | Scoring  | Requirement                                                                 |
|-------------------|----------|-----------------------------------------------------------------------------|
| Data Visualizations | Complete/Incomplete | - Data visualizations are distinct from each other<br>- Data visualizations are clearly identified<br>- Different sources/rationales (text with two images of data, if visualizations are labeled)<br>- High-quality visuals (high resolution and clear data)<br>- Data visualizations follow best practices of accessibility |
| Written Explanations | Complete/Incomplete | - All questions from assignment description are answered for each visualization<br>- Explanations are supported by course content or scholarly sources, where needed |
| Code              | Complete/Incomplete | - All code is included as an appendix with your final submissions<br>- Code is clearly commented and reproducible |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `23:59 - 13/07/2025`
* The branch name for your repo should be: `assignment-3`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_3.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-3`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
