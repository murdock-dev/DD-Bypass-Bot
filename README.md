<!-- ╔══════════════════════════════════════════════════════════════╗ -->
<!-- ║                        DD BYPASS BOT                           ║ -->
<!-- ╚══════════════════════════════════════════════════════════════╝ -->

<div align="center">

<img src="https://imgyx.pages.dev/RZmRJ" alt="DD Bypass Bot" width="100%" />

<br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=24&pause=1000&color=0EA5E9&center=true&vCenter=true&width=720&lines=Bypass+shorteners+%26+ad-walls+instantly;Turn+file-sharers+into+direct+links;Extract+media%2C+mediainfo+%26+screenshots;Posters%2C+OTT+lookup%2C+YouTube+%26+more" alt="Typing SVG" />
</a>

<br/>

<p>
  <a href="https://telegram.dog/DDxBypass_Bot"><img alt="Try the Bot" src="https://img.shields.io/badge/Try%20it-%40DDxBypass__Bot-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" /></a>
  <a href="https://t.me/DD_Botz"><img alt="Updates" src="https://img.shields.io/badge/Updates-Channel-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" /></a>
  <a href="https://github.com/murdock-dev/DD-Bypass-Bot/stargazers"><img alt="Stars" src="https://img.shields.io/github/stars/murdock-dev/DD-Bypass-Bot?style=for-the-badge&logo=github&color=FFB13B" /></a>
</p>

<p>
  <img alt="Python" src="https://img.shields.io/badge/Python-3.10%2B-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img alt="Docker" src="https://img.shields.io/badge/Docker-Ready-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-Backed-47A248?style=flat-square&logo=mongodb&logoColor=white" />
  <img alt="Telegram" src="https://img.shields.io/badge/MTProto-Pyrogram-26A5E4?style=flat-square&logo=telegram&logoColor=white" />
  <img alt="300+ sites" src="https://img.shields.io/badge/Supported%20Sites-300%2B-0EA5E9?style=flat-square" />
  <img alt="License" src="https://img.shields.io/badge/Use-Educational-critical?style=flat-square" />
</p>

<p><strong>A high-performance Telegram bot that bypasses shorteners, ad-walls and file-sharer links — and hands you the clean direct link, media, and metadata in a single reply.</strong></p>

</div>

---

## 📑 Table of Contents

- [✨ Highlights](#-highlights)
- [🚀 Features](#-features)
  - [🔗 Link Tools](#-link-tools)
  - [📁 File &amp; Media Tools](#-file--media-tools)
  - [⬇️ Downloaders](#️-downloaders)
  - [🎬 Discovery &amp; Metadata](#-discovery--metadata)
  - [👤 Account &amp; System](#-account--system)
- [🌐 Supported Sites](#-supported-sites)
- [🛡️ Protection Handling](#️-protection-handling)
- [⚡ Command Reference](#-command-reference)
- [💎 Free vs Premium](#-free-vs-premium)
- [🧠 How It Works](#-how-it-works)
- [🔒 Privacy &amp; Safety](#-privacy--safety)
- [📬 Links &amp; Support](#-links--support)
- [⚖️ Legal](#️-legal)

---

## ✨ Highlights

<table>
<tr>
<td width="33%" valign="top">

### 🔗 Bypass Anything
300+ shorteners, ad-walls & sharers resolved to the real target — automatically.

</td>
<td width="33%" valign="top">

### 🎞️ Media Toolkit
Mediainfo, samples, screenshots, thumbnails and direct stream links for Telegram files.

</td>
<td width="33%" valign="top">

### 🎬 Rich Discovery
IMDb, AniList, posters, backdrops and where-to-watch OTT lookups on demand.

</td>
</tr>
<tr>
<td valign="top">

### ⚡ Built for Speed
Fully asynchronous engine with concurrency control and smart retries.

</td>
<td valign="top">

### 🧩 Command-less Mode
Drop a link or a file in a configured group — no command needed.

</td>
<td valign="top">

### 💎 Fair Usage
Free daily quota with an optional premium tier and self-serve payment.

</td>
</tr>
</table>

---

## 🚀 Features

### 🔗 Link Tools

> Send a protected or shortened link — get the real destination back.

- **Universal bypass** — resolve URL shorteners, ad-link walls, timer/verify pages and file-sharer index pages into their true target link.
- **Direct-download resolution** — turn file-host and sharer pages into ready-to-use direct links where possible.
- **Redirect tracing** — follow the full `301`/`302` redirect chain for any URL and see every hop.
- **Batch friendly** — throw multiple links in one message and get them resolved together.

```text
/bypass https://short.ly/abc123      →  https://example.com/file.zip
/redirect https://tiny.url/xyz        →  hop 1 → hop 2 → final target
```

### 📁 File &amp; Media Tools

> Reply to any Telegram file (or pass a URL) and put it to work.

- **Direct link** — generate a streamable / downloadable link for a Telegram file.
- **Playlist link** — stitch several consecutive files into one batch playlist link.
- **Mediainfo** — full technical readout (codecs, resolution, bitrate, duration, tracks).
- **Sample clip** — auto-cut a short preview from a video.
- **Screenshots** — capture frame grabs from a file or a URL.
- **Instant cover** — swap a video's thumbnail in place, without re-uploading.
- **Thumbnail extract** — pull the embedded cover/thumbnail out of a file.
- **Image links** — get a stable direct link for any photo or image file.

```text
reply /mediainfo   →  H.264 · 1080p · 24fps · AAC · 01:42:10 · 1.4 GB
reply /cover <img> →  thumbnail replaced ✓
reply /link        →  https://cdn.example.net/dl/…/video.mkv
```

### ⬇️ Downloaders

- **YouTube** — download audio or video from any YouTube link, quality-selectable.
- **Songs** — search a track by name (or paste a link) and get the audio delivered.

```text
/yt https://youtu.be/abc   →  choose quality → file delivered
/song faded alan walker     →  🎵 audio delivered
```

### 🎬 Discovery &amp; Metadata

- **IMDb** — detailed movie/series cards from a title or IMDb link, with a custom info template.
- **Anime** — rich anime details sourced from AniList.
- **Posters &amp; backdrops** — fetch official artwork by name, IMDb/TMDB link, or scrape it directly from a supported streaming site.
- **OTT lookup** — find out which streaming platforms carry a movie or show in your region.

```text
/imdb Inception      →  🎬 rating · genre · cast · plot · poster
/ott Breaking Bad    →  ▶ Netflix · Prime Video · …
/posters Oppenheimer →  portrait poster + landscape backdrop
```

### 👤 Account &amp; System

- **Usage** — see your consumption for the day at a glance.
- **Premium** — upgrade for higher/unlimited quotas via built-in self-serve payment.
- **Status &amp; ping** — live bot and system health, plus latency checks.
- **Command-less group mode** — admins can enable auto-processing so members just drop a link or file.
- **Media mode** — pick the default action for any media sent directly to the bot.

---

## 🌐 Supported Sites

The bypass engine covers **300+ registered handlers** across four categories.

> **Tip:** send `/supported` to the bot for the live list, categorised by type.

### ⚡ Shorteners &amp; Ad-link Walls (160+)

Sites where you have to click, wait, or solve a challenge before reaching the real URL — bypassed silently.

<details>
<summary>Show all supported shorteners</summary>

`adsfly.in` · `adurl.io` · `bit.ly` · `cpmshort.com` · `cutt.ly` · `cutw.in` · `earn2short.com` · `earn4link.in` · `earnads.net` · `earnbylink.com` · `earnlinks.in` · `easysky.in` · `egolinks.site` · `enlink.in` · `ez4short.com` · `fly2url.com` · `followyou.me` · `fylio` · `go.youlinks.in` · `gplinks.co / gplinks.pro` · `iflylink.com` · `indiaearnx.com` · `indianshortner` · `instantlinks.co` · `is.gd` · `just2earn.com` · `krownlinks.me` · `kwik` · `lanza.me` · `linegee.net` · `link4earn` · `link.indiaearnx.in` · `linkjust.com` · `linkpays.in` · `linksfire.co` · `linksgo.in` · `linkshort.in` · `linkshortx.in` · `linksxyz.in` · `liteshort.com` · `liteurl.in` · `lnk.ink` · `luckyurl.in` · `maalink.in` · `makelinks.in` · `mdiskshort.in` · `mdiskshortner.link` · `minifyurls.in` · `moonlinks.in` · `mrn-officialx.vercel.app` · `mvurl.site` · `nanolinks.in` · `nazki-protected.vercel.app` · `ngshortx.com` · `nowshort.com` · `nsfer.xyz` · `ouo` · `papajiurl.com` · `pubnotepad.com` · `redirect.proyato.com` · `redirly.icu` · `rocklinks.net` · `seturl.in` · `sfl.gl` · `short-pay.xyz` · `short.filmymod.com` · `short.onlykdrama.top` · `shorturl.at` · `shortxlinks` · `shortz.linkpc.net` · `shr2.link` · `shrinkme / shrinke` · `shrinkforearn` · `sklinker` · `softurl.in` · `spoo.me` · `sub2go.net` · `sub2unlock.io / .me` · `sub4unlock.com / .io` · `surajitlinks.in` · `swiftlnx.com` · `tfushorty.com` · `tinysl.net` · `tinyurl.com` · `uclinks.vercel.app` · `unlocktoearn.com` · `urllinkshort.in` · `urlshortx.io` · `urlspay.com` · `vercal-protection.vercel.app` · `verify.24x7-mltb.eu.org` · `vifix` · `vipshort.in` · `vipcpm.in` · `vm-mrx-protection.vercel.app` · `vplink.in / vplinks.in` · `vshort.xyz` · `welllinks.xyz` · `xdabo.com` · `yorurl.com` · `youlinks.in` · `zdrive` · `tmbcloud` · `uhdshortener.uhdnetwork.workers.dev` · `url.shortners.workers.dev` · `backend.tw4all.workers.dev` · `safelink-generator.vercel.app` · `demon-lord.vercel.app` · `jeevanmoviessbot.koyeb.app` · `antibypass.koyeb.app` · `warm-dormouse-freeg-80278e06.koyeb.app` · `mccloud` · `psa.wf` · and many more…

</details>

### 📂 File Hosts &amp; DDL Sites (20+)

`dropbox` · `gofile` · `mediafire` · `pixeldrain` · `1337x` · `buzzheavier` · `fuckingfast` · `filepress` · `filesdl` · `github (releases)` · `pahe.plus` · `yandex` · `pinterest` · and more.

### 📺 Sharer / Index Sites (60+)

Pages that list download buttons behind their own portal — the bot extracts the actual file link.

<details>
<summary>Show all supported sharers</summary>

`akirabox` · `alpha-links.in` · `arlinks.in` · `arolinks.com` · `babylinks.in` · `bindaaslinks.com` · `blog.linksflys.com` · `buzzheavier` · `caslinks.in` · `caslinks.com` · `cloudmoviez` · `cyberloom` · `dangalplay` · `devuploads` · `dldokan` · `dotflix` · `drivehub` · `drivenext` · `driveseed` · `droplink.co` · `dtflix` · `dupload` · `fastdlserver` · `fastuplod` · `filebee` · `flyurl.com` · `fxlinks` · `gcloud` · `gdflix` · `gdlink` · `gdshare` · `gkyfilehost` · `hindianimeszone` · `hubcdn` · `hubcloud` · `hubdrive` · `inddrive` · `kmhd` · `krownlinks.me` · `linksflys.com` · `linksflys` · `linkshub` · `links.asprin.dev` · `links.atozcartoonist.com` · `mcloud` · `messycloud` · `modpro` · `nexdrive` · `oxxfile` · `sharedisklinks.com` · `spacecloud` · `streamtape` · `teknoasian.com` · `teraboxlinks.com` · `teraurl.com` · `tollyflix` · `toonrips` · `uclinks.vercel.app` · `vcloud` · `vik1ngfile` · `vikingf1le` · `vikingfile` · `vifix` · `xcloud` · `xdmovies` · `zdrive` · and more.

</details>

### 🖼️ Poster Scraping (35+ OTT &amp; Cinema sites)

Fetch official posters, landscapes and backdrops directly from streaming platforms:

`Netflix` · `Amazon Prime Video` · `Disney+ Hotstar` · `Apple TV+` · `Sony LIV` · `Zee5` · `MX Player` · `Aha` · `Chaupal` · `Crunchyroll` · `Mubi` · `Viki` · `Vivamax` · `JioCinema` · `Airtel Xstream` · `Aaonxt` · `Addatimes` · `Atrangii` · `ETV Win` · `Hungama` · `PlayFlix` · `Plex` · `SainaPlay` · `BookMyShow Stream` · `TicketNew` · `WetV` · `District` · `Stage` · `Streamtape` · and more.

---

## 🛡️ Protection Handling

The bot handles the toughest anti-scraping defences automatically:

| Protection | Handling |
|---|---|
| **Cloudflare JS challenge** | Browser-fingerprint emulation via `curl-cffi` + dedicated CF solver API |
| **Cloudflare Turnstile** | Turnstile token solved via external solver |
| **hCaptcha** | Task-API solver integration |
| **Altcha PoW** | SHA-256 proof-of-work solved in-process with retry logic |
| **Timer / redirect walls** | Session re-use, delay, and redirect chain tracing |
| **Bot detection headers** | Realistic browser impersonation for every request |
| **Rate limiting** | Per-host concurrency limits, exponential back-off, `Retry-After` respect |
| **Proxy rotation** | Datacenter and residential proxy pools, per-region targeting |

---

## ⚡ Command Reference

### General

| Command | What it does |
|---|---|
| `/start` | Welcome message + current group link |
| `/help` | Full command list with descriptions |
| `/ping` | Latency check |
| `/usage` | Your daily usage against free/premium quotas |
| `/status` | Live bot &amp; system health dashboard |
| `/supported` | Full list of supported sites, categorised |

### Link Tools

| Command | Aliases | What it does |
|---|---|---|
| `/bypass <url>` | `/b` | Bypass a shortener / sharer / ad-wall |
| `/redirect <url>` | — | Trace all redirect hops for a URL |

### File &amp; Media Tools

| Command | Aliases | What it does |
|---|---|---|
| `/link` | — | Direct stream/download link for a replied Telegram file |
| `/batch_link` | — | Playlist link spanning multiple consecutive files |
| `/mediainfo` | `/mi` | Full tech specs for a Telegram file or URL |
| `/sample` | `/sam` | Generate a short sample clip from a video |
| `/screenshot` | `/ss` | Frame grabs from a video file or URL |
| `/cover` | — | Swap the thumbnail of a replied video (reply with a photo) |
| `/extract_thumb` | — | Extract the embedded thumbnail from a file |
| `/paste` | — | Get a direct link for a replied photo |

### Downloaders

| Command | What it does |
|---|---|
| `/yt <url>` | Download audio or video from YouTube |
| `/song <name or url>` | Search and download a song |

### Discovery &amp; Metadata

| Command | Aliases | What it does |
|---|---|---|
| `/imdb <title>` | — | IMDb card — rating, genre, cast, synopsis, poster |
| `/anime <title>` | — | AniList card — score, episodes, status, synopsis |
| `/posters <title or url>` | `/ps`, `/p` | Fetch official poster + backdrop art |
| `/ott <title>` | — | Where to watch — OTT platform availability |

### Settings

| Command | Who | What it does |
|---|---|---|
| `/mode` | Group admins | Toggle command-less link/media mode |
| `/media_mode` | Anyone | Choose the default action for directly sent media |
| `/group_link` | Anyone | Fetch the current bypass group invite link |
| `/premium` | Anyone | Self-serve premium subscription / payment |

---

## 💎 Free vs Premium

| | Free | Premium |
|---|:---:|:---:|
| Daily bypass quota | ✅ (limited) | ✅ Unlimited |
| Mediainfo, samples, screenshots | ✅ | ✅ |
| YouTube &amp; song downloads | ✅ (limited) | ✅ Unlimited |
| Poster scraping | ✅ | ✅ |
| Priority processing | — | ✅ |
| Usage tracking | ✅ | ✅ |

> Use `/premium` or `/usage` to check your current plan.

---

## 🧠 How It Works

```
User message
     │
     ▼
┌────────────────────┐
│   Handler layer    │  Command / message router (Pyrogram)
└────────┬───────────┘
         │
         ▼
┌────────────────────┐
│   Bypass engine    │  Classifies URL → dispatches to the right handler
│  (300+ handlers)   │  Shorteners · Sharers · File hosts · Poster sites
└────────┬───────────┘
         │
         ▼
┌────────────────────┐
│  Protection layer  │  CF / Turnstile / hCaptcha / PoW / proxy rotation
└────────┬───────────┘
         │
         ▼
┌────────────────────┐
│  Result formatter  │  Direct link · Mediainfo · Poster · Metadata
└────────┬───────────┘
         │
         ▼
   Telegram reply
```

- Fully async (Python `asyncio` + `uvloop`) — hundreds of concurrent requests.
- Per-host concurrency semaphores prevent blacklisting on any single site.
- MongoDB persists user state, settings, quotas and premium records.
- Docker-first deployment; live hot-reload of bypass modules without restarting.

---

## 🔒 Privacy &amp; Safety

- Files are **not stored permanently**; temporary caching is used only during processing.
- No conversation content is logged beyond what the operator configures.
- API rate limits apply; aggressive automated use will be throttled.
- Users are responsible for complying with copyright law and the ToS of accessed platforms.

---

## 📬 Links &amp; Support

<div align="center">

| | |
|---|---|
| 🤖 **Bot** | [Click Here](https://telegram.dog/DDxBypass_Bot) |
| 📣 **Updates channel** | [Click Here](https://t.me/DD_Botz) |
| 🐛 **Issues** | [Click Here](https://github.com/murdock-dev/DD-Bypass-Bot/issues) |
| 👮 **Contact** | [Click Here](mailto:contact@murdok.in) |

</div>

---

## ⚖️ Legal

This project is provided for **educational and personal-use automation** only. You are solely responsible for complying with the Terms of Service of every platform you access and with all applicable laws. Do not use this project to violate copyrights, circumvent paywalls, or infringe any third-party rights.

IMDb, TMDB, JustWatch, Netflix, Amazon, and all other platform names are trademarks of their respective owners. This project is not affiliated with or endorsed by any of them.

---

<div align="center">

Made with ❤️ · Drop a ⭐ if this saved you time

<br/>

<a href="https://telegram.dog/DDxBypass_Bot"><img src="https://img.shields.io/badge/Try%20%40DDxBypass__Bot-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Try the Bot" /></a>

</div>
