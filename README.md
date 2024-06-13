# hikari-lightbulb-bot-template

A basic, extendable discord bot written using `hikari` and `hikari-lightbulb`.

Comes with two slash commands to demonstrate basic library functionality.

## Running the bot

Acquire a token for the bot from the [discord developer portal](https://discord.com/developers/docs/quick-start/getting-started#step-1-creating-an-app)
and put it in a plaintext file - `.token` - in the root of this directory.

> [!TIP]
> You can use the `TOKEN_FILE` environment variable to make the bot read the token from
> a different file. (only when **NOT** running using docker)

Install the requirements

```bash
pip install -r requirements.txt
```

Run using Python

```bash
python -m bot
```

## Additional features

- Dependabot configuration to assist in keeping dependencies up-to-date
- Docker configuration bootstrapped using `docker init`
  - Easily run the application with docker using `docker compose up`
  - Database container configuration included (but commented out) if you need it down the line
