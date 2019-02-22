# YouTube APIs

## YouTube Data API Authentication Instructions

1. Create credentials (API key) here: https://console.developers.google.com/apis/credentials?project=clean-skill-232401&folder&organizationId
2. Pass in API key in endpoint as done in get_video_metadata().

## YouTube Analytics API Authentication Instructions

#### Source: https://developers.google.com/youtube/reporting/v1/code_samples/python#retrieve_daily_channel_statistics

1. Create credentials here: https://console.developers.google.com/apis/credentials?project=clean-skill-232401&folder&organizationId
  - When prompted to select application type, be sure to select 'Other.'
2. Click the down arrow icon to download the JSON file and name it CLIENT_SECRETS_FILE in nb
3. Installation:
  - pip install --upgrade google-api-python-client
  - pip install --upgrade google-auth google-auth-oauthlib google-auth-httplib2

Once setup, visit the Youtube API [GitHub](https://github.com/youtube/api-samples/tree/master/python) to explore the different capabilities.
