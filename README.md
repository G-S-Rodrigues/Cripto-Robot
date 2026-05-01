Here is the English version of your instructions, formatted in Markdown and ready to copy:

---

# Setup and Execution Guide

### 1. Install Dependencies
Open your terminal (**Ctrl + J**) and run the following command:
```bash
pip install -r requirements.txt
```

### 2. Configure API Keys
Insert your Binance keys into the `.env` file.
> 🟡 **IMPORTANT:** The keys must be enclosed in double quotes (e.g., `API_KEY="your_key_here"`).

### 3. Set the VS Code Interpreter
1. Press **Ctrl + Shift + P**.
2. Type **"Select Interpreter"** and select it.
3. Choose the **Python -> "Base" (Conda)** environment.
> 🟡 **IMPORTANT:** After selecting the interpreter, click the **TRASH CAN** icon in the terminal panel to close the current session, then open a new terminal.

### 4. Configure the Bot
All variables and bot settings are managed within the following file:
`.\src\main.py`

### 5. Run the Bot
To start the bot, enter the following command in the terminal:
```bash
python -m src.main
```

### 6. Run Backtests
To perform backtesting, enter the following command in the terminal:
```bash
python -m src.backtests
```
