# idrc-rpaday2

Day 2 Challenge: Intelligent Email Classifier

1. Download excel data attached.
2. [Spam_Email_DataSet.xlsx](https://github.com/incubateind/idrc-rpaday2/files/6603736/Spam_Email_DataSet.xlsx)
3. Create Train Data -> train.csv
4. Create Test Data -> test.csv
5. Create a project in AI Center as Intelligent Email Classifier
6. Upload the dataset
7. Select the English Text classification ML Model
8. Train the ML Model with the dataset
9. Create a Uipath workflow which reads email as input
10. Using intelligent Email Classifier ML Skill detect whether email is spam or not. 
11. Classify email in specific folders.

-----------------------------------------------------------------------------------------------------------
Day 2 Challenge: AI Enabled - Email Classifier

1. Create 2 ML Projests in AI Center
        a. Sentiment Analysis
        b. Language Detection
2. Deploy 2 ML Skills - Non retrainable models 
        a. Language Analysis - SentimentAnalysis
        b. Language Analysis - LanguageDetection
3. Create a UiPath Workflow as follows
4. Input: 20 Emails in different langugages as follows: 
        a. 5 - English Language Emails
        b. 5 - Russian Language Emails
        c. 5 - Hindi Langugage Emails
        d. 5 - French Emails
5. Create 4 Folders - For each language in Email.
6. Using Language Detection classify all the emails to respective folders.
7. Read Email Body of english language emails and identify sentimes from each email.
8. Create a Excel output file for English language emails and update the following columns.
9. Excel Output Format:
  Sender Name | Email Subject | Email Body | Sentiment | Confidence | Email Time
10. Happy Automation!     
