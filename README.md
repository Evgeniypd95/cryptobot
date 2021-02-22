to make the bot work create a tokens.py file where
cmc_token = your token from CoinMarketCap.com
tg_token = your bot's token

$ cd /Users/evgenypavlov/Documents/cryptobot
$ cd bot
$ code .
Green triangle to start the server
$ virtualenv -p python3 /Users/evgenypavlov/Documents/cryptobot
$ source /Users/evgenypavlov/Documents/cryptobot/bin/activate

$ ssh -R 80:localhost:5000 localhost.run
Delete previous webhook. 
In your browser to connect to a webhook again:
https://api.telegram.org/bot1698970219:AAFDYe4Gm7NFSphXKGeRHYTh4QiAYcQ****/setWebhook?url=https://your-localhost-url

Here are the steps for environment setup https://evgenypavlovd.medium.com/creating-a-telegram-bot-full-beginners-guide-2021-df88e680f285
