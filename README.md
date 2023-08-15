# This is a test bot

## Steps:
1. Ensure `python3` & `pip`are installed. Then install the virtualenv python packange:
**Debian based distros:**
```sh
sudo apt install python3.10-venv
```

**Non-debian based distros:**
```py
python3 -m pip install --user virtualenv
```

2. Initialize the virtual environment:

```py
python3 -m venv env
```
3. Activate the virtual environment:

```sh
source env/bin/activate
```

4. Create a new file called `.env`& paste the bot token or execute the following command:

```sh
export BOT_TOKEN=your-bot-token-here
```

5. Execute the bot with this command:

```sh
python3 bot.py
```


------

*pd: to leave the virtual environment, execute:* `deactivate`.