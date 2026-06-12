# Privacy Policy — AeroNova Prime

**Last updated:** June 12, 2025  
**Developer:** Sarthak | Sanerex Development  
**Support:** [discord.gg/Sanerex Development](https://discord.gg/BU53R7ZEKd)

---

## 1. Introduction

AeroNova Prime ("the Bot") is a Discord music bot developed by Sanerex Development. This Privacy Policy explains what data we collect, how we use it, and your rights regarding that data. By using AeroNova in your server, you agree to this policy.

---

## 2. Data We Collect

### 2.1 Server Data
| Data | Purpose |
|------|---------|
| Guild ID | Server-specific settings (prefix, DJ mode, setup channel) |
| Channel IDs | Music setup panel, bot channel, log channel |
| Role IDs | DJ role configuration |

### 2.2 User Data
| Data | Purpose |
|------|---------|
| User ID | Playlists, saved queues, XP/level system, vote tracking |
| Voice channel presence | Queue management, skip voting, 24/7 mode |
| Message content (prefix commands) | Parsing and executing bot commands (e.g. `!play`, `!skip`) |

### 2.3 Music & Activity Data
| Data | Purpose |
|------|---------|
| Songs played (URI, title, artist) | Global song stats, top charts, recommendations |
| Listening time | XP system, leaderboard |
| Songs played count | User profile, badges |

### 2.4 What We Do NOT Collect
- Passwords or authentication tokens
- Personal information (name, email, address)
- Payment information
- Message content beyond command parsing
- Data from private/DM channels

---

## 3. How We Use Your Data

- To provide and improve bot features (music playback, playlists, DJ system)
- To enforce server-specific settings (prefix, DJ roles, ignored channels)
- To power the XP and leveling system
- To display global statistics (top songs, leaderboard)
- To enforce premium plan limits
- To maintain bot stability and debug issues

We do **not** sell, rent, or share your data with third parties.

---

## 4. Data Storage

- All data is stored in a local SQLite database (`AeroNova.db`) on our secure server
- Data is stored only as long as necessary for the bot to function
- No data is stored on third-party cloud platforms outside our control

---

## 5. Message Content Intent

AeroNova uses Discord's **Message Content Intent** solely to parse prefix-based commands (e.g. `/play`, `/skip`, `/queue`). We do **not**:
- Read, log, or store regular conversations
- Use message content for any purpose other than command execution
- Share message content with any third party

---

## 6. Server Members Intent

AeroNova uses Discord's **Server Members Intent** for:
- DJ role verification before executing music commands
- Displaying who requested a track in the queue
- Vote skip threshold calculation based on voice channel members

---

## 7. Presence Intent

AeroNova uses Discord's **Presence Intent** for:
- Displaying real-time bot statistics in the `/stats` command
- Managing queue behavior when users leave voice channels

We do **not** store or track individual user presence/activity data long-term.

---

## 8. Data Retention

| Data Type | Retention |
|-----------|-----------|
| Server settings | Until bot is removed from server or manually deleted |
| User playlists / saved queues | Until user deletes them or requests removal |
| XP / listening stats | Until user requests deletion |
| Vote records | 12 hours (auto-expiry) |
| Premium records | Until expiry or manual removal |

---

## 9. Your Rights

You have the right to:
- **Access** — request what data we hold about you
- **Delete** — request deletion of your data at any time
- **Opt-out** — stop using the bot; your data will be removed upon request

To exercise any of these rights, contact us via our [Support Server](https://discord.gg/SZrmhwvsqD).

---

## 10. Third-Party Services

AeroNova connects to the following external services for music playback:
- **Lavalink / YouTube** — audio streaming
- **Spotify API** — track metadata resolution
- **SoundCloud** — audio streaming
- **LRCLIB** — synchronized lyrics

These services have their own privacy policies. We do not share your Discord data with them.

---

## 11. Children's Privacy

AeroNova is not directed at children under the age of 13. We do not knowingly collect data from users under 13. If you believe a child has provided us data, contact us immediately.

---

## 12. Changes to This Policy

We may update this policy from time to time. Changes will be announced in our [Support Server](https://discord.gg/BU53R7ZEKd). Continued use of the bot after changes constitutes acceptance.

---

## 13. Contact

**Developer:** Sarthak  
**Agency:** Sanerex Development  
**Discord:** [Sanerex Development](https://discord.gg/BU53R7ZEKd)  
**Bot ID:** 1509948611599925328
