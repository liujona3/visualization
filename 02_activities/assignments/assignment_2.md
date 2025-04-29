# Data Visualization

## Assignment 2: Good and Bad Data Visualization

### Requirements:

- Data visualizations are important tools for communication and convincing; we need to be able to evaluate the ways that data are presented in visual form to be critical consumers of information 
- To test your evaluation skills, locate two public data visualizations online, one good and one bad  
    - You can find data visualizations at https://public.tableau.com/app/discover or https://datavizproject.com/, or anywhere else you like! 
- For each visualization (good and bad):  
    - Explain (with reference to material covered up to date, along with readings and other scholarly sources, as needed) why you classified that visualization the way you did.
      ```
      'good': https://dribbble.com/shots/462651-Conversions?list=show&tag=funnel
      - This visualization has good/clear encoding, where the size/width of the funnel is representative of the magnitude. In this case, the wider/larger the funnel, the more usuers it represents. Implementing a funnel like plot for conversion drop offs allows the viewer see the magnitude of dropoffs at each stage, potraying the effects at each stage specifically in a sequential direction.
      - In this context, implementing the different stages into the same plot allows for direct comparisons, speciifcally through the one continuous funnel, where you can directly relate stages to one another. 
      - The use of colour was also well implemented, where similar hue of colours were used. Specifically, the each sequential stage was of a different luminance.
      - In addition to using size/width to represent the numbers, the actual numbers were also included for each stage, with the addition of the conversion % at each stage.
      - The title and labels are clear and convey the purpose of the visualization. For example: Patient conversion, 30 days, and at each stage. 
      
      'bad': https://public.tableau.com/app/profile/yuchen.luo4060/viz/bad_example/Sheet1
      I classified this visualization as bad because of several reasons.
       - There is no title or proper labels to properly describe the dataset context.
       - The encode seems to be lacking effectiveness, specifically through Map, where the colour remains the same for different charts.
       - Too many different charts and since they are separate, hard for direct comparisons.
       - If the purpose is mroe focused on trends over time for each answer, then separate charts might make sense. Trends can be seen in some charts where there are larger responses, but for the answers with less responses, trends can be hard to spot since the y axis magnitudes remain the same for every chart. Smaller changes are harder to spot on such a large scale.
       - In addition to this, the actual number of resposnes per year are not shown so it can be more difficult to see the differences.
      ```
    - How could this data visualization have been improved?  
      ```
      'good': https://dribbble.com/shots/462651-Conversions?list=show&tag=funnel
      - It is not 100% clear how the overall conversion is calculated based on the placement and the mini lineplot. It is the final number/the starting number but can be confusing due to placements.
      - The converison % at each stage is not labelled and can be confused to what they represent. The colour remains the same for all conversion % at each stage as well. Perhaps having a different luminescence for each stage could help with clarity.
      
      'bad': https://public.tableau.com/app/profile/yuchen.luo4060/viz/bad_example/Sheet1
      - providing a clear/clean title and labels to provide context for the visualization
      - Perhaps encode different responses as differents colours on the same chart for easier direct comparison
      - If they are more intereseted in the changes over time than direct comparisons, they could rescale the y axes for each chart, this allows changes in the smaller responses to be seen easier.
      - Adding the number of responses for each answer at each time points can also provide somethign to help the audience compare/see trends.
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
* Submission Due Date: `23:59 - 30/04/2025`
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

If you encounter any difficulties or have questions, please don't hesitate to reach out to our team via our Slack. Our Technical Facilitators and Learning Support staff are here to help you navigate any challenges.
