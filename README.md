# Message-Spam-Filter

**Spam Message Classification Using Naive Bayes**
This project develops a spam message classifier utilizing Naive Bayes algorithms for natural language processing (NLP). The goal is to distinguish spam from legitimate (ham) messages.
**Data Preparation**
The project begins with importing and exploring the dataset, comprising spam and ham messages. Data cleaning involves renaming and removing irrelevant columns, followed by label encoding to convert categorical labels into binary values. Descriptive statistics and visualizations (pie charts, heatmaps) provide insights into dataset distribution.
**Exploratory Data Analysis (EDA)**
EDA involves analyzing message characteristics: word count, sentence count and character count. Visualizations (displots) compare these features across spam and ham messages, highlighting differences.
**Data Preprocessing**
Text preprocessing is crucial for NLP. This step includes tokenization, removing special characters, punctuation and stop words and stemming. The preprocessed text facilitates model training.
**Model Building and Evaluation**
Three Naive Bayes variants (Multinomial, Bernoulli and Gaussian) are trained and evaluated. Performance metrics include accuracy, classification reports and precision scores. Comparative bar charts illustrate model accuracy and precision.
