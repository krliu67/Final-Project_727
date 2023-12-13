# A Content Analysis of Reddit User’s Response Towards Students for Fair Admissions v. Harvard
- Final Project of **SURV/SURVMETH 727 - Fundemental of Data Display and Computing** 
+ Work by Chloe Chen and Kangrui Liu

## Background  
Students for Fair Admissions v. Harvard is a landmark decision of the Supreme Court of the United States, in which the court determined that race-based affirmative action in college admissions violates the Fourteenth Amendment's Equal Protection Clause on 29th June, 2023. This ruling has significantly influenced college admissions processes and has elicited diverse reactions from various stakeholders.

## Question of Interest
This study aimed to investigate the impact of the Supreme Court's decision in Students for Fair Admissions v. Harvard on Reddit users. Specifically, it focused on their engagement, emotional tendencies and the topics of concern related to affirmative action in college admissions. Our research questions are detailed as follows:

  (1) Whether the decision of the Supreme Court provoked Reddit users’ discussion concerning race-based affirmative action in college admissions, i.e. how the number of daily comments pertinent to the topic of interests changed after the leak of the decision? 
  
  (2) How did people's sentimental tendencies change before and after the leak of the decision of the Supreme Court? 
  
  (3) What are the topics of interest to people who hold different emotional tendencies, i.e. which topics certain sentiments are related to? 
  

## Methodology
### Data source
We intend to collect Reddit comments posted before and after the Supreme Court decision leak, focusing on those containing keywords relevant to this topic, such as “affirmative action” “fair admission” “SFFA” and “admission discrimination”. Our search will be specifically targeted at certain subreddits. This approach is due to the difficulty in accurately identifying our intended content through a broad, site-wide search. To address potential representative biases that might arise from limiting our search to specific subreddits, we have intentionally chosen a diverse range of subreddits, including those named after various races and representing both major political parties, ensuring considerable heterogeneity in our data.

### Analysis techniques
We intend to employ the Latent Dirichlet Allocation (LDA) model for classifying the comments. Alongside this, we will conduct sentiment analysis coupled with time series analysis to investigate changes in sentiment over time. For visualization purposes, we plan to incorporate interactive time series plots using dygraphs, as well as word clouds to depict word frequencies associated with various topics.
