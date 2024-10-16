# Goats - Auto Claim Bot

🔗 **Referral Link**: [Goats](https://t.me/realgoats_bot/run?startapp=8565146f-2b4b-46f6-b8d0-d8531c6f82ca)

## 📢 Telegram Group

Join our Telegram group to stay updated and get instructions on how to use this tool:

- [Secretniy Channel](https://t.me/secretniy)
- [Secretniy Chat](https://t.me/+eTYhicQb1KczYTYy)

## 🌟 Features

| Feature        | Status | Description                                |
| -------------- | ------ | ------------------------------------------ |
| Mission Completion | On/Off | automatically watching ads |
| Auto Do Task   | On/Off | Completes available missions                             |
| Daily Check-in  | Auto ON | Checks in daily and collects rewards                      |
| Slot Machine |      On/Off     |        Spins the slot machine if coins are available          |
|Enable Proxies| On/Off       | To use proxies enable **Use Proxy** `ON` in the menu |



## ⛔ Attention!
If you have a **Python** version **lower than 3.7**, in the `bot.py` file replace 

`asyncio.run(main())`


with


`loop = asyncio.get_event_loop()`

`loop.run_until_complete(main())`


like this
![image](https://github.com/user-attachments/assets/930db2c0-0863-4e5d-9770-a0c3fc2e45e7)




## 🧑‍🔧 How to install in Linux
#Linux
```shell
apt install -y git python3 python3-pip
git clone https://github.com/secretniy/goats-bot.git
cd goats-bot/
python3 -m pip install -r requirements.txt --break-system-packages
```
Enter you (`query_id=... /user=...`) in file data.txt. Each new token from a new line.

How to find [query_id=... /user=..](https://t.me/secretniy)

To change a file in bash use the command `nano data.txt`

`ctrl+o` `enter` -  save file.

`ctrl+x` -  exit editor.


Modify the config.json file as desired.
```json
  {
      "sleep_before_start": 5,
      "account_delay": 5,
      "countdown_loop": 100
  } 
  ```
`sleep_before_start`: Delay before starting the first run

`account_delay`: Delay in seconds between switching accounts.

`countdown_loop`: Time in seconds to wait before running all accounts again.

To change a config file in bash use the command `nano config.json`

## 👩‍🔧 How to install in Windows
#Windows
1. Make sure you computer was installed python and git.
   
   python site : [https://python.org](https://python.org)
   
   git site : [https://git-scm.com/](https://git-scm.com/)

2. Clone this repository
   ```shell
   git clone https://github.com/secretniy/goats-bot.git
   ```

3. goto goats-bot directory
   ```
   cd goats-bot
   ```

4. install the require library
   ```
   python -m pip install -r requirements.txt
   ```

5. Edit `data.txt`, input you data token in `data.txt`, find you token in How to find [query_id=... /user=..](https://t.me/secretniy). One line for one data account, if you want add you second account add in new line!

6. execute the main program 
   ```
   python bot.py
   ```


## 🌎 About Proxy

Register on this site to get free proxy : [Here](https://t.me/secretniy)

You can add your proxy list in `proxies.txt` and proxy format is like example below :

Format :

```
http://host:port
http://user:pass@host:port
```

Example :

```
http://127.0.0.1:6969
http://user:pass@127.0.0.1:6969
socks5://127.0.0.1:6969
socks5://user:pass@127.0.0.1:6969
```

## 🚀 Run File

| Run                    | 
| -------------------------------- | 
| `python3 bot.py`          |  

## ⚠️ Note

- **Loading setup via CLI argument:** If the `--setup` argument is provided, the script will load the corresponding `.json` file and run the bot directly without displaying the menu.
- **Menu display:** If no `--setup` argument is provided, the script will display the menu as usual.
- **Setup saving:** The option to save setups has been included in the menu as option `8`.

