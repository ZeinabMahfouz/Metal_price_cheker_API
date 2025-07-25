# 🪙 Metal Price Checker (GoldAPI)

This is a simple Python script that retrieves the current price of precious metals (Gold, Silver, Platinum, or Palladium) in a selected currency using the [GoldAPI](https://www.goldapi.io/) service.

## 🚀 Features

- Select a metal (e.g., Gold, Silver, etc.)
- Select a currency (e.g., USD, EUR, INR)
- Fetch real-time metal prices using GoldAPI
- Displays:
  - Metal name
  - Price
  - Date and time (UTC) of the price quote
- Handles invalid input gracefully

---

## 🖼️ Example Output

Available metals:

XAU: Gold

XAG: Silver

XPT: Platinum

XPD: Palladium

Enter the metal code (e.g., XAU): XAU
Common currency codes: USD, EUR, GBP, INR, JPY, etc.
Enter the currency code (e.g., USD): USD

📈 Current price of Gold in USD: 2418.13
🕒 Price time: 2025-07-25 14:30:00 UTC

yaml
Copy
Edit

---

## ⚙️ Requirements

- Python 3.x
- `requests` library

Install dependencies:

```bash
pip install requests
🔑 API Key Setup
You will need a free or paid API key from GoldAPI.io.

Sign up at https://www.goldapi.io/

Copy your API key

Replace the api_key variable in the script with your own:

python
Copy
Edit
api_key = "your-api-key-here"
🧠 Notes
The script includes validation for both metal codes and common currency codes.

Timestamp is displayed in UTC format.

Errors such as unsupported currencies or invalid API keys are handled gracefully.

🙌 Acknowledgements
GoldAPI for providing real-time precious metal pricing.
