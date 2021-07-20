![Casino bot](https://media.giphy.com/media/oqZVCd0xI7mBXYJMES/giphy.gif)

![LICENSE](https://img.shields.io/github/license/Animatea/casino-bot-for-discord)
![STARS](https://img.shields.io/github/stars/Animatea/casino-bot-for-discord)
![FORKS](https://img.shields.io/github/forks/Animatea/casino-bot-for-discord)
![LAST COMMIT](https://img.shields.io/github/last-commit/Animatea/casino-bot-for-discord)
![RELEASE DATE](https://img.shields.io/github/release-date/Animatea/casino-bot-for-discord)
![ALL CONTRIBUTORS](https://img.shields.io/github/contributors/Animatea/casino-bot-for-discord)
![COMMITS](https://img.shields.io/github/issues/Animatea/casino-bot-for-discord)
![Python3.8+](https://img.shields.io/badge/python-3.8+-blue.svg)
![DiscordPy](https://img.shields.io/badge/discord.py-1.7+-blue.svg)

# **Installation**
* **Requirements:** discord.py, python-dotenv

* **Note:** `[]` - optional, `<>` - required

#### 1. Cloning repository
```bash
$ git clone https://github.com/Animatea/casino-bot-for-discord.git
```
#### 2. Env manipulation
Rename `.env.example` to `.env` and paste here your bot token.
```bash
# .env file
token=YourBotToken
```
#### 3. Requirements
###### Using venv:
```bash
$ cd path/to/folder_with_requirements.txt
$ source <venv>/bin/activate
$ pip3 install -r requirements.txt
```
###### Without venv:
```bash
$ pip3 install -r requirements.txt
```
#### 4. Start the bot
###### Flags:
| flag         | type  |  defaultv  |                description              |
|:-------------|:-----:|:----------:|:---------------------------------------:|
|`--mypy_debug`| bool  | False      | Mypy check for all `.py` files in project |

```bash
$ cd path_to_repo/casino discord bot/src
$ python3 -m src [**flags]
```
#### 5. Bot commands
| qualname      |                usage                |                description                                        |
|:-------------|:-----------------------------------:|:-----------------------------------------------------------------:|
| `casino`     | `.casino <bet> [num_of_games=1]`      |Casino, generates lines with sectors depending on <number of games> (last argument, default: 1). |
