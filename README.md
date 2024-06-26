# AI Bot
 > Discord bot to speak with my [CatAI](https://github.com/withcatai/catai) models.

## Table of contents
- [AI Bot](#ai-bot)
  - [Table of contents](#table-of-contents)
  - [Requirements](#requirements)
  - [Installation](#installation)
  - [Configuration](#configuration)
  - [License](#license)
  - [Contributing](#contributing)

## Requirements
- Discord Bot
- Python 3.8 or higher
- Selfhosted [CatAI](https://github.com/withcatai/catai) (powerful machines are recommended for better performance)

## Installation
1. Clone the repository
2. Install the requirements with the following command:
```bash
python -m pip install -r requirements.txt
```
3. Fill the `config.yaml` file with your the needed details, see [Configuration](#configuration) for more information.
4. Run the bot with the following command:
```bash
python main.py
```
5. Invite the bot to your server & sync the commands with the 2 following commands:
```
.sync
```
and
```
.sync YOUR_GUILD_ID
```
6. Enjoy!

## Configuration
Don't use quotes or double quotes in the values of the configuration file.
```yaml
# [APP]
app_logo: # String, URL to the app logo
app_name: # String, Name of the app
app_url: # String, URL to the app
app_version: # String, Version of the app
log_file: # String, Path to the log file (Example: ai_bot.log)

# [BOT]
bot_prefix: # String, Prefix for the bot
bot_token: # String, Token of the bot
chat_category: # String, Category ID for the chat channels to be created
dev_guild_id: # String, Guild ID for the development guild

# [AI]
api_endpoint: # String, URL to the CatAI selfhosted API (Example: http://127.0.0.1:3000/api/chat/prompt)
```

## License
This project is licensed under the GNU License - see the [LICENSE](LICENSE) file for details.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.