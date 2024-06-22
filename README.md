Exploring the Correlation Between Social Media Usage and Emotional Wellbeing

This project is a part of the AAI-500 course in the Applied Artificial Intelligence Program at the
University of San Diego (USD).

Project Status: [Completed]

Installation
You should add an instruction how this project to be used, installed, run, edited in others’
machine.

All of our gathered metrics are stored in a Jupyter notebook, specifically Social_Media_Notebook_v9.ipynb. To run it you will need to install Python version 3.11 or later.

You will need to install some modules using PiP, Conda, or your preferred installation method. 

PiP: https://pip.pypa.io/en/stable/cli/pip_install/
Conda: https://conda.io/projects/conda/en/latest/user-guide/install/index.html

Modules to install: pandas, statsmodels, matplotlib, seaborn, scipy, sklearn

Project Intro/Objective
The main purpose of this project is to determine if there is a correlation between social media usage and emotional well-being using this dataset:

https://www.kaggle.com/datasets/emirhanai/social-media-usage-and-emotional-well-being

Our goal is to analyze what effects if any social media has on our emotions through metrics inherent to social media usage. Metrics such as Likes Per Day,
amount of time spent on social media, and more.

Partner(s)/Contributor(s)
• Gurleen Virk
• Samantha Colbert-Neal
• Victor Hsu

Methods Used
• Inferential Statistics (Pairwise T-Tests, Chi-squared Test, Hypothesis testing, Linear Regression)
• Machine Learning (Random Forest, K-means Clustering)
• Data Cleaning and preprocessing
• Descriptive Statistics (Histograms, Bar plots, Box plots, Scatterplots, Outlier Detection)

Technologies
• Python
• Jupyter Notebook

Project Description
Discuss the details of project overview. Description your selected dataset, such as data source,
number of variables, size of dataset, etc. Include data dictionary, if available. Provide questions
and hypothesis that you are exploring. What specific data analysis, visualization, and modeling
work are you using to solve the problem? What roadblocks and challenges are you facing? etc.

Dataset Features:

• User_ID: Unique identifier for the user

• Age: Age of the user

• Gender: Gender of the user (Female, Male, Non-binary)

• Platform: Social media platform used (e.g., Instagram, Twitter, Facebook, LinkedIn, Snapchat, WhatsApp, Telegram)

• Daily_Usage_Time (minutes): Daily time spent on the platform in minutes

• Posts_Per_Day: Number of posts made per day

• Likes_Received_Per_Day: Number of likes received per day

• Comments_Received_Per_Day: Number of comments received per day

• Messages_Sent_Per_Day: Number of messages sent per day

• Dominant_Emotion: User's dominant emotional state during the day (e.g., Happiness, Sadness, Anger, Anxiety, Boredom, Neutral)

SOURCES
The data for this dataset was generated using a hypothetical survey-based methodology, designed to simulate real-world social media usage patterns and the corresponding emotional states of users. The dataset was meticulously researched and prepared by AI Inventor Emirhan BULUT. The data points were crafted to represent a diverse set of users from various social media platforms, capturing their daily activities and emotional responses.

COLLECTION METHODOLOGY
The data was collected through a hypothetical survey where participants were asked about their daily social media usage, including the amount of time spent on different platforms, the number of posts made, likes and comments received, and messages sent. Additionally, participants reported their dominant emotional state at the end of each day. Responses were then collated and structured into three different files: `train.csv`, `test.csv`, and `val.csv`, each serving a specific purpose in data analysis and machine learning model training and validation.

MODELING WORK
Linear regression was used to draw correlations between independent variables of engagement (likes, posts, comments, etc.), daily usage versus the dependent variable of the dominant emotion.
Additional conclusions were verified and drawn from k-means clustering and random forest. k-means clustering confirmed the correlation between daily usage and dominant emotion, while random forest showed the precision of being able to predict emotion from our independent variables.

ROADBLOCKS/CHALLENGES

Modeling - There was a struggle here because of the categorical nature of dominant emotion, once we learned about the dummy method, that helped with forming conclusions for linear regression. There was also a struggle with multicollinearity for the independent variables, which we resolved by standardizing all relevant variables (found with coefficiency matrix/ random forest importance) and forming it into a single variable (overall engagement).

License

Dataset License: https://www.mit.edu/~amini/LICENSE.md

Acknowledgments
Special acknowledgements towards the team who stayed motivated, showed patience and kindness while making progress towards our final results and conclusions.
