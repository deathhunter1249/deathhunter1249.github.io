```markdown
# DPRT Verification Bot

A Discord bot that verifies Roblox accounts for the Democratic People's Republic of Teapots (DPRT) using Roblox OAuth 2.0.

## How It Works

1. A user runs `/verify` in the Discord server.
2. The bot sends them a secure Roblox OAuth link.
3. The user logs in and authorizes with their Roblox account.
4. The bot checks that they are a member of both required Roblox groups.
5. If everything checks out, their Discord roles are updated automatically.

## Commands

| Command | Description |
|---|---|
| `/verify` | Link your Roblox account to the server |
| `/unverify` | Unlink your Roblox account from the server |
| `/update` | Re-check your Roblox group membership and sync your roles |

## Safety

This bot uses Roblox's official OAuth 2.0 system. It only reads your basic profile information (username and ID). It cannot access your password, inventory, Robux, or any other account data. For more information see the [Roblox OAuth2 documentation](https://create.roblox.com/docs/cloud/auth/oauth2-overview).

## How Role Sync Works

When `/update` is run the bot checks that you are still a member of both required Roblox groups. If you have left either group your roles will reflect that. If your roles are already up to date no changes will be made.

## Groups

- [Civ Group](https://www.roblox.com/communities/34683201/DPRT-Democratic-Peoples-Republic-of-Teapots#!/about)
- [Army Group](https://www.roblox.com/communities/34683309/DPRT-Handsome-Teapot-Army-of-the-DPRT#!/about)
```
