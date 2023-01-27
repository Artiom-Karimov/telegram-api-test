# Telegram bot using express
## Capabilities
- On /start command it sends back menu of 2 buttons
- It can flip a coin (heads/tails)
- It can generate random number (1-10)

## What's in the project
- <a href="https://expressjs.com/">Express</a> for receiving messages
- <a href="https://axios-http.com/">Axios</a> for sending messages
- <a href="https://ngrok.com/">Ngrok</a> for setting webhook (development mode)
- <a href="https://inversify.io/">Inversify</a> for keeping things cleaner
- API models with detailed description
- Security token generation on startup
- Custom logger
- Unhandled error processing


## How to set up
<p>The bot connects to <a href="https://core.telegram.org/bots/api">Telegram API</a> using webhook.</p> 
<p>You should register your bot using @BotFather, 
<br>then copy generated API token into TELEGRAM_TOKEN environment variable.</p>
<p>When BASE_URL env variable is not set, it uses <a href="https://www.npmjs.com/package/ngrok">Ngrok</a> to create a hook.</p>
<p>If you don't need it, set BASE_URL to your host (https://example.com).
<br><strong>Note:</strong> It should use https. Telegram supports only common http ports (80, 8080, 443) </p>

