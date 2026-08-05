# 7DC — 7TV Discord Bridge (User-Installable App)

This started as a simple idea: bringing the 7TV Twitch emote experience - especially wide-emotes - to Discord.
7DC is a **User-Installable Application**, meaning it is tied to your Discord account and works across direct messages, group chats, and wervers without requiring external installations or a bot in each channel.

<p align="center">
  <a href="https://discord.com/oauth2/authorize?client_id=1513755393682313467">
    <img src="https://img.shields.io/badge/%20Install%207DC-5865F2?style=for-the-badge" alt="Install 7DC">
    <img src="https://img.shields.io/badge/Join%207DC-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord Server">
  </a>
</p>

---

# <img src="https://cdn.7tv.app/emote/01FPCZ99CR000EJT2EVEY3K7J8/4x.avif" width="48" height="49" alt="emoji"> Features

* **Use Everywhere:** Thanks to Discord's "User Install" feature, your emotes follow you globally
* **7TV Sync:** Directly pulls from your current active 7TV emote-set
* **Reactions:** React to a message using emotes (*Guide in Commands Section*)
* **Autocomplete:** Search for emotes instantly via the Discord command UI

# <img src="https://cdn.7tv.app/emote/01HVWN8E1G0003S49WDMY4KNHN/4x.avif" width="48" height="49" alt="emoji"> How to Use

1. Link your Discord account to your [7TV profile](https://7tv.app/settings)
2. [Add 7DC to Discord](https://discord.com/oauth2/authorize?client_id=1513755393682313467)
3. Use the commands below to get started sending emotes or configure your experience

[Feedback](https://github.com/0PZI/7DC-Public/issues) is greatly appreciated and helps shape the future of 7DC

# <img src="https://cdn.7tv.app/emote/01FC9H31S800013JMVXD3ETX68/4x.avif" width="48" height="49" alt="emoji"> Commands

* `/emote [name]` | `/e [name]` — Search and send an emote from your active emote-set
* `/size [small/medium/large]` — Change your default emote preview size `default=small`
* `/set [emote-set ID or link]` — Change your active emote-set or fall back to default
* `/help` — Show info about 7DC

<details>
<summary><strong>Emote Reactions Guide</strong></summary>

<br>

React to any message with your 7TV emotes directly through Discord.

### How to use

**1. Open The Message Context Menu**

Right-click (Desktop) or long-press (Mobile) a message and open:

`Apps → 7DC → React`

<img src="https://github.com/user-attachments/assets/631d4ae3-0a44-404d-a566-f21e75f2779b" width="450" height="300" />

---

**2. Select Your Emote**

Choose the emote you want to use from your active 7TV emote-set

<img src="https://github.com/user-attachments/assets/5bc88799-4a66-40d0-adb6-3527f350b29b" width="300" height="200" />

---

**3. Done**

Your selected 7TV emote will be added as a reaction to the message

<img src="https://github.com/user-attachments/assets/24a6209b-c18b-42a6-891a-f01a6db63909" width="300" height="150" />

</details>

# <img src="https://cdn.7tv.app/emote/01FB4NYBG0000FFZEHGR5A0DYS/4x.avif" width="48" height="49" alt="emoji"> Performance & Caching

The app is optimized for speed:

* **Instant Search:** Your 7TV emote-list is cached in-memory for 10 minutes. This ensures that when you type a name, the suggestions appear instantly without waiting for an API response
* **Efficient API Usage:** Caching prevents unnecessary requests to 7TV's servers, keeping the integration smooth and stable

# <img src="https://cdn.7tv.app/emote/01JQHGR6R8705W0TX7MC5CGAE7/4x.avif" width="48" height="49" alt="emoji"> Data & Privacy

7DC is designed with a "privacy-first" approach:

* **No Private Data:** The application **does not** collect or store passwords, emails, or private messages
* **Public IDs Only:** To function, the app only maps your **Discord ID** to your **7TV ID**. Both of these are public identifiers that are already available on your public profiles
* **No Tracking:** Your emote usage is not tracked, stored, or logged. The app simply acts as a bridge to display your own 7TV collection

# <img src="https://cdn.7tv.app/emote/01G6ZS6QDR0003EG3F712GQ2C8/4x.avif" width="48" height="49" alt="emoji"> Limitations

* **Emote previews are not possible**
* **Emote Reactions do NOT feature Autocompletion**

---

## 🔗 Links

[Install 7DC](https://discord.com/oauth2/authorize?client_id=1513755393682313467) • [7TV](https://7tv.app) • [Discord Terms & Guidelines](https://discord.com/guidelines)

## 🧾 Notes

* 7DC is not affiliated with, nor endorsed by 7TV.
* Emotes remain property of their respective creators on 7TV.
* Users are responsible for ensuring proper use according to Discord guidelines and 7TV rules.
* This project follows Discord Developer Policies.
