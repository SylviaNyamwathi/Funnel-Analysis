# Funnel Chart Analysis

This analysis focuses on building a funnel chart from the raw_events data, identifying key user events while removing duplicates to avoid inflating the results. I used 6 event types for the funnel, split by the top 3 countries based on event volume. Insights and event drop-off percentages were calculated to understand user behavior better.

Key points:

- **Query**: The query eliminates duplicate events and keeps only the first occurrence per user for accurate funnel analysis.
- **Funnel Chart**: Created with a country split (United States, India, and Canada), with additional insights on event drop-offs.
- **Device Categories**: Analyzed user events based on device categories to understand how different platforms contribute to the funnel.
You can find the SQL queries used for this analysis [here in the Google Sheet](https://docs.google.com/spreadsheets/d/1l0qp8WbqeERRdpN8QQzpKYI_43jCAKaO/edit?usp=sharing&ouid=107830398096037668785&rtpof=true&sd=true).
