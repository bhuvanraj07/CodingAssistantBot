# howdoi-telegram

A telegram bot for accessing [gleitz/howdoi](https://github.com/gleitz/howdoi). Get instant coding answers. Telegram bot that answers your coding questions.

Get to the solution quickly without any distraction.

Take a look!

![demo-gif](images/howdoi_0.01.gif)

## How to run

You can run on any OS (windows/mac/linux). For better reliability, you may deploy to a VPS like Digital Ocean Droplet. You can even run on Android, using the Termux app.

Open your terminal and follow the instructions to run the bot.

- Make sure you have `git`, `python` and `pip`.

    ```bash
    # the following commands should not produce error
    git --version
    python --version # 3.9 is recommended
    pip --version
    ```

    > **Note:** In some systems `python` version 3 is availaible as `python3`

- First of all, clone the repository.

    ```shell
    git clone https://github.com/aahnik/howdoi-telegram.git
    ```

- Now, move into the `howdoi-telegram` directory.

    ```shell
    cd howdoi-telegram
    ```

- Create a python virtual enviroment.

    ```bash
    python -m venv .venv # create
    source .venv/bin/activate # activate (unix)
    # the command to activate virtual environment is different for Windows, google search
    ```

- Install the requirements.

    ```bash
    pip install -r requirements.txt
    ```

- Set `BOT_TOKEN` environment variable. Write the following into a file named `.env`.

    ```bash
    BOT_TOKEN=1234fsjksjfls23r4
    # use your own real token
    ```

    You can create a new bot and get token from [@BotFather](https://telegram.me/BotFather).

- Run the `do.py`, and you are good to go.

    ```shell
    python do.py
    ```

## Deploy to Heroku

You can click this button to deploy to Heroku.

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/bhuvanraj07/CodingAssistantBot)

For more details [read the guide](https://github.com/aahnik/howdoi-telegram/issues/6) about Heroku deployment.

<!-- deploy success -->

## Contributing

Issues and PRs welcome!
