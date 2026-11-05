# Hi, I'm Alberto Fernández 👋

Developer and **Salesforce Marketing Cloud** specialist based in Madrid. I like building small, useful tools (bots, static sites, modules that solve one specific problem), usually with no backend and deployed on GitHub Pages or Cloudflare Workers. Lately I've also been digging into retro games and handhelds: decompilation, ports and firmware.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-afsenovilla-0A66C2?logo=linkedin&logoColor=white)](https://www.linkedin.com/in/afsenovilla/)

---

## 🛠️ Projects

### Retro games and handhelds

- [**Tombi-Decomp**](https://github.com/afsenovilla/Tombi-Decomp) — Matching decompilation of *Tombi!* (*Tomba!*) for the original PlayStation, with over 99% of the game's code matching byte for byte, plus a playable native port for Windows and Linux with nine languages and mods. You supply your own disc image.
- [**Ash Droid Launcher**](https://github.com/afsenovilla/ash-droid-launcher) — Android launcher for Pokémon Fire Ash and other Pokémon Essentials fangames running on mkxp-z, aimed at handhelds with physical controls: it detects the screen and controller, walks you through button mapping and writes a config tuned to the device. Based on mkxp-z-android.
- [**XX-CFW**](https://github.com/afsenovilla/XX-CFW) *(experimental)* — A layer on top of ROCKNIX that aims to make closing the lid on Anbernic H700 clamshells such as the RG34XXSP work like a GBA SP: instant sleep, minimal battery drain and back to your game on opening. Not yet tested on the console.

### Pokémon

- [**Poketracker**](https://github.com/afsenovilla/poketracker) · [pokedex.asuntosimportant.es](https://pokedex.asuntosimportant.es) — Living Dex and Shiny Living Dex tracker for Pokémon HOME, in Spanish, built on the PokédexTracker frontend. React + Vite + TypeScript; your progress is saved as a JSON file in your own GitHub repository, with no server. Includes where to catch each Pokémon, origin marks and night mode.
- [**Pokémon Distribuciones Bot**](https://github.com/afsenovilla/pokemon-distro-bot) — Telegram bot (Cloudflare Workers + KV) covering Mystery Gift distributions and in-game events across the main series: what's active now, the full history by console, whether each one was shiny (read from the actual wondercard), and wondercard downloads. It messages you when something new appears and checks against Poketracker to tell you what you're missing.
- [**PokeDump**](https://github.com/afsenovilla/PokeDump) *(experimental)* — Read-only save dumper for Pokémon FireRed / LeafGreen on Nintendo Switch, using an ESP32-S3 and a web page. It produces a `.sav` for PKHeX and a JSON file you can import into Poketracker. Tested in an emulator and against a simulated console, with the first test on real hardware still to come.

### Yoto tools

| Project | What it does | |
|---|---|---|
| [**YOTO JSON Extractor**](https://github.com/afsenovilla/YOTO-json-extractor) | Python app (also available as an `.exe`) that downloads the audio tracks and images from Yoto URLs and embeds their metadata. | ![Stars](https://img.shields.io/github/stars/afsenovilla/YOTO-json-extractor?style=flat) |
| [**Yoto Audio Player Browser Extension**](https://github.com/afsenovilla/Yoto-Audio-Player-Browser-Extension) | Extension for [Chrome](https://chromewebstore.google.com/detail/yoto-audio-player/ndmodaehbkhkcmpmplnlijknkcppllfn), [Edge](https://microsoftedge.microsoft.com/addons/detail/jnpkhcjceoolcliepogelalaccmohjhl) and [Firefox](https://addons.mozilla.org/addon/yoto-audio-player/) to play and download the tracks on your Yoto cards right in the browser. | ![Stars](https://img.shields.io/github/stars/afsenovilla/Yoto-Audio-Player-Browser-Extension?style=flat) |

### Bots and modules

- [**MMM-DexcomOne**](https://github.com/afsenovilla/MMM-DexcomOne) — MagicMirror² module showing live Dexcom glucose with a trend arrow and a 3-hour chart, with no Nightscout or developer account needed.
- [**MMM-ComedorBuero**](https://github.com/afsenovilla/MMM-ComedorBuero) — Dependency-free MagicMirror² module showing the school lunch menu (today, several days or the whole week), read from the [ComedorBueroVallejo](https://github.com/afsenovilla/ComedorBueroVallejo) JSON.
- [**RajoySlackBot**](https://github.com/afsenovilla/RajoySlackBot) — Slack bot with a `/rajoy` command that sends audio clips to a channel. Python + Flask + ffmpeg, in Docker on Render.

---

## 🧰 Stack

![C](https://img.shields.io/badge/C-A8B9CC?logo=c&logoColor=black)
![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?logo=react&logoColor=black)
![Angular](https://img.shields.io/badge/Angular-DD0031?logo=angular&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?logo=flask&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?logo=microsoftsqlserver&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white)
![Sass](https://img.shields.io/badge/Sass-CC6699?logo=sass&logoColor=white)
![Android](https://img.shields.io/badge/Android-34A853?logo=android&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare_Workers-F38020?logo=cloudflare&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?logo=githubactions&logoColor=white)

**Marketing:** Salesforce Marketing Cloud (HTML email, SQL queries, journeys and data architecture) and Braze.

---

## 🎓 Certifications

- Salesforce Certified Marketing Cloud Engagement Specialist (2024, formerly "Marketing Cloud Email Specialist")
- Salesforce Certified AI Associate (2024)
- Braze Certified Marketer (2025)
- Querying Microsoft SQL Server (70-461)
- ChatGPT Prompt Engineering for Developers (DeepLearning.AI)

---

## 📫 Contact

If something here is useful to you or you'd like to work together, reach out on [LinkedIn](https://www.linkedin.com/in/afsenovilla/).
