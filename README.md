# 🎵 YouTube Music Songrequest Bot for Twitch

A lightweight, background-running application that allows your Twitch viewers to request songs, automatically adding them to a queue system. 

> ⚠️ **IMPORTANT REQUIREMENT**
> The base application used for this bot is **[Pear Desktop](https://github.com/pear-devs/pear-desktop)**. 
> *Other YouTube Music desktop apps will **not** work, as they use different backend API routes and ports.*

---

## ✨ Features

* 🎛️ **Interactive Dashboard** * View upcoming songs and see exactly who requested them.
  * Delete specific songs from the queue with a single click.

* 💬 **Viewer Song Requests** * Users can request songs using raw text input (search) or direct YouTube links.
  * Supports requests via **Channel Points** or **Chat Commands**.

* ⏭️ **Skip Functionality** * Skip the current song via Channel Point rewards or a Chat Command (default: Moderators only).

* 📜 **Info Commands** * Let your chat easily display the current playing song and the upcoming queue.

* 📺 **OBS Web-Overlay** * Includes a built-in, fully customizable browser overlay for OBS to display the current track and artist on your stream.

* 🛡️ **Moderation Tools** * **Blocklists:** Restrict specific artists or users from using the song request feature.
  * **Duration Limit:** Set a maximum allowed time per song (standard is 10 minutes) to prevent overly long tracks.

* 💻 **Dual PC Support** * Seamlessly works across Dual PC streaming setups (run the bot on the streaming PC while music plays on the gaming PC).

* ⚙️ **Autostart** * Option to automatically launch the program silently in the background when Windows starts.
