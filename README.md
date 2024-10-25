# Cats Dogs Bot


[![Join our Telegram](https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white)](https://t.me/MexicanbrScripts)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Mexicanbr)

## Registrations [https://t.me/catsdogs_game_bot/](https://t.me/catsdogs_game_bot/join?startapp=7862506317)


## Features

- **Multi-account Support:** Automate actions across multiple accounts.
- **Auto Complete Task** Automatically perform available quest
- **Configurable Settings:** Control various aspects of the script via a `config.json` file.
- **Using a proxy**
- **Static user agent**

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/Mexicanbr/Cats-Dogs-Bot.git
   cd CatsDogsCum
   
Create and activate a virtual environment:

   ```bash
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```
Install the required dependencies:

   ```bash
pip install -r requirements.txt
   ```

## Configuration
Create a config.json file in the root directory with the following structure:
   ```json
{
    "delay_account": [5, 10],
    "cycle_delay": [1000, 2000]
}
   ```

`delay_account`: Delay between processing different accounts (in seconds) - the minimum and maximum values are taken randomly

`cycle_delay`: Delay between different cycles of operations (in seconds) - the minimum and maximum values are taken randomly

## About Proxy


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
```

## How to get tgWebAppData (query_id / user_id)

1. Login telegram via portable or web version
2. Launch the bot
3. Press `F12` on the keyboard 
4. Open console
5. Сopy this code in Console for getting tgWebAppData (user= / query=):

```javascript
copy(Telegram.WebApp.initData)
```

6. you will get data that looks like this

```
query_id=AA....
user=%7B%22id%....
```
7. add it to `query.txt` file or create it if you dont have one


## This bot helpfull?  Please support me by buying me a coffee: 
``` 0x5e14f8333a49b888bc66068c18cde3ecc6f8b272 ``` - BSC (BEP 20)

``` EQCA1BI4QRZ8qYmskSRDzJmkucGodYRTZCf_b9hckjla6dZl ``` ``` Memo - 2084424251 ``` - TON

``` 0x5e14f8333a49b888bc66068c18cde3ecc6f8b272 ``` - Optimism

``` TDanbBakUT2dkQdzpkC7tCugMvd5eNGWnR ``` - TRX (TRC 20)

## License
This project is licensed under the MIT License - see the LICENSE file for details.

## Chanel
New scripts on the channel [MEXICANBR Chanel](https://t.me/MexicanbrScripts)
