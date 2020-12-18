# Retrieve Tweets
## Retrieve tweets from the Twitter API Recent Search endpoint from your command line.

### Navigating this Repo
| RetrieveTweets.py   | a Python file that executes Retrieve Tweets  |
| requirements.txt    | a .txt file containing required packages and library  |
| .env                | a file containing your Twitter API credentials   | 

### Instructions for Use
**Note:** This program requires Twitter API credentials. You must have a Twitter developer account to get API credentials. To learn more about how you can obtain your own API keys, please visit [Obtaining user access tokens (3-legged OAuth) | Docs | Twitter      Developer](https://developer.twitter.com/en/docs/authentication/oauth-1-0a/obtaining-user-access-tokens) 

1. For best results, activate a new virtual environment for this program. Read more on how to do that here.
2. Download the contents of this repository.
3. Set the local environment of the directory to the new virtual environment. Read more on how to do that here. Make sure it is activated.
4. Install the required packages into your directory: 
`pip install -r requirements.txt`
3. Edit the contents of `.env` to include your Twitter credentials. 
4. Type `python3 RetrieveTweets.py` and follow the prompts to download your data.
