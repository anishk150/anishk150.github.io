# Predictive Maintenance for Swire Coca-Cola 

## Business Problem & Project Objective
Coca-Cola faces significant challenges in managing maintenance across their facilities, with a high number of unplanned maintenance events leading to operational disruptions and increased costs. The objective of this project is to develop a predictive model that can accurately forecast maintenance requirements, helping transition from reactive to proactive maintenance approaches. By analyzing historical maintenance data from various facilities, we aim to identify patterns and predict potential equipment failures before they occur, ultimately reducing downtime and optimizing resource allocation.

## Group's Solution to the Business Problem
Our team developed a comprehensive solution utilizing both Logistic Regression and Random Forest models to predict unplanned maintenance events. The initial Logistic Regression model achieved 82.3% accuracy, with precision at 74.5% and recall at 64.2%. We then improved upon these results with a Random Forest model, which achieved superior performance with 87.0% accuracy, 81.2% precision, and 74.8% recall. The Random Forest model particularly excelled at identifying location-specific maintenance patterns and equipment age impacts, providing more nuanced predictions than the simpler logistic approach.

## My Contribution to the Project
In this project, I took the lead on:

- Data preprocessing and cleaning, handling missing values and standardizing formats
- Developing and implementing both Logistic Regression and Random Forest models
- Creating visualizations for missing data analysis and maintenance patterns
- Conducting statistical analysis to identify key predictive factors
- Interpreting model results and translating them into actionable insights
- Documenting the technical approach and findings

## Business Value of the Solution
Our predictive maintenance solution delivers substantial business value through:

- Reduction in unplanned downtime by enabling proactive maintenance scheduling
- Cost savings through better resource allocation and maintenance planning
- Improved operational efficiency across different facilities
- Enhanced equipment longevity through timely interventions
- Data-driven decision making for maintenance operations

The Random Forest model's superior performance (87% accuracy) translates to potentially preventing thousands of hours of unplanned downtime annually.

## Difficulties Encountered
Throughout the project, our team faced several challenges:

1. Data Quality Issues

- Significant missing values in equipment and maintenance data
- Inconsistent data formats across different facilities
- Complex temporal relationships in maintenance patterns


2. Technical Challenges

- Initial model convergence issues with logistic regression
- Balancing model complexity with interpretability
- Integrating temporal features effectively


3. Implementation Hurdles
- Handling large dataset (1.4 million records)
- Computing resource limitations
- Cross-validation with time-series data

## Learning Outcomes
1. Technical Skills Development
Through this project, I gained extensive hands-on experience with advanced predictive modeling techniques. The process of handling a large-scale maintenance dataset enhanced my proficiency in data preprocessing, feature engineering, and model optimization. Working with time-series data presented unique challenges that required developing specialized solutions for temporal feature creation and validation strategies. I learned to effectively implement and compare different machine learning algorithms, particularly focusing on the nuances between Logistic Regression and Random Forest models. The experience of handling missing values and implementing various data imputation techniques significantly improved my data cleaning capabilities.
2. Business Understanding and Analytics
This project deepened my understanding of industrial operations and maintenance management. I learned how to translate complex technical findings into actionable business insights, particularly in the context of predictive maintenance. Working with maintenance data helped me understand the critical balance between maintenance costs and operational efficiency. I gained valuable insights into how data-driven decision making can significantly impact business operations, especially in reducing unplanned downtime and optimizing resource allocation. The process of developing performance metrics and conducting cost-benefit analyses enhanced my ability to quantify the business impact of technical solutions.
3. Professional Skill Enhancement
The project significantly developed my project management and communication skills in a data science context. I learned to effectively collaborate with team members, present technical findings to non-technical stakeholders, and document complex analytical processes. The experience of working with real-world industrial data taught me the importance of balancing theoretical knowledge with practical considerations. I developed strong problem-solving skills, particularly in handling unexpected data challenges and model performance issues. The project also enhanced my ability to write clear, comprehensive documentation and present results in an accessible manner.
4. Machine Learning Application Expertise
Working on this project provided deep insights into the practical application of machine learning in an industrial setting. I gained experience in selecting appropriate algorithms based on business requirements, handling class imbalance in real-world datasets, and implementing cross-validation strategies for time-series data. The process of model selection and optimization taught me the importance of balancing model complexity with interpretability. I learned to effectively evaluate model performance using various metrics and make data-driven decisions for model selection.
5. Data Visualization and Communication
The project enhanced my data visualization skills, particularly in creating meaningful representations of complex maintenance patterns and model results. I learned to use various visualization techniques to communicate insights effectively to different stakeholders. The experience of creating dashboards and summary reports improved my ability to present technical findings in an accessible format. I developed expertise in using visualization tools to identify patterns in maintenance data and communicate predictive model results.

The project enhanced my understanding of both the technical aspects of predictive modeling and the practical considerations of implementing such solutions in an industrial setting. The experience of working with real-world maintenance data and addressing actual business challenges provided invaluable insights into the intersection of data science and business operations.
