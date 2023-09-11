# SuapDiscord
Project with studying purpose

Made with [@darkratos](https://github.com/darkratos)

### Disclaimer

This project only works with SUAP (Sistema Unificado de Adminstração Pública), but it can be quite easy modified to work with other grade systems aswell

## What I learned
- Web Scraping
- Basic Web Reverse Engineering
- API usage

## Usage

### Create a discord app
Just follow the instructions on [discord developers](https://discord.com/developers/docs/getting-started#step-1-creating-an-app)

### Change Discord Json Config
```
{
    "token": # Bot token,
    "serverId": # Server ID (Enable Discord developer on app to see this),
    "channelNames": { # (Need Discord developer enabled too)
        "grades": # Server channel for grades,
        "absences": # Server channel for absences
    }
}
```

### Change Suap Json Config
```
{
    "user": # Your username,
    "pass": # Your password
}
```
