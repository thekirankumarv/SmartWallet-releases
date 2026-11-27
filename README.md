<div align="center">

<img src="screenshots/icon.png" width="96" alt="SmartWallet icon" />

# SmartWallet

**Track every rupee in seconds. Tap, speak, scan a bill, or let your bank SMS do it.**

An offline-first money manager for Android. Expenses, budgets, accounts, credit cards and loans, all stored on your phone. No sign-up, no ads, no server.

![Platform](https://img.shields.io/badge/Android-7.0%2B-3DDC84?logo=android&logoColor=white)
![Price](https://img.shields.io/badge/price-free-8B7CFF)
![Ads](https://img.shields.io/badge/ads-none-2FD9A0)
![Data](https://img.shields.io/badge/data-on_your_phone-FFB547)

### [⬇ Download the latest APK](https://github.com/thekirankumarv/SmartWallet-releases/releases/latest)

</div>

<p align="center">
  <img src="screenshots/01-home.png" width="200" alt="Home" />
  <img src="screenshots/06-ask-answer.png" width="200" alt="Ask SmartWallet" />
  <img src="screenshots/13-bank-sms.png" width="200" alt="Bank SMS suggestions" />
  <img src="screenshots/11-scan-review.png" width="200" alt="Bill scan" />
</p>

## Contents

- [Install](#install)
- [Features](#features)
- [Screenshots](#screenshots)
- [Set up voice and bill scanning](#set-up-voice-and-bill-scanning)
- [Privacy](#privacy)
- [Updates](#updates)
- [FAQ](#faq)

## Install

1. Open the [latest release](https://github.com/thekirankumarv/SmartWallet-releases/releases/latest) on your Android phone.
2. Download `SmartWallet-vX.Y.Z.apk` from **Assets**.
3. Open it. If Android asks, allow **Install unknown apps** for your browser or file manager.
4. Open SmartWallet and add your first account.

Needs Android 7.0 or newer on a 64-bit (arm64) phone, which covers almost every phone from the last several years.

If **Play Protect** says *App blocked to protect your device* (it checks apps that can read SMS), open **Play Store → profile → Play Protect → ⚙ → turn off Scan apps with Play Protect**, install SmartWallet, then turn it back on. SMS are only read if you turn on bank SMS in Settings, and never leave your phone.

## Features

### 🏠 Home
- Net worth, what you saved this month, and spending against your monthly budget
- **Month-end forecast** and **safe to spend per day**, worked out from your own pace
- **Financial health score** (savings rate, emergency buffer, debt load, budgets) with the one thing to improve
- **Smart insights:** unusual spends, categories running hot, subscriptions you may have forgotten
- **Recurring payments** spotted automatically, with one tap to turn them into reminders
- Coming up: bills and EMIs due in the next two weeks
- **Unusual spending:** an expense far above your usual, likely duplicate charges, and subscription price rises
- **Year in review** in December and January: your year's totals, top categories, biggest expense, favourite shop and no-spend days

### ✨ Ask SmartWallet
- Tap the glowing orb in the middle of the bottom bar, then type or **speak** your question in plain words
- **Several things at once:** *"milk and curd"*, *"dairy and petrol"*, *"milk vs curd"*
- **Follow-ups:** *"food this month"* → *"and last month?"* → *"only swiggy"*
- **Patterns:** *"which weekday do I spend most"*, *"average daily spend on food"*, *"how many times swiggy"*, *"top 5 shops"*
- **Entries:** *"what did I buy yesterday"*, *"last time I bought curd"*
- **Why and what-if:** *"why did I spend more this month"*, *"if I cut food by 20%"*, *"save 1 lakh by March"*, *"when can I afford a 50k phone"*
- **Never guesses:** if it doesn't recognise a word, it tells you instead of showing wrong numbers
- Answers are worked out **on your phone** from your own entries, so they always match Home and Stats; the AI never does the maths
- Type *"petrol 205"* or *"spent 250 on swiggy"* to add an entry
- Only when your phone can't understand a question (and a Gemini key is set), the question text and your category, tag and account names go to Gemini to work out what you meant. It remembers those on your phone, so next time they work offline

### 💬 Bank SMS (Android)
- Reads bank, card and UPI SMS **on your phone** and suggests entries: amount, account, shop and a category learned from your past entries
- Nothing is saved until you tap ✓ or edit it; skipped SMS never come back
- Ignores OTPs, balance alerts, bill reminders, payment requests, failed payments and offers
- The bank SMS and the UPI app SMS for one payment show once; money moved between your own accounts becomes one transfer; payments you already entered aren't suggested again
- Asks once which account a new card or account number belongs to; change it any time under **Account numbers**
- **Skip all** clears a long list after asking you to confirm
- **Instant alerts (optional):** a notification like *"₹386 spent"* the moment the SMS arrives; tap it to review. The lock screen shows only "New bank SMS"

### 🔒 App lock
- Fingerprint, face or your phone's screen lock to open SmartWallet
- Locks when you open the app and after you've been away for more than a minute
- Your phone does the check; SmartWallet never sees your fingerprint or PIN

### ✍️ Transactions
- Expense, income and transfer, with a built-in calculator keypad (`40+7`, `2×120`)
- Two taps to categorise: category, then subcategory (**Dairy → Milk**)
- Today / Yesterday chips, or any date and time
- **+ Next** to log several items in a row
- Notes and colour-coded **tags** for shops, trips or festivals (`#SPAR`, `#Goa trip`, `#Diwali`)
- **Shop memory:** type a note like "dmart" and the category you usually pick for it is filled in
- **Hold to peek:** hold any entry to see its details without opening it
- Swipe between months; entries grouped by day with daily totals

### 🎙️ Voice entry
- Hold the mic, speak, let go. Light runs around the guide card and colour glow rises from the bottom of the screen as you talk
- The popup shows what to say and in which order: category, subcategory, amount, date, account, then a note and tag if you like
- Say several entries in one go: *"Dairy, milk, 47, today, from cash. Vehicle, fuel, 205, yesterday, from card"*
- Understands "yesterday", "last Friday", "on the 5th", and matches your own accounts, categories and tags
- You check every entry before it's saved

### 🧾 Bill scanning
- Photograph a supermarket bill, pick one from the gallery, or choose a PDF
- The camera finds the bill's edges and crops it, up to 5 photos for long bills
- The AI reads every line: **each item becomes its own expense** with the right category
- Fix anything, pick the date, account and tag, then save all items in one tap
- **Scanned bills** keeps each bill with its photo and items, and warns when the items don't add up to the bill total

### 📊 Stats & budgets
- Monthly and yearly income, expense and savings
- Pie chart by category; tap one to see its subcategories and which account paid
- Monthly budget per category with progress bars (green → amber → red), and a **notification at 80% and 100%**
- **Net worth over time:** a 12-month chart of what you own minus what you owe
- Month-by-month bars for the year
- Spend per tag; tap a tag to see its transactions

### 🏦 Accounts
- Bank, cash, wallet, credit card, fixed deposit and loan, plus your own types (gold, stocks…)
- Live balances, net worth, and assets vs liabilities, each account type in its own neon colour
- **Net worth = assets − owed.** Assets are your bank, cash, wallet, FD and other balances; owed is what's left on loans and unpaid card bills. Card limits never count
- Transfers between accounts, which never count as spending
- Fix a wrong balance two ways: correct the opening amount, or add a dated adjustment entry, so history is never lost

### 💳 Credit cards
- Limit, outstanding, available credit, utilisation, statement day and due day
- Regular or FD-backed cards
- **Pay bill** is a transfer from your bank, so the bill isn't counted as spending twice
- Spending past the available credit is blocked

### 🏠 Loans
- Outstanding amount, % repaid and expected payoff month
- **Pay EMI** in one tap; interest is added each month automatically (reducing balance)
- Reports show EMI and interest separately
- **Pay-extra planner:** see how many months earlier a loan closes and the interest you save by paying a little more each month

### ⏰ Payment reminders
- Rent, bills, card dues, EMIs, insurance: repeat every few days, weeks, months or years
- Notifications before the due date and on the day
- **Pay** opens a pre-filled entry; saving marks the reminder paid
- Overdue payments show as a banner on the home screen

### 📲 Widget & shortcuts
- **Home-screen widget:** safe to spend today and spent this month, with a + button to add an entry
- **App icon shortcuts:** long-press the icon for Add expense, Ask or Scan bill
- Slide along the bottom bar to switch tabs

### 🙈 Hide amounts
- **Eye button** hides every balance and total when someone can see your screen; tap one to peek for 3 seconds
- Option to always start with amounts hidden, and App lock on top

### 🔎 Search
- Search notes, categories, accounts, tags and amounts
- Filter by date range, type, account, category and tags

### 💾 Backup & data
- **Automatic backup** to a folder you pick, after every change and when you leave the app: the latest copy plus one per day for a week. The folder stays when the app is uninstalled
- **Google Drive sync (optional):** one sign-in, then a copy goes to a hidden SmartWallet folder in your Drive
- **Android's Google backup** also covers your data and display settings; your Gemini key is never included
- **Restore from backup** right on the home screen after a reinstall, or from Settings → Backup
- **PDF statements** for any week, month, year or dates you pick, for all accounts or one. Share or print
- Export to CSV for spreadsheets; import CSV from other apps, with duplicate detection
- Every delete asks first

### 🗂️ Categories & tags
- A ready-made set of categories (Dairy, Groceries, Bills & Utilities, Vehicle…)
- Add, rename, hide or delete categories and subcategories
- Tags with your own colours; rename, merge or delete them

### ✨ And more
- **Help & FAQ** built in, with search
- **In-app updates:** a popup when a new version is out, installed in a couple of taps
- **Send feedback** straight from Settings
- **40 currencies** (Settings → Currency): ₹ with the Indian number format by default, $, €, £, AED and more
- Dark theme, haptic feedback

## Screenshots

### Home & Ask SmartWallet
<p>
  <img src="screenshots/01-home.png" width="200" alt="Home" />
  <img src="screenshots/05-ask.png" width="200" alt="Ask SmartWallet" />
  <img src="screenshots/06-ask-answer.png" width="200" alt="Ask SmartWallet answer" />
  <img src="screenshots/16-home-bank-sms.png" width="200" alt="Bank SMS to review on Home" />
</p>

### Bank SMS & app lock
<p>
  <img src="screenshots/13-bank-sms.png" width="200" alt="Bank SMS suggestions" />
  <img src="screenshots/14-bank-sms-accounts.png" width="200" alt="Which account is this" />
  <img src="screenshots/15-bank-sms-alert.png" width="200" alt="Instant alert" />
  <img src="screenshots/17-app-lock.png" width="200" alt="App lock" />
</p>

### Transactions
<p>
  <img src="screenshots/02-transactions.png" width="200" alt="Transactions" />
  <img src="screenshots/03-add-transaction.png" width="200" alt="Add transaction" />
  <img src="screenshots/04-hold-to-peek.png" width="200" alt="Hold to peek" />
  <img src="screenshots/29-search.png" width="200" alt="Search" />
</p>

### Voice entry
<p>
  <img src="screenshots/07-voice-guide.png" width="200" alt="Voice guide while recording" />
  <img src="screenshots/08-voice-review.png" width="200" alt="Check voice entries" />
  <img src="screenshots/33-voice-settings.png" width="200" alt="Voice settings" />
</p>

### Bill scanning
<p>
  <img src="screenshots/09-scan-bill.png" width="200" alt="Scan bill" />
  <img src="screenshots/10-scanning.png" width="200" alt="Reading the bill" />
  <img src="screenshots/11-scan-review.png" width="200" alt="Bill items" />
  <img src="screenshots/12-scanned-bills.png" width="200" alt="Scanned bills" />
</p>

### Stats & budgets
<p>
  <img src="screenshots/18-stats.png" width="200" alt="Monthly stats" />
  <img src="screenshots/19-stats-categories.png" width="200" alt="Categories, tags and budgets" />
  <img src="screenshots/20-stats-yearly.png" width="200" alt="Yearly stats" />
  <img src="screenshots/21-stats-breakdown.png" width="200" alt="Yearly breakdown" />
</p>
<p>
  <img src="screenshots/22-budgets.png" width="200" alt="Category budgets" />
  <img src="screenshots/42-net-worth.png" width="200" alt="Net worth over 12 months" />
  <img src="screenshots/43-year-review.png" width="200" alt="Year in review" />
</p>

### Accounts, cards & loans
<p>
  <img src="screenshots/23-accounts.png" width="200" alt="Accounts" />
  <img src="screenshots/24-credit-cards.png" width="200" alt="Credit cards" />
  <img src="screenshots/25-loans.png" width="200" alt="Loans and pay-extra planner" />
  <img src="screenshots/26-account-history.png" width="200" alt="Account history" />
</p>

### Reminders, tags & privacy
<p>
  <img src="screenshots/27-reminders.png" width="200" alt="Payment reminders" />
  <img src="screenshots/28-tags.png" width="200" alt="Tags" />
  <img src="screenshots/30-hidden-amounts.png" width="200" alt="Hidden amounts" />
  <img src="screenshots/32-privacy-backup.png" width="200" alt="Privacy and backup settings" />
</p>

### Settings, help & updates
<p>
  <img src="screenshots/31-settings.png" width="200" alt="Settings" />
  <img src="screenshots/34-help.png" width="200" alt="Help & FAQ" />
  <img src="screenshots/35-update.png" width="200" alt="Update available" />
  <img src="screenshots/41-first-run.png" width="200" alt="First run" />
</p>

### Backup, statements & currency
<p>
  <img src="screenshots/40-restore.png" width="200" alt="Restore from backup" />
  <img src="screenshots/38-statement.png" width="200" alt="PDF statement" />
  <img src="screenshots/39-balance-choice.png" width="200" alt="Fix a balance" />
  <img src="screenshots/36-currency.png" width="200" alt="Pick a currency" />
</p>
<p>
  <img src="screenshots/37-home-usd.png" width="200" alt="Home in US dollars" />
</p>

<sub>Screenshots use sample data.</sub>

## Set up voice and bill scanning

Voice entry and bill scanning use Google Gemini with **your own free API key**. Everything else works without it.

1. Open [Google AI Studio](https://aistudio.google.com/apikey) and sign in with your Google account.
2. Tap **Create API key** and copy it.
3. In SmartWallet go to **Settings → Voice entry**, paste the key and tap **Check & save**.

The free tier is plenty for personal use and needs no card. The key is stored encrypted on your phone and is never part of backups.

## Privacy

- All your data lives in one file **on your phone**. There's no account, no server and no analytics.
- Voice clips and bill photos go to Google Gemini **only when you use those features**, together with your account, category and tag names so it can match them. Balances and past transactions never leave your phone.
- **Ask SmartWallet** answers on your phone. Only a question it can't understand goes to Gemini (if you've set a key), as the question text plus your category, tag and account names; amounts and entries never do. Spoken questions use Android's own speech service.
- **Bank SMS** are read on your phone only, when you turn it on, and are never uploaded or sent to Gemini. Message text isn't stored or backed up.
- **App lock** uses Android's own fingerprint and face prompt. SmartWallet never sees your fingerprint or PIN.
- Backups go only where you choose: your backup folder, Android's Google backup, and (if you connect it) a hidden SmartWallet folder in your own Google Drive that the app can't see beyond.
- Full [privacy policy](https://smartwalletapp.vercel.app/privacy/).

## Updates

SmartWallet checks this page for new versions and shows a popup with what's new. Tap **Update now**, or update later from **Settings → App updates**. Your data stays as it is. Every version is also listed under [Releases](https://github.com/thekirankumarv/SmartWallet-releases/releases).

## FAQ

<details>
<summary><b>Is it really free?</b></summary>

Yes. No ads, no subscriptions, no in-app purchases. If you'd like to say thanks, there's a **Support the developer** option in Settings.
</details>

<details>
<summary><b>Why isn't it on the Play Store?</b></summary>

It's distributed here on GitHub, so Android asks once for permission to install it. In-app updates are downloaded from this page and their checksum is verified before installing.
</details>

<details>
<summary><b>How do I move to a new phone?</b></summary>

Keep a copy off the old phone: connect **Google Drive** in **Settings → Backup**, turn on Android's Google backup, or sync your backup folder to Drive. On the new phone install SmartWallet and tap **Restore from backup** on the home screen. Add your Gemini key again, since keys aren't stored in backups.
</details>

<details>
<summary><b>Will I lose my data if I uninstall?</b></summary>

Not if a backup folder is chosen in **Settings → Backup**. SmartWallet saves to it after every change, and the folder stays when the app is removed. Reinstall, tap **Restore from backup** and pick the same folder.
</details>

<details>
<summary><b>Can I bring data from another app?</b></summary>

Yes. **Settings → Import CSV** reads any file with `Date`, `Account`, `Type` and `Amount` columns. Accounts and categories are matched by name or created, and duplicates are skipped.

```csv
Date,Time,Type,Account,To Account,Category,Subcategory,Note,Amount,Tags
2026-10-24,08:15,Expense,HDFC Bank,,Dairy,Milk,,56,"milk, swiggy instamart"
2026-10-01,,Income,HDFC Bank,,Salary,,,85000,
2026-10-05,,Transfer,HDFC Bank,Home Loan,,,,21500,
```
</details>

<details>
<summary><b>Can SmartWallet add entries from my bank SMS?</b></summary>

Yes. Turn on **Settings → Privacy → Suggest from bank SMS**. Each time you open the app it reads bank, card and UPI SMS from the last 30 days and shows them on Home as *bank SMS to review*. Nothing is saved until you tap ✓ or edit it. OTPs, balance alerts, bill reminders, failed payments and offers are ignored, and a payment reported by both your bank and your UPI app shows once. Turn on **Alert on new bank SMS** to get a notification the moment one arrives. SMS never leave your phone.
</details>

<details>
<summary><b>How does Ask SmartWallet work?</b></summary>

Your phone reads the question and matches each word to your categories, subcategories, tags, accounts, entry notes and dates. If it understood every word, it works out the answer on your phone, with no internet. If a word is unclear and you've added a Gemini key, only the question text and your category, tag and account names go to Gemini to work out what you meant; the numbers are still calculated on your phone. If it still can't tell, it says what it didn't understand instead of guessing. It can only find what's in your data, so add shop or item names as notes when you log entries.
</details>

<details>
<summary><b>What is net worth, and what are assets and owed?</b></summary>

**Net worth = assets − owed.** Assets are the balances of your bank, cash, wallet, fixed deposit and your own account types like gold. Owed (liabilities) is what you still have to pay back: what's left on each loan and the unpaid amount on each credit card. Your card limit never counts. Example: bank 80,000 + cash 5,000 + FD 50,000 = 1,35,000 assets; car loan 40,000 + card bill 15,000 = 55,000 owed; net worth = 80,000.
</details>

<details>
<summary><b>How do I add the home-screen widget?</b></summary>

Long-press an empty spot on your home screen → **Widgets** → SmartWallet, and drag it out. It shows how much is safe to spend today and what you've spent this month, with a + button to add an entry. It updates whenever you open the app or change an entry, and shows •••• when amounts are hidden.
</details>

<details>
<summary><b>Why does it ask for SMS permission?</b></summary>

Only for the bank SMS feature, and only when you turn it on. Android shows it as "send and view SMS messages", but SmartWallet only reads; it never sends a message. If the SMS permission is greyed out or says "restricted setting": open **App info → Permissions → SMS**, tap the greyed-out Allow and then OK. Go back to App info, tap **⋮ → Allow restricted settings** and confirm, then allow SMS.
</details>

<details>
<summary><b>Play Protect says the app is blocked. What do I do?</b></summary>

Google Play Protect blocks some apps installed outside the Play Store if they can read SMS, to stop OTP-stealing scams. SmartWallet asks for SMS only for the optional bank SMS feature and never sends anything off your phone. To install: **Play Store → your profile → Play Protect → ⚙ → turn off Scan apps with Play Protect**, install or update SmartWallet, then turn it back on.
</details>

<details>
<summary><b>Can I lock the app?</b></summary>

Yes. **Settings → Privacy → App lock** asks for your fingerprint, face or screen lock when SmartWallet opens and after you've been away for more than a minute. It needs a screen lock set up on your phone.
</details>

<details>
<summary><b>Does it work offline?</b></summary>

Everything except voice entry, bill scanning, update checks and the rare Ask question that needs Gemini works with no internet at all. Bank SMS suggestions, alerts and the widget work offline.
</details>

<details>
<summary><b>Found a bug or have an idea?</b></summary>

Use **Settings → Send feedback** in the app, or open an [issue](https://github.com/thekirankumarv/SmartWallet-releases/issues).
</details>
