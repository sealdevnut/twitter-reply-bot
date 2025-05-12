# [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Want%20to%20create%20your%20own%20AI%20powered%20Twitter%20bot?%0ATry%20this%20one%20that%20searches%20for%20tweets%20with%20specific%20keywords%20and%20replies%20with%20comments%20generated%20by%20@OpenAI&url=https://github.com/sojinsamuel/Twitter-Comment-Bot&hashtags=chatgpt) Twitter Comment Bot

This Twitter Comment bot comments on tweets containing a specified keyword. The bot uses the OpenAI API to generate comments and the Twitter API to post them. It is designed to run continuously, with a fixed delay between each comment.

## :technologist: Technologies used

- Node.js
- Axios
- twit
- Twitter API
- OpenAI API

## :mechanical_arm: How it works

- The bot uses the Twitter API to search for tweets containing the specified keyword.
- For each tweet found, the bot uses the OpenAI API to generate a comment.
- The bot then uses the Twitter API to post the generated comment as a reply to the tweet.
- The bot waits for a fixed amount of time before searching for new tweets again.

## :imp: Requirements

- A Twitter developer account and API keys (with elevated access)
- An OpenAI API key

## :rocket: Deploying to Heroku

The bot can be easily deployed to Heroku to run 24/7. Follow the steps in the [Heroku documentation](https://devcenter.heroku.com/articles/getting-started-with-nodejs) to set up a Heroku account, create a new app, and deploy the code. Don't forget to set up the environment variables in the Heroku app's settings.

Could you please spread the word through Twitter :arrow_right: [![Tweet](https://img.shields.io/twitter/url/http/shields.io.svg?style=social)](https://twitter.com/intent/tweet?text=Want%20to%20create%20your%20own%20AI%20powered%20Twitter%20bot?%0ATry%20this%20one%20that%20searches%20for%20tweets%20with%20specific%20keywords%20and%20replies%20with%20comments%20generated%20by%20@OpenAI&url=https://github.com/sojinsamuel/Twitter-Comment-Bot&hashtags=chatgpt)

## :computer: Unlock full potential of Twitter Comment Bot with Professional Assistance

I am glad to make this bot available for you to use, If you need help in setting this up on AWS or Heroku, I am willing to assist you. However, please note that this service comes at a cost.

# Project Notice

⚠️ **Warning:** This project uses Twitter API v1, which is now deprecated.

Starting from now, all bots must be developed using the Twitter API v2.

I can help you migrate your project to the new API. Feel free to contact me [here](mailto:sojinsamuel2001@gmail.com) for assistance.

To verify this deprecation and learn more, please visit [this link](https://twittercommunity.com/t/reminder-to-migrate-to-the-new-free-basic-or-enterprise-plans-of-the-twitter-api/189737).
