# GoogleNews-Vendor-Risk-Analysis

This project provides an automated solution to assess the risk associated with companies based on their news coverage. By leveraging the `pygooglenews` API and a machine learning pipeline (SVC model with Snorkel integration), the project extracts and categorizes news headlines over a full year to determine whether they are positive or negative. The results are saved in an Excel file for easy review, including details such as the news title, publication date, link, and sentiment score.

## Features

- Extracts news headlines for any given company over a specified year using the `pygooglenews` API.
- Supports sentiment analysis for both English and Spanish news sources.
- Uses a combined SVC model with Snorkel to categorize news titles into positive or negative.
- Generates an Excel report with the following columns:
  - News title
  - Publication date
  - Link to the news article
  - Sentiment analysis result (Positive/Negative)
- The sentinment analysis model has a precision of 0.88.
- The complete process runs in approximately 5 minutes.

## Use Case

This project is designed for investigating companies, particularly suppliers, to help determine their reliability based on the sentiment of news coverage over time. It provides a fast and automated way to detect potential risks by highlighting negative news articles.
