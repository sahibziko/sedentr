# Seden UserBot <sub><sup><sub>_Feel my hands in your hair_</sup></sub></sub>
### Telegram Python Bot running on Python3 with a Postgresql Sqlalchemy database. It is a modular and easy-to-use bot.

![GitHub](https://img.shields.io/github/license/TeamDerUntergang/Telegram-SedenUserBot?color=red)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)

## Disclaimer
```python
# -*- coding: utf-8 -*-
"""
DISCLAIMER: 
The use of this Telegram bot is subject to the following terms:

- Your Telegram account may be banned due to misuse of the bot.
- The responsibility for any misuse of the bot lies entirely with the user.
- This bot is primarily maintained for facilitating efficient group management and for entertainment purposes.
- Engaging in spam activities within groups is strongly discouraged.
- If your account is banned due to spamming, any requests for assistance will not be entertained.
"""
```

## Run Bot
<details>
  <summary>Click to expand!</summary>

```bash
# Clone repo
git clone https://github.com/TeamDerUntergang/Telegram-SedenUserBot.git
cd Telegram-SedenUserBot

# Create and activate a virtual environment (you can change 'sedenify-venv' to your preferred name)
python3 -m venv sedenify-venv
source sedenify-venv/bin/activate

# Install Python dependencies
pip install -r requirements.txt

# Generate a session file if it doesn't exist
python3 session.py

# Create a configuration file and fill in the required variables
cp sample_config.env config.env
# Then fill in the necessary variables in config.env

# Run bot
python3 seden.py

```
### Nix/NixOS
To set up the bot in a Nix/NixOS environment, navigate to the bot folder and execute the `nix-shell` command.
</details>

## Q&A
If you have any requests, complaints, or suggestions, please feel free to reach out to us.

- Join our [support group](https://t.me/SedenUserBotSupport) for assistance.
- Submit a [GitHub issue](https://github.com/TeamDerUntergang/Telegram-SedenUserBot/issues) to report any problems or provide feedback.

For installation instructions, please visit our [GitHub.io](https://teamderuntergang.github.io/installation.html) page. We kindly request that you read the instructions carefully before asking questions, as questions that can be answered by following the instructions may not receive a response.

## Credits
<details>
  <summary>Click to expand!</summary>

*   [@naytseyd](https://github.com/naytseyd) - Founder
*   [@frknkrc44](https://github.com/frknkrc44) - Operator
*   [@Sedenogen](https://github.com/ciyanogen) - Co-Founder
*   [@Delivrance](https://github.com/pyrogram/pyrogram) - Pyrogram Library
*   [@Skittles9823](https://github.com/skittles9823) - Memes
*   [@RaphielGang](https://github.com/raphielgang) - Other Modules
*   [All Contributors](https://github.com/TeamDerUntergang/Telegram-SedenUserBot/graphs/contributors)
</details>

## License
This project is licensed under the [GNU Affero General Public License v3.0](https://www.gnu.org/licenses/agpl-3.0.html).