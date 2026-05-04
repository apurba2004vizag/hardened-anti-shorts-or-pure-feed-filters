# 🛡️ Hardened Anti-Shorts & Pure Feed Filters

A hardened uBlock Origin filter list to completely block YouTube Shorts and Instagram Reels at the network and API level.

## ⚡ Why this is different
Most filter lists rely on hiding CSS elements (like `.x1odjw0f`). These break constantly when YouTube or Instagram update their UI. 

This list is built differently:
* **API & Network Interception:** Kills the background data requests (XHR/GraphQL) before the video even loads.
* **Locale-Independent:** Uses structural ARIA and routing tags, so it works no matter what language your browser is in.
* **Zero CPU Bloat:** By stopping the payload instead of just hiding it, your browser stays lightning fast.

## 🚀 Installation Instructions

1. Open the **uBlock Origin Dashboard** (click the extension icon > ⚙️ gears icon).
2. Go to the **Filter lists** tab.
3. Scroll to the very bottom and click the **+** next to **Custom**.
4. Check the box next to **Import**.
5. Copy and paste the exact URL below into the text box:
   `https://raw.githubusercontent.com/apurba2004vizag/hardened-anti-shorts-or-pure-feed-filters/main/filters.txt`
6. Click **Apply changes** in the top left corner.
7. Refresh your feed and enjoy the silence.
