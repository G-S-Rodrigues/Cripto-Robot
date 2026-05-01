
# Setup and Execution Guide

### 1. Install Dependencies
Open your terminal and run the following command:
```bash
pip install -r requirements.txt
```

### 2. Configure API Keys
Insert your Binance keys into the `.env` file.
> 🟡 **IMPORTANT:** The keys must be enclosed in double quotes (e.g., `API_KEY="your_key_here"`).

### 3. Configure the Bot
All variables and bot settings are managed within the following file:
`.\src\main.py`

### 4. Run the Bot
To start the bot, enter the following command in the terminal:
```bash
python -m src.main
```

### 5. Run Backtests
To perform backtesting, enter the following command in the terminal:
```bash
python -m src.backtests
```
