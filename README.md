# ETL-Project
This is a data engineering project using AWS and Snowflake. Here we extract data using spotify api in S3 bucket and do transformation using AWS Lambda function and load the data in Snowflake using Snowpipe. Lastly we can analyze the data using ChatGPT if we want.

Key Components:

1. AWS S3 Storage: Utilized for managing raw and transformed data files.
2. Lambda Functions: Used for automating data extraction, transformation, and loading processes.
3. Snowflake Integration: Enabled seamless loading of transformed data to Snowflake for storage and analysis.


Technical Details:
- Extracted playlist data using Python and Spotipy library.
- Scheduled data extraction using AWS EventBridge CRON trigger & Event based triggers.
- Extracted audio features for each song to understand its popularity and characteristics.
- Established connection between AWS S3 and Snowflake for automated data ingestion.
