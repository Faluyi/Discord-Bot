# Withdrawal Request Bot 🤖💵

A powerful and interactive Discord bot designed to streamline withdrawal request logging directly from Discord to Google Sheets. The bot leverages Discord's slash commands and interactive UI components (dropdowns, buttons) for a seamless user experience.

### Features 🚀

1. **Slash Command Integration**:
   - `/withdrawal`: Log withdrawal requests with ease, including the amount, book, and payment method.

2. **Interactive Book Selection**:
   - Paginated dropdowns allow users to select from a list of books (with over 40 options) for their withdrawal request.

3. **Payment Method Dropdown**:
   - Supports multiple payment methods such as Interac E-transfer, Crypto, Debit Card, PayPal, and more.

4. **Google Sheets Logging**:
   - Automatically logs withdrawal requests to a connected Google Sheet for tracking and management.

5. **Custom UI Views**:
   - Leverages Discord’s interactive UI components, such as dropdowns and buttons, for pagination and selection.

6. **Error Handling**:
   - Validates input data and provides clear feedback for errors (e.g., invalid amount or missing selection).

7. **Secure Configuration**:
   - Environment variables and Google Service Account credentials ensure secure and scalable deployment.

### Tech Stack 💻

- **Programming Language**: Python
- **Discord API**: Built with `discord.py` and `discord.ext.commands`
- **Google Sheets API**: Uses `gspread` for seamless integration with Google Sheets.
- **Environment Management**: `dotenv` for secure token and configuration handling.

### Use Cases 🌟

- Automating withdrawal request workflows in Discord communities.
- Providing seamless logging of financial transactions to Google Sheets.
- Improving operational efficiency in payout or financial tracking processes.

