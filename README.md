# steam-autotrader

## A NodeJS bot written to boost your steam trade counter for your profile.

### **Requirements:**
* NodeJS
* 2 Steam accounts (Mobileguard for more than 7 days)
* The shared_secret and identity_secret for those two accounts

### **Setup:**

Fill out the `settings.json` file with at least two accounts and set a trade key. This key will be used to identify bot trades.
To install the dependecies run
```
npm install
```
Just as every other app you can start it with
```
node app
```
If you wish to run it in background you can use forever
```
npm install -g forever
forever start app.js
```

### **Trading:**

To start using the tradebot, log into one of the accounts and send the other one a tradeoffer with **_1_** steamcommunity item (https://steamocommunity.com/id/yoururl/inventory/753_6) and set your choosen _tradekey_ as the message of the trade. Confirm that trade in your mobile guard and watch the bot trade between the two accounts.
You can insert more accounts into `settings.json` and then all those accounts are able to accept trades and resend them exactly.

### **Support:**

If you have questions or suggestions, bugs or improvements, make sure to create an issue or fork my repo and enhance it :)