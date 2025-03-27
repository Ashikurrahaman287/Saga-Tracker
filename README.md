
# SAGA Tracker Bot

**SAGA Tracker** is a simple, interactive finance tracker bot made by **SAGA LAB**. It helps users manage their finances by tracking their expenses and income, setting budgets, and checking transaction history.

## Features

- **Record Transactions:** Easily track your expenses and income with `/Debt` and `/Credit`.
- **View Transaction History:** Check your past transactions for the last 7 days, 30 days, or just today.
- **Manage Budget:** Set a monthly budget and view your remaining balance.
- **Delete Transactions:** Remove your last recorded transaction if necessary.

## Available Commands

### 📥 `/Debt [amount] [description]`
Record an expense. For example:
```
/Debt 50 Grocery shopping
```

### 📤 `/Credit [amount] [description]`
Record income. For example:
```
/Credit 100 Salary
```

### 📊 `/Last7`
View all transactions from the last 7 days.

### 📈 `/Last30`
View all transactions from the last 30 days.

### 📅 `/Today`
View all transactions recorded today.

### ❌ `/Del`
Delete the last recorded transaction.

### 💰 `/Set_Budget [amount]`
Set a monthly budget to help you track your spending. For example:
```
/Set_Budget 1000
```

### 💼 `/Balance`
View your current balance, including total debt and credit.

## How to Use

1. Start by typing `/start` to interact with the bot.
2. Record your transactions using `/Debt` or `/Credit` commands.
3. Check your transaction history using `/Last7`, `/Last30`, or `/Today`.
4. Set a budget and track your remaining balance with `/Set_Budget` and `/Balance`.
5. If necessary, delete a transaction using `/Del`.

## Installation

To run this bot locally, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/your-repository-link
   cd your-repository-folder
   ```

2. Install dependencies:
   ```bash
   go get gopkg.in/tucnak/telebot.v2
   ```

3. Set up your Telegram bot token:
   - Create a bot on Telegram using [BotFather](https://core.telegram.org/bots#botfather).
   - Copy the bot token provided by BotFather and replace the `Token` in the code with your bot's token.

4. Run the bot:
   ```bash
   go run main.go
   ```

## License

This project is licensed under the MIT License.

## Credits

**Ashikur Rahman**  
Co-Founder & BackEnd Engineer at **SAGA LAB**

---
