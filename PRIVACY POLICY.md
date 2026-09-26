# Privacy Policy for QuasarBot

**Last Updated: September 27, 2026**

## 1. Introduction

This Privacy Policy explains how QuasarBot ("the Bot", "we", "our") collects, uses, and protects information when you use our Discord bot. By using QuasarBot, you agree to the data practices described in this policy.

## 2. Information We Collect

### 2.1 Automatically Collected Data
When you interact with QuasarBot, we automatically collect:
- **Discord User ID** - Used to identify your account for alliance and representative tracking
- **Discord Server (Guild) ID** - Used to store server-specific settings
- **Message IDs** - Used for advertisement tracking and cleanup when ads are deleted
- **Channel IDs** - Used for ad channel, log channel, welcome channel, and trap channel configuration
- **Role IDs** - Used for representative role and bypass role configuration
- **Command Usage** - Which commands you use for cooldown management

### 2.2 Data You Provide
- **Custom Prefixes** - Server administrators can set custom command prefixes
- **Auto Responder Triggers/Responses** - Configured by server administrators
- **Welcome Messages** - Custom welcome messages configured by server administrators
- **Server Configuration** - Ad categories, rep actions, bypass roles, and other settings

## 3. How We Use Your Information

We use collected data for:
- **Bot Functionality** - Alliance management, auto responders, welcome messages, and server management
- **Server Configuration** - Storing your server's custom settings and preferences
- **Advertisement Tracking** - Tracking representative mentions and managing rep roles in ad channels
- **Auto-Moderation** - J2L (Join-to-Leave) system for auto-banning users who leave within 24 hours
- **Rep Management** - Automatic role assignment and removal for representatives
- **Trap Channel** - Banning accounts that post in a designated trap channel for spam/scam detection
- **Anti-Nuke Protection** - Logging and punishing rapid destructive actions in servers

## 4. Data Storage

### 4.1 Database Storage
All data is stored in a secure PostgreSQL/SQLite database. Data includes:
- Server configurations (prefix, channels, roles, settings)
- Advertisement tracking records (user mentions, message tracking)
- Auto responder configurations (triggers, responses, category restrictions)
- Welcome message configurations
- Anti-nuke bypass lists and warning records

### 4.2 Data Retention
- **Permanent Data**: Server configurations, auto responder settings, welcome configurations
- **Advertisement Mentions**: Stored until the representative leaves the server or ad is deleted
- **Anti-Nuke Warnings**: Reset daily
- **Command Cooldowns**: Automatically managed by the system

## 5. Data Sharing

We do NOT:
- Sell your data to third parties
- Share your data with advertisers
- Use your data for purposes outside bot functionality
- Export personal data without owner authorization

## 6. User Rights

Server administrators have the right to:
- **View Configuration** - Check all server settings using `/config`
- **Modify Settings** - Change any server configuration at any time
- **Remove Bot** - Kick the bot to stop all data collection for that server

Bot owner has the right to:
- **Export Data** - Create database backups using `/exportdb`
- **Import Data** - Restore data using `/importdb`
- **Delete All Data** - Use `/nukedb` command for complete data wipe

## 7. Security

We implement security measures including:
- Database connection encryption
- Secure environment variables for sensitive tokens
- Input validation to prevent injection attacks
- Rate limiting to prevent abuse
- Permission checks for administrative commands

## 8. Data Collected by Command

| Command/Feature | Data Collected |
|----------------|----------------|
| Auto Responders | Trigger words, response messages, category restrictions |
| Welcome Messages | Channel ID, custom message template, embed color |
| Ad System | User mentions, message IDs, channel IDs, role assignments |
| Server Config | Prefix, channel IDs, role IDs, action preferences |
| J2L System | User join/leave timestamps for auto-ban detection |
| Anti-Nuke | Bypass user/role IDs, warning counts, action types |

## 9. Contact Information

If you have questions about this Privacy Policy, you can:
- Contact the bot owner through Discord: quasar (ID: 956902107355689061)
- Use `/about` for bot information

---

**By using QuasarBot, you acknowledge that you have read and understood this Privacy Policy.**
