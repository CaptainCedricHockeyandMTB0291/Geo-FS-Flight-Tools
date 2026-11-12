# ✈️ Geo-FS Flight Tools
### A collection of useful tools, utilities and JavaScript add-ons for GeoFS 4.0 Beta.

So basically, this project is about making GeoFS a little easier and more useful to work with. It contains a collection of independent tools for navigation, flight planning, calculations, checklists and other simulator utilities.

The idea is to keep everything lightweight, easy to install and, most importantly, easy to use.

These are separate tools, not one massive script that does everything.

---

## 🧰 What's Included

| Tool | Description |
|---|---|
| Flight Checklist | Interactive checklist for virtual flights |
| Navigation Calculator | Calculate distances between coordinates |
| ETE Calculator | Estimate flight time using distance and groundspeed |
| Crosswind Calculator | Calculate headwind, tailwind and crosswind components |
| Flight Timer | Simple flight timer with start, pause and reset |
| Flight Logbook | Keep records of virtual flights |
| Flight Tools Panel | Quick access to useful simulator utilities |

More tools can be added as the project develops.

## 🌐 Compatibility

| Platform | Format |
|---|---|
| Windows | Tampermonkey / JavaScript |
| macOS | Userscripts / Bookmarklets |
| iPad | Safari Bookmarklets |
| Other browsers | Bookmarklets where supported |

Not every script will necessarily work on every device. Mobile Safari has some restrictions, especially with longer bookmarklets.

## 📦 Installation

### Desktop — Tampermonkey

1. Install Tampermonkey or another compatible userscript manager.
2. Open the dashboard.
3. Create a new userscript.
4. Paste the complete script.
5. Save it.
6. Open GeoFS and see whether the tool loads.

### iPad — Safari Bookmarklets

1. Open Safari.
2. Create a new bookmark.
3. Name it after the tool.
4. Edit the bookmark.
5. Replace the URL with the bookmarklet code.
6. Save it.
7. Open GeoFS and tap the bookmark to activate it.

Some scripts may need shorter mobile-specific versions because Safari has bookmarklet limitations.

## ⚙️ How It Works

Most of these tools are designed to run locally in your browser.

Some are standalone calculators, while others may interact with GeoFS's browser-side interface.

The goal is to avoid unnecessary external services and keep the scripts readable so people can actually understand what they're running.

## 🔧 Development

A few things this project aims to follow:

- Keep scripts independent whenever possible.
- Don't make every tool depend on one giant framework.
- Keep the code readable.
- Avoid unnecessary performance overhead.
- Make interfaces usable on touchscreens.
- Keep desktop and mobile versions where practical.
- Document simulator-specific dependencies.

## 🔒 Privacy

- No unnecessary accounts.
- No hidden tracking.
- No unnecessary external services.
- Local browser storage only where needed.
- Source code available for inspection.

## ⚠️ WARNING — USE AT YOUR OWN DISCRETION

These are unofficial community-made tools.

GeoFS 4.0 Beta
