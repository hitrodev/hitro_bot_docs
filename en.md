`English` | **[`Русский`](/ru.md)**

# HitroBot documentation + instructions

*Follow [HitroNews](https://t.me/hitro_news) Telegram-channel to stay tunned*  
*Contact the developers: [@hitro_dev](https://t.me/hitro_dev)*

---

### [What is HitroBot](#what-is-hitrobot-1)
- #### [Robot profitability](https://www.binance.com/en/futures-activity/leaderboard?type=myProfile&encryptedUid=CEFC421368F9D59B8499CE65813D7FCA)

### [How to start using HitroBot](#how-to-start-using-hitrobot-1)

### [Binance registration and account setup](#binance-registration-and-account-setup-1)

- #### [Promo code with *-10%* Binance commission discount](https://accounts.binance.com/en/register?ref=N587Q7WB)

### [Using Telegram-bot](#using-telegram-bot-1)

### [How to deposit and withdraw funds](#how-to-deposit-and-withdraw-funds-1)

### [HitroBot commission](#hitrobot-commission-1)

### [How to invite friends](#how-to-invite-friends-1)

### [Binance restrictions](#binance-restrictions-1)

### [Frequently asked questions](#frequently-asked-questions-1)

### [Terms and Conditions](#terms-and-conditions-1)


---


## What is HitroBot

HitroBot — fully automated algorithmic robot that trades cryptocurrency futures.
"Hitro" means smart, canny bot.

It is integrated with the Binance exchange as a trading platform. Binance users can connect to the robot.

Is it worth using HitroBot?
**The robot has positive profitability, it is public and available on the [Binance Leaderboard](https://www.binance.com/en/futures-activity/leaderboard?type=myProfile&encryptedUid=CEFC421368F9D59B8499CE65813D7FCA).**

Average profitability is above **+30-50%**. Testing of the algorithm on historical data (backtesting) shows positive results at the end of each month.
Backtesting results are available [here](/backtesting/report.md).

It is worth noting that the robot can sometimes close trades at a loss, therefore, on the PNL (Profit and Loss) chart, you can sometimes see short-term drawdowns, for example: October 6 -5.5%, October 17 -15%.
This is fine, as the overall portfolio size is going up!

<img src="/images/pnl-october.png" alt="October PNL" style="object-fit: cover; max-width:100%; height:388px;"/>

More information about the robot can be found in the [FAQ](#frequently-asked-questions-1) section.

## How to start using HitroBot

In order for HitroBot to start trading for you, you will need:
- an account in the [Telegram messenger](https://telegram.org)
- an account on the [Binance exchange](https://accounts.binance.com/en/register?ref=N587Q7WB) (registration instructions are [below](#binance-registration-and-account-setup-1))
- at least $1,000.00 in your account

So, the instructions for connecting to HitroBot:
1. Go to [@hitro_crypto_bot](https://t.me/hitro_crypto_bot) Telegram-bot and press `Start`. You will control the robot through it.
2. The bot will ask you to send an invitation code, send your invite that you received from a friend.
3. Log in or register with Binance ([instructions](#binance-registration-and-account-setup-1)).
4. The bot will ask you to send API Keys for trading for your Binance account. Set up the API Keys ([instructions](#api-keys-setup)) and send API Key first, then API Secret to the bot.
5. Fund your Futures account on Binance ([instructions](#how-to-deposit-and-withdraw-funds-1)).
6. In the bot menu press `Activate the robot`. It will validate given API keys. If the bot returned an error, check if the keys were set up correctly. You can also try creating the API keys again and update them with `Update API keys` button in the bot menu.
7. **Done! Now the robot trades and earns money for you!**
8. You can control the robot and view statistics through the Telegram-bot menu ([more details](#using-telegram-bot-1)).

> Note:
> - You should not close positions opened by the robot, this may interfere with the algorithm.
> - Positions in the futures account opened not by the robot will be closed to ensure the integrity of trading.


## Binance registration and account setup

To register with Binance:
1. Go through the [promo code link](https://accounts.binance.com/en/register?ref=N587Q7WB) that gives *-10%* commission discount.
2. Then the usual: register with your [email](https://www.binance.com/en/support/faq/115003764911) or a [phone number](https://www.binance.com/en/support/faq/718f25947c2c4cf2ab0b28ca411e682a).
3. To remove the account limits, as well as to be able to create API keys that the robot will need, [complete the Identity Verification](https://www.binance.com/en/support/faq/360027287111). You will need to send a scan of your ID document.
4. Then [open the Futures USDⓈ-M account](https://www.binance.com/en/support/faq/360033772992), which the bot will use to trade.

The registration and account setup are complete! Now you can move on to configuring API access.

### API Keys setup

5. Create an API key with any name following the [instructions](https://www.binance.com/en/support/faq/360002502072).
6. Press "Edit restrictions" and set "Enable Futures" — the access to trade in Futures account. It should look like this:
<img src="/images/api-restrictions.png" alt="API restrictions" height="400"/>

Done! Now you can send API Key and API Secret to the Telegram-bot.  
The robot will not have permission to withdraw funds, you don't have to worry about that.


## Using Telegram-bot

The trading robot is controlled via the Telegram-bot [@hitro_crypto_bot](https://t.me/hitro_crypto_bot).
After [account activation in the bot](#как-подключиться-к-hitrobot-1) you'll be able to:
- View status and statistics of trades in various time intervals.
- Suspend/resume the robot.
- Update API keys if necessary.

<img src="/images/telegram-bot.png" alt="Telegram-bot" height="520"/>

Menu appears when you send any message in the chat, just in case.


## How to deposit and withdraw funds

There are two types of accounts that you should know about:
- "Fiat and Spot" — main account that can be funded with cash/crypto, you can buy and hold crypto there and withdraw funds from it.
- "Futures" — an account, the main purpose of which is speculative trading. This account is used by the robot to trade.

You can easily transfer funds between these accounts. HitroBot uses only *Futures USDⓈ-M* account and doesn't touch other accounts at all.

### Deposit

There are millions of ways to top up the main account. But each of them is charged a fee.

Probably, [card depositing with Euro](https://www.binance.com/en/support/faq/a6f4eb39c27347109b5091dfee3ec96a) is the simplest, fastest and cheapest method.

1. So, fund your account using one of the available methods, for example:
   - [card deposit](https://www.binance.com/en/support/faq/a6f4eb39c27347109b5091dfee3ec96a)
   - [P2P deposit](https://www.binance.com/en/support/faq/360043832851)
2. Convert fiat currency into USDT: *Trade -> Convert (or Classic)*.
3. Transfer USDT from the Spot account to the Futures USDⓈ-M account for the robot to start trading.

### Withdraw

For withdrawal you need to perform basically the same order of actions as with depositing but in reverse.

1. Firstly, transfer funds from Futures account to Spot wallet.
2. Convert USDT to fiat currency: *Trade -> Convert (or Classic)*.
3. Then: *Withdraw -> Withdraw Fiat*. Or you can [try P2P](https://www.binance.com/en/support/faq/360041106311) for withdrawals.


## HitroBot commission

Users of HitroBot pay a commission — a fixed percentage **of the profits**.
The percentage is tied to the specific invitation that you joined HitroBot with.
The robot will calculate the commission size for you and send via Telegram all the information including wallet adresses for transfer.

There is a Binance [example on how to withdraw funds to another wallet](https://www.binance.com/en/support/faq/115003670492).
It is more profitable to use the BEP20 and BEP2 networks for transfers, since they are commission-free.

The commission is charged according to the schedule starting since enabling the robot:
- after next **3 days**
- after next **week**
- every **2 weeks** from now on

For instance, a user connected to HitroBot on 1st of October 2021, then the commission will be charged on October 4, then October 11, then October 25, November 8 and so on.

The commission is charged only on the profit since the moment of either topping up the account or the last commission was charged.
That means if the robot closes a period of time at a loss, it continues to trade without fees until the size of the portfolio reaches the last maximum.

> Example: For ease of calculation let's take the commission percentage 50%.  
> The robot gained from $10,000 to $12,000 in two weeks. The profit is `$12,000 - $10,000 = $2,000`.  
> Then the commission would be `$2,000 * 50% / 100 = $1,000`, the account is left with $11,000.  
> Over the next two weeks the robot loses $500.
> Since the profit is negative, the commission is not charged, the robot continues to trade.  
> Over the next two weeks the robot earns $1,500. Taking into account the losses of the previous two weeks, the total profit is `$1,500 - $500 = $1,000`.  
> The commission would be `$1,000 * 50% / 100 = $500`, and the account is left with $11,500.

The transaction should be made from your Binance account which is connected to HitroBot.
In this case it will understand that this account is yours.
When the robot receives money the Telegram-bot will notify you about that.

> Advice: When sending funds for the first time, it is possible to send a few dollars first, wait for confirmation from the bot for a few minutes and then send the rest.  
> This way, in case of an error in the wallet address or other parameters only a small fraction of the funds will be lost.

You have one to three days to pay the commission after the charge.
If the commission is not paid, the robot will be suspended.


## How to invite friends

All HitroBot users are able to share this opportunity to earn crypto with friends.

To do it press the `Invite friends` button in the Telegram-bot menu (if there is no such button, send any message to the bot, it will update the menu).
The bot will reply with your individual invitation code which can be used by your friends to join HitroBot.
Send your friend the invite and a [link](https://bit.ly/hitro-bot-docs) with instructions on how to join.

As a bonus **10%** of your friends' commission will be rebated to you.  
The bot will calculate the rebate amount and:
- notify you about it in a message
- deduct it from the next commission


## Binance restrictions

HitroBot can manage only a limited number of accounts due to some Binance restrictions on the number of API calls and orders per minute.
Currently the maximum number of users is **200**.

When the number of active users exceeds the maximum, users with larger balance of the Futures USDⓈ-M account have the priority.
In other words, all accounts are sorted in descending order of the account balance, and the robot manages the first 200.

The Telegram-bot will notify you about possible displacement from the top-200.
If the user is not in the top, the robot will be suspended for his account.


## Frequently asked questions

**Question:** Can the robot withdraw my funds?  
**Answer:** No, because it doesn't have API permissions to do that. When you set up API access, you only give permission to trade futures.

**Q:** How does the robot work?  
**A:** It trades futures using a smart strategy that was developed and tested for over six months. It buys low and sells high, simple :)

**Q:** Does the robot use leverage?  
**A:** Yes, for one trade the robot can use a margin of 1X to 3X. It is safe because the program strictly controls the stop-loss and does not let the price fall below the formula value.

Still have questions? Message me, [@hitro_dev](https://t.me/hitro_dev).


## Terms and Conditions

Can be found [here](/terms_and_conditions.md).
