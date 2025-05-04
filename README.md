## 🪙 Crypto Price Fetcher

A simple Python script that fetches real-time cryptocurrency prices using the [CoinGecko API](https://www.coingecko.com/en/api). The script allows you to retrieve the current price of a specified cryptocurrency in a given fiat currency.


### 📌 Features

* Fetches current price data from CoinGecko
* Supports multiple cryptocurrencies and currencies
* Handles API errors and connection issues gracefully
* Easy to customize and extend


### 🧰 Requirements

* Python 3.x
* `requests` library

Install dependencies using pip:

```bash
pip install requests
```

---

### 🚀 Usage

Run the script directly in your terminal or Python environment:

```bash
python crypto_price_fetcher.py
```

By default, it fetches the **Bitcoin** price in **USD**.

---

### 🔄 Customization

To fetch prices for a different cryptocurrency or currency, modify the function call:

```python
fetch_crypto_price("ethereum", "eur")
```

Supported examples:

```python
fetch_crypto_price("dogecoin", "zar")  # Dogecoin in South African Rand
fetch_crypto_price("cardano", "gbp")   # Cardano in British Pound
```

---

### ⚠️ Error Handling

The script handles:

* Invalid cryptocurrency/currency combinations
* Network errors or timeouts
* Unexpected API responses
* HTTP errors (e.g. 404, 500)

---

### 📁 Project Structure

```
crypto_price_fetcher.py
README.md
```

---

### ✅ Example Output


The current price of Bitcoin in USD is: 64235
```



