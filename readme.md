

## Setting up the bot

1. Go to [Slack API](https://api.slack.com);
2. Create a new app
3. In the basic information tab, you will find the parameters like token, secret etc. for setting up the .env.
4. Copy the `clientSigningSecret` and paste it in the `.env`. 
5. For `botToken` in the `.env`, use the legacy slack auth token which can be generated [here](https://api.slack.com/custom-integrations/legacy-tokens). 


## Integrating with slack

Follow [this procedure](https://botkit.ai/docs/provisioning/slack-events-api.html)
