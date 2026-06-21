# Hellfire Music — Privacy Policy

**Effective date:** June 21, 2026

This Privacy Policy explains what data the **Hellfire Music** Discord bot ("the Bot")
and the **Hellfire Music** desktop application ("the App") access, how it is used, and
your choices. By using the Bot or the App you agree to this policy.

"We", "us", and "our" refer to the operator of Hellfire Music. Contact details are at
the end of this document.

---

## 1. Summary (the short version)

- We do **not** read your Discord messages.
- We do **not** sell your data or share it for advertising.
- We do **not** use your data to train AI or machine-learning models.
- We do **not** run a user database. The Bot keeps no long-term store of your
  personal data on our servers.
- The App stores your own login tokens **locally on your device**, not on our servers.

---

## 2. Data we access

### Through Discord (the Bot)
- **Account identity** — your Discord user ID, username, and avatar — used to identify
  you and to authorize control requests from the App.
- **Your servers (guilds)** — to determine which servers you and the Bot are both in,
  so the App can show you where it can play.
- **Voice state** — which voice channel you are in, so the Bot can join it and so that
  only members in the Bot's voice channel can control playback.
- **Spotify activity (Presence)** — **only when you run the `/playalong` command**, the
  Bot reads the song shown in your Discord "Listening to Spotify" status so it can play
  that same track. This is read at that moment and is **not stored**.
- **Command inputs** — the text you provide to slash commands (e.g. a search term or a
  link) is processed to fulfill the command.

We do **not** use the Message Content intent and do not read the content of messages.

### Through Discord (the App)
- When you log in with Discord, the App receives your profile (id, username, avatar) and
  your list of servers, using the `identify` and `guilds` scopes. These are used to show
  your profile and the servers you share with the Bot.
- The App may set your Discord "Rich Presence" (e.g. "Listening to <song>") locally
  through the Discord client on your computer while you are playing music.

### Through Spotify (the App — optional)
If you choose to connect Spotify, the App accesses, **on your behalf and with your
authorization**, your: profile (name, avatar), playlists, saved/"Liked" tracks,
recently played, and top artists/tracks. With your action it can also: save or remove
Liked tracks, and create or add tracks to your playlists. This data is shown to you in
the App. It is **not** stored on our servers, sold, or shared.

### Through YouTube
The Bot retrieves audio streams and search results from YouTube to play music. No
personal data of yours is sent to YouTube beyond standard network requests.

---

## 3. How we use data

We use the data above solely to provide the service: to authenticate you, show your
library and the servers you share with the Bot, play and control music, display synced
lyrics, and (on request) play the song from your Spotify status.

---

## 4. Storage and retention

- **Bot identity cache:** to verify that a control request truly comes from you, the Bot
  briefly caches your Discord access token and ID **in memory only** (a few minutes) and
  then discards it. It is never written to disk.
- **Saved queues:** the "Save Queue" feature stores **track metadata only** (titles,
  links, artwork URLs). It does **not** store your identity, messages, or member lists.
- **No user database:** the Bot does not maintain a persistent database of users,
  members, presences, or messages.
- **The App stores on your device only:** your own Discord and (if connected) Spotify
  login tokens are stored locally on your computer so you stay logged in, along with
  your recent searches. This data lives on your machine; we do not receive or store it.

---

## 5. Sharing and third parties

We do not sell or rent your data. Data is shared only with the third-party services
required to make the product work, each under their own privacy policies:

- **Discord** — https://discord.com/privacy
- **Spotify** (if you connect it) — https://www.spotify.com/legal/privacy-policy/
- **YouTube / Google** — https://policies.google.com/privacy
- **Lyrics providers** (lrclib.net, and as a fallback SpicyLyrics) — track title and
  artist are sent to fetch lyrics. No personal account data is sent.

---

## 6. AI / machine learning

We do **not** use your data — including message content (which we do not access),
presence, or Spotify data — to train or improve any AI or machine-learning models.

---

## 7. Your choices and rights

- **Disconnect at any time:** log out of Discord or Spotify in the App to remove the
  stored tokens from your device.
- **Revoke access:** remove the App's authorization in your
  [Discord Authorized Apps](https://discord.com/settings/authorized-apps) and
  [Spotify Apps](https://www.spotify.com/account/apps/) settings.
- **Presence / `/playalong`:** this only runs when you invoke it. You can also hide your
  activity via Discord's "Share your activity with others" / "Display current activity"
  setting so no one (including the Bot) can read it.
- **Remove the Bot:** a server admin can remove the Bot at any time.

---

## 8. Children

Hellfire Music is not directed to children under 13 (or the minimum age required by
Discord's Terms of Service in your country). Do not use it if you are under that age.

---

## 9. Security

We use reasonable measures to protect data in transit (HTTPS/secure connections).
No method of transmission or storage is 100% secure; we cannot guarantee absolute
security.

---

## 10. Changes to this policy

We may update this policy. Material changes will be reflected by updating the effective
date above. Continued use after changes constitutes acceptance.

---

## 11. Affiliation

Hellfire Music is an independent project and is **not affiliated with, endorsed by, or
sponsored by** Discord, Spotify, or YouTube/Google. All trademarks belong to their
respective owners.

---

## 12. Contact

Questions or data requests: **[your-contact-email-or-support-server]**

*This document is provided for transparency and is not legal advice; for a commercial
public launch, consider having it reviewed by a qualified professional.*
