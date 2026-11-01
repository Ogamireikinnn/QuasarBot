# Privacy Policy

Last updated: November 1, 2026

This policy explains what information QuasarBot ("the bot") collects, how it is used, and how long it is kept. By adding the bot to your server or using its commands, you agree to this policy.

## 1. Information the bot collects

**Server settings.** When a server admin runs `/setup`, `/welcome` commands, `/autoreact`, `/autoresponder`, or `/timezone`, the bot stores the chosen channel IDs, role IDs, the server's timezone, and the text of any welcome messages and auto-responders.

**Partnership records.** When an ad is posted in a configured ad channel, the bot stores the IDs of the mentioned users, the message ID, and the channel ID. It does not store the text of ads. The bot uses these records to assign and remove rep roles.

**Member IDs and moderation records.** The bot stores user IDs for moderation actions such as bans, kicks, trap-channel punishments, and join-and-leave (J2L) checks, along with the reason and timestamp.

**Ticket transcripts.** When a ticket is closed with `/close`, the bot saves a plain-text copy of the ticket's messages, including authors, timestamps, message text, and attachment links. The transcript is sent to the bot owner's private log channel.

**Poll votes.** When a broadcast poll is used, the bot stores the user ID and the option chosen.

**Usage data.** The bot may log errors and command names to help the developer fix problems. It does not log private message content outside of the ticket transcripts described above.

The bot does not read messages in channels it is not configured for, except to check for auto-responder triggers and auto-reactions in the channels where those are set.

## 2. How we use the information

We use this information only to run the bot's features: assigning roles, enforcing ad rules, moderating, sending welcome messages, sending setup reminders, running the daily ad scan, and handling support tickets.

We do not sell your information. We do not use it for advertising.

## 3. Direct messages

The bot sends direct messages in these cases only:
- To a server owner, when the server has not finished `/setup` (at most once every 3 days, and it stops if the owner presses **Stop**).
- To a server owner, with a support server invite or ticket link when they open a ticket.
- To a new member, only if a server admin has turned on the welcome DM option.
- To a server owner, when the bot cannot perform an action such as missing permissions.

## 4. Backups

The bot creates a daily backup of its database and sends it to the bot owner's private log channel. Backups contain the same information described in section 1.

## 5. How long we keep information

- Server settings are kept until the server removes the bot or runs `/setup` and presses **Reset Configuration**.
- Partnership records are removed when the ad is deleted, when the rep leaves the server, or when the server resets its settings.
- Moderation records are kept for as long as the bot needs them to enforce server rules.
- Ticket transcripts are kept in the owner log channel until the owner deletes them.
- Daily backups are kept in the owner log channel until the owner deletes them.

## 6. Sharing

Information is shared only:
- With Discord, as needed to run the bot.
- With the bot's hosting provider, which stores the database and runs the bot.
- If required by law.

## 7. Your choices

- **Server admins** can remove the bot, reset its settings with `/setup`, or delete individual ads and auto-responders.
- **Members** can ask a server admin to remove their ad records.
- **Anyone** can ask for their information to be deleted by contacting us through the support server listed below. We will delete records about you, except where we must keep them to follow the law or to protect the server.

## 8. Children

The bot is not intended for anyone under 13 years old, as required by Discord's terms of service.

## 9. Security

We take reasonable steps to protect stored information. No system is completely secure, so we cannot guarantee absolute security.

## 10. Changes to this policy

We may update this policy. The "Last updated" date at the top shows when it last changed. Continued use of the bot after an update means you accept the new policy.

## 11. Contact

For questions or deletion requests, join the support server: https://discord.gg/kXwAQRNq2d