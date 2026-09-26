# Bingo — Privacy Policy

*Last updated: 26 September 2026*

Bingo is a Discord bot. This policy explains what data it collects and why.

## What we collect

- **Discord user IDs and guild IDs** — stored as numeric identifiers only
- **Game data** — pet records, currency balances, voting streaks, cosmetic ownership, notification preferences
- **AFK status** — your away message, deleted when you return
- **Feedback and suggestions** — text you deliberately submit via `!feedback` or `!suggestion`
- **Command usage log** — a rolling record of commands used, for moderation and debugging
- Records of any cosmetic features granted to your account

## What we do not collect

Bingo reads message content only to operate its features. Almost always that means detecting and running a command. Two features necessarily read messages that are not commands: while you are marked away with !afk, Bingo checks messages for mentions of you so it can tell you who mentioned you, and clears your away status when you next speak; and while you have started !parrot, Bingo reads your own messages in that channel for up to five minutes in order to echo them back. Messages read for either purpose are processed in memory and are never stored, profiled, or analysed for anything else.. Bingo only processes a message when it begins with `!` or when you reply to a message while using a command.

We do not store usernames, avatars, roles, or member lists. We do not sell or share data with third parties.

## Third-party processing

- `!ask` sends your question to [Groq](https://groq.com) to generate a response. It is not retained afterwards and is not used for training.
- Vote rewards are verified against [Top.gg](https://top.gg) using your Discord user ID.

## Retention and deletion

Data is kept while you continue using the bot. Pet data is archived after 28 days of inactivity.

To delete your data, use `!deletedata` in any server with Bingo, or ask in the support server. Requests are actioned within 7 days.

Economy audit records are anonymised rather than deleted, as transaction totals must remain balanced. No identifying information is retained in them.

## Contact

Support server: [discord.gg/bHBkezNex7](https://discord.gg/bHBkezNex7)
