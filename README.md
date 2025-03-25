# Nodepay BOT
Nodepay BOT

- Register Here : [Nodepay](https://app.nodepay.ai/register?ref=88pnjPEUkN9Dtxg)

## Features

  - Auto Get Account Information
  - Auto Run With [Monosans](https://raw.githubusercontent.com/monosans/proxy-list/main/proxies/all.txt) Proxy - Choose 1
  - Auto Run With Private Proxy - Choose 2
  - Auto Run Without Proxy - Choose 3
  - Auto Complete Available Tasks
  - Auto Send Ping Every 55 Minutes
  - Multi Accounts With Threads

Note: auto connects 3 connections if u using proxies and only 1 if not.

## Requirements 

- Make sure you have Python3.9 or higher installed and pip.

## Installation 

1. **Clone The Repositories:**
   ```bash
   git clone https://github.com/Not-D4rkcipherX/Nodepay-v2.git
   cd Nodepay-v2
   pip install -r requirements.txt #or pip3 install -r requirements.txt
   ```
   
## Configuration

Before running the bot, you need to set up your configuration:

### 1. `tokens.txt` (Required)

To get your Bearer token:

1. **Register for a Nodepay account**:
   - Go to [Nodepay Registration Page](https://app.nodepay.ai/register?ref=88pnjPEUkN9Dtxg) and sign up for an account.

2. **Get your token**:
   - Open **DevTools** in your browser (right-click > Inspect or press `Ctrl+Shift+I`).
   - Go to the **Console** tab in DevTools.
   - Type the following command to get your token:

     ```javascript
     localStorage.getItem('np_webapp_token')
     ```

   - This will return the Bearer token. **Copy the token** (without the `Bearer` prefix, just the alphanumeric string).


## Accounts Setup
```bash
nano tokens.txt
```
- Make sure `tokens.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    eyjxxxx1
    eyjxxxx2
  ```
  
## PROXY
```bash
nano proxy.txt
```
- Make sure `proxy.txt` contains data that matches the format expected by the script. Here are examples of file formats:
  ```bash
    ip:port # Default Protcol HTTP.
    protocol://ip:port
    protocol://user:pass@ip:port
  ```

## Run

```bash
python bot.py #or python3 bot.py
```

## Buy Me a Coffee

- **EVM:** 0x47f41Fcb17cF9B7A02C26EE855d26bB8D3928E1b
- **TON:** UQA-qG5eyQ7gVxvPDpy484xzc0UPS9a8hJsUAwe0T_3D7_oF
- **SOL:** A1pUv13rRDtubtYJuXswZYSQBJojPhthXJftfNZBRnEX
- **SUI:** 0xeb697918d66c4ade867d61d0b8fb541df83675e8f60b6b81da8917aab149ee8f

Thank you for visiting this repository, don't forget to contribute in the form of follows and stars.
If you have questions, find an issue, or have suggestions for improvement, feel free to contact me or open an *issue* in this GitHub repository.

**D4rkCipherX**
