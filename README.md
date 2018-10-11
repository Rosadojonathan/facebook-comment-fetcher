Fetches negative comments on Facebook Ads for some Facebook Ads accounts and pushes them to Slack

Uses VADER sentiment analysis library and deepL to translate sentences from French to English

Needs to iterate over Facebook Ads accounts every 15 minutes and checks for new comments

already_parsed.db is cleaned every week so that the script doesn't get too slow overtime (time complexity O(n))
