# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
https://public.tableau.com/app/profile/naresh.suglani/viz/LondoninNumbers/LondonDemographics

The provided visualization, titled "London in Numbers: Data-Driven Insights for the Capital City," is well-executed for several reasons:

Clarity and Simplicity: The visualization, with its user-friendly interface and effectively grouped information (e.g., population density, crime, health) in distinct panels, ensures that the viewer can easily navigate and focus on specific insights, promoting a sense of ease and comfort.
Color Coding: Using purples and gradients visually emphasizes differences in metrics, such as population density or crime rates, without overwhelming the viewer.
Interactive Components: Features like a borough filter and crime type selector offer dynamic insights tailored to user interest, enhancing engagement.
Legibility: Labels, legends, and concise text annotations are clear and accessible, contributing to easy comprehension.
Data Integrity: The use of census data from 2021 and credible sources (e.g., OpenStreetMap) ensures the information is grounded in reality, fostering a sense of security and confidence in the reliability of the data.
Data Representation: Metrics such as population, house prices, and mean income are displayed quantitatively without distortion or bias.
Audience-Centric Design: The dashboard, designed with the needs and interests of policymakers, urban planners, and citizens in mind, provides relevant insights, making the audience feel valued and considered in the visualization process.
Data Context: Each chart and metric includes contextual information, such as time frames, ensuring interpretive accuracy.
Regional Focus: The borough-level granularity supports localized decision-making, making the visualization actionable.
Balance and Layout: The even distribution of charts and maps ensures no single element dominates the dashboard, achieving visual harmony.
Modern Styling: The sleek fonts, icons, and minimalist background highlight the data effectively without distractions.
Engaging Interactivity: Elements such as toggles for map layers and dynamic filters add a visually and functionally appealing dimension.

https://public.tableau.com/app/profile/jmackinlay/viz/TableauHistory/History

The visualization titled "Tableau Innovation History" provides an overview of Tableau's features and product development over time. Why is it Bad?

Clarity and Simplicity: The dashboard tries to present too much information in a single view, leading to visual clutter. For instance:
The timeline chart (number of features per release) competes with the table of features, which is dense and difficult to scan.
Multiple dropdown filters and color-coded ratings make the interface overwhelming rather than intuitive.
Poor Use of Space: The visualization dedicates a significant portion of the screen to the table, leaving little room for more insightful or impactful charts. This imbalance creates a disproportionate emphasis on granular details over broader trends.
Insufficient Context: While the timeline chart includes milestones (e.g., "IPO 13" and "New CEO 16"), these annotations are vague and lack an explanation of their relevance to the data. There's also no description of what "Gold," "Iron," and "Water" ratings signify, leaving the viewer to guess their importance.
Ambiguity in Data: The dashboard does not clarify its intended audience. Is it for Tableau users, employees, or a general audience? Without this context, the significance of the features and ratings is unclear.
Lack of a Narrative: The visualization fails to guide the viewer through a story. 
Aesthetic Appeal: Dropdown menus for "Release," "Product," "Feature Type," and "Feature Wildcard" crowd the interface, making the visualization harder to navigate.
Table Design: The table, with small text and densely packed rows, dominates the screen without providing meaningful visual insights.
Inconsistent Color Use: The ratings (Gold, Iron, Water) use colors that do not relate to the timeline or other visualizations, reducing the dashboard's cohesion.

Comparison with Figure 1 (London in Numbers)
For instance, 'London in Numbers' effectively balances granularity with high-level insights, providing a clear and engaging narrative. In contrast, the 'Tableau Innovation History' visualization struggles with focus and clarity, making it difficult for the viewer to grasp the key points.
While "London in Numbers" uses interactivity to enhance understanding, "Tableau Innovation History" relies heavily on dropdown menus, which obscure the broader story.




      ```
    - How could this data visualization have been improved? 
 
      ```
      Simplify the Table: Replace the detailed table with a concise summary, focusing on key features or notable releases. This will help the audience to grasp the main points quickly and reduce information overload. For example, replace the table with a high-level heatmap or bar chart summarizing feature ratings. Allow users to drill down interactively to view specific features, maintaining detail for those who need it.
Spotlight Trends: Leverage the timeline to spotlight trends in feature development, with milestones elucidated through tooltips or annotations. For instance, stacked bar charts can be employed to dissect the count of features per release by rating (Gold/Iron/Water) or feature type (e.g., Desktop, Server, Connectivity). This approach will help to craft a clear narrative that steers the viewer through Tableau's innovation journey.
Contextualize Ratings: Provide a legend or brief description of what "Gold," "Iron," and "Water" represent. This will make the audience feel knowledgeable and confident in their understanding of the data.
Improve Layout: Allocate more space to visualizations like bar charts or heatmaps, reducing the prominence of text-heavy elements.
Narrative Focus: Incorporate a clear narrative that guides the viewer through Tableau's innovation journey.
Aesthetic Design: Use a consistent color scheme across all elements. Ensure these colors are accessible to individuals with color vision deficiencies. Apply the same color scheme to the timeline and other visual elements, creating a cohesive narrative. Use consistent font sizes and styles for labels and headers to create a cleaner look. Add white space to improve readability and reduce visual fatigue.






      
      ```
- Word count should not exceed (as a maximum) 500 words for each visualization (i.e. 
300 words for your good example and 500 for your bad example)

### Why am I doing this assignment?:

- This assignment ensures active participation in the course, and assesses the learning outcomes
* Apply general design principles to create accessible and equitable data visualizations
* Use data visualization to tell a story

### Rubric:

| Component               | Scoring   | Requirement                                                 |
|-------------------------|-----------|-------------------------------------------------------------|
| Data viz classification and justification | Complete/Incomplete | - Data viz are clearly classified as good or bad<br />- At least three reasons for each classification are provided<br />- Reasoning is supported by course content or scholarly sources |
| Suggested improvements  | Complete/Incomplete | - At least two suggestions for improvement<br />- Suggestions are supported by course content or scholarly sources |

## Submission Information

🚨 **Please review our [Assignment Submission Guide](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md)** 🚨 for detailed instructions on how to format, branch, and submit your work. Following these guidelines is crucial for your submissions to be evaluated correctly.

### Submission Parameters:
* Submission Due Date: `HH:MM AM/PM - DD/MM/YYYY`
* The branch name for your repo should be: `assignment-2`
* What to submit for this assignment:
    * This markdown file (assignment_2.md) should be populated and should be the only change in your pull request.
* What the pull request link should look like for this assignment: `https://github.com/<your_github_username>/visualization/pull/<pr_id>`
    * Open a private window in your browser. Copy and paste the link to your pull request into the address bar. Make sure you can see your pull request properly. This helps the technical facilitator and learning support staff review your submission easily.

Checklist:
- [ ] Create a branch called `assignment-2`.
- [ ] Ensure that the repository is public.
- [ ] Review [the PR description guidelines](https://github.com/UofT-DSI/onboarding/blob/main/onboarding_documents/submissions.md#guidelines-for-pull-request-descriptions) and adhere to them.
- [ ] Verify that the link is accessible in a private browser window.

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack at `#cohort-3-help`. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
