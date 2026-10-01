# 📺 EPG Light & Night: Smart EPG Harvester

**EPG Light & Night** is a streamlined, automated tool that creates a custom TV guide (EPG) specifically for your unique playlist. Instead of downloading thousands of channels you don't have, this script "looks" at your playlist `id=""` tags and only grabs the data you actually need.

## 🌟 Why use this?
* **Tiny File Size:** Generates a compressed `.gz` file to stay under GitHub's 100MB limit.
* **Smart Filtering:** Uses your own M3U playlist as a map so your guide is never cluttered.
* **Fully Automated:** Updates itself every 6 hours.

---

## 🔗 How to use it in your IPTV Player
Add a new EPG source in your player using the "Raw" link to your compressed file:
```
https://epg-coocaa.vercel.app/light-epg.xml.gz
```

---
