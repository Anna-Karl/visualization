# Data Visualization

## Assignment 4: Final Project

### Requirements:
- We will finish this class by giving you the chance to use what you have learned in a practical context, by creating data visualizations from raw data. 
- Choose a dataset of interest from the [City of Toronto’s Open Data Portal](https://www.toronto.ca/city-government/data-research-maps/open-data/) or [Ontario’s Open Data Catalogue](https://data.ontario.ca/). 
- Using Python and one other data visualization software (Excel or free alternative, Tableau Public, any other tool you prefer), create two distinct visualizations from your dataset of choice.  
- For each visualization, describe and justify: 

Data Source: https://data.ontario.ca/dataset/university-enrolment

     > What software did you use to create your data visualization?

For Visualization 1, I used Python with libraries such as Numpy, Pandas, Matplotlib, and Seaborn, running in Jupyter Notebooks for writing, testing, and visualizing the code and outputs. This visualization represents Toronto Metropolitan University and focuses on analyzing trends in student enrollment over time.

For Visualization 2, I used Tableau Public, which allowed me to create interactive and user-friendly visualizations. The visualization represents the University of Toronto and provides insights into student enrollment patterns.

 > Who is your intended audience? 

Students, prospective students, and their parents might be interested in understanding the trends in different academic programs and study levels, especially those interested in applying to Architectural Science and Architectural Arts programs.
Educational Administrators and Policymakers who need insights into student enrollment trends for decision-making
Researchers or data analysts are involved in studying educational patterns and trends.  
    
 > What information or message are you trying to convey with your visualization?

Visualization 1 conveys trends in enrollment data for Toronto Metropolitan University, including how student enrollment in different programs has evolved over the years, the distribution of students across study levels, and the program-wise distribution of undergraduate enrollments.
Visualization 2 provides insights into student enrollment trends at the University of Toronto, specifically for various programs. It emphasizes the most popular programs and their changes over time. 
    
 > What design principles (substantive, perceptual, aesthetic) did you consider when making your visualization? How did you apply these principles? With what elements of your plots?

Substantive principles: I ensured the data was clearly represented and easily understandable. In both visualizations, I focused on showing trends over time and categorizing data effectively (e.g., using grouped bars or pie charts).
Perceptual principles: I used color palettes (e.g., Seaborn's "rocket" palette) to differentiate data groups and visually make the chart more engaging. I also used labels and percentages in pie charts to improve comprehension.
Aesthetic principles: I maintained clean and minimal designs, keeping visual elements consistent and non-distracting. I used well-organized charts with readable fonts and appropriate color contrasts to ensure the data was accessible.
    
 > How did you ensure that your data visualizations are reproducible? If the tool you used to make your data visualization is not reproducible, how will this impact your data visualization? 

For Visualization 1, I ensured that my work was reproducible using Python scripts and Jupyter Notebooks, which contain both the code and the output. Anyone can rerun the scripts to generate the same results.
In Visualization 2, Tableau Public supports reproducibility by allowing others to download the workbook and interact with the same datasets to replicate the analysis.

 > How did you ensure that your data visualization is accessible?  

In both visualizations, I ensured that the fonts were legible, the colors were chosen to be colorblind-friendly, and the axes were labeled clearly. In Tableau, I added tooltips to provide additional context and used interactive filters to allow users to explore the data according to their interests.

 > Who are the individuals and communities who might be impacted by your visualization?  

Students and Prospective Students are the primary beneficiaries of these visualizations. They can use them to gain a comprehensive understanding of enrollment trends and make well-informed decisions about their future studies, empowering them in their academic journey.
Faculty and Department Chairs could use these visualizations to assess different programs' popularity and enrollment patterns, helping optimize academic offerings.

 > How did you choose which features of your chosen dataset to include or exclude from your visualization? 

I focused on key features related to enrollment trends:
Program Name, Fiscal Year, and HEADCOUNT were chosen because they provide valuable insights into the number of students enrolled in each program over time.
Data regarding study levels (Undergraduate vs Graduate) and the specific programs were prioritized to highlight key differences in enrollment patterns.

 > What 'underwater labour' contributed to your final data visualization product?
 
Data Cleaning: I had to filter out missing or invalid data (e.g., programs with missing enrollment data) and ensure the dataset was properly structured for aggregation and plotting.
Data Transformation: I converted the Fiscal Year and HEADCOUNT columns to the correct data types and aggregated the data at different levels (by program, by year).
Customization: To ensure clarity, I adjusted the visualization aesthetics, such as changing color palettes, changing labels, and fine-tuning the chart layout.

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
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-4`
* What to submit for this assignment:
    * A folder/directory containing:
        * This file (assignment_4.md)
        * Two data visualizations 
        * Two markdown files for each both visualizations with their written descriptions.
        * Link to your dataset of choice.
        * Complete and commented code as an appendix (for your visualization made with Python, and for the other, if relevant) 
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-4`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
