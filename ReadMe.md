# Toucans-ObtainX-Export

A one-stop shop to a clean, open-source (and Material Design 3) maximizing Android device via ObtainX.

This repository contains my ever-evolving **ObtainX** export. I have completely revamped this list to focus on keeping only what I consider the absolute best app for each role. Where necessary, custom regex filters are baked into the export to ensure a seamless, one-touch install/update experience—no manual choosing between multiple architecture variants or build flavors. 

Installing the apps from this list will provide you with a fully functioning, standalone Android experience on **GrapheneOS**, **LineageOS**, or a heavily debloated stock ROM.

---

## 🚀 Setup Instructions

1. **Download the Export File**  
   📥 Download the [`obtainx-export.json`](./obtainx-export.json) file from this repository.

2. **Install ObtainX**  
   📦 Install ObtainX directly from GitHub: [`bikram-agarwal/ObtainX`](https://github.com/bikram-agarwal/ObtainX).

3. **Import the Export File**  
   ⚙️ Open ObtainX and go to **Backup** ➡️ **ObtainX import**, then choose your downloaded `obtainx-export.json` file.

4. **Add GitHub PAT (Recommended)**  
   🔑 Go to **Settings** ➡️ **GitHub PAT** and add your GitHub Personal Access Token. This prevents API rate limiting when scraping updates.

5. **Configure Automated Installs (Highly Recommended)**  
   ⚡ Install **InstallerX Revived** first. Select an available privilege. Edit the default profile so **Install mode** is set to `Auto notification`. This will remove tedious button presses from the app install process.

---

## 📦 App Inventory & Functions

A curated list of core tools categorized by function to give you an immediate bird's-eye view.

### 📲 App Stores & Package Installers
| App | Package Name | Description |
| :--- | :--- | :--- |
| **ObtainX** | `dev.bikram.obtainx` | App installer that scrapes GitHub and other sources and sideloads APKs. |
| **Aurora Store** | `com.aurora.store` | Play Store client for anonymous app downloads. |
| **InstallerX-Revived** | `com.rosan.installer` | Fast, modern app installer with root, Shizuku, and network APK streaming support. |

### 🛡️ System, Root & Network Utilities
| App | Package Name | Description |
| :--- | :--- | :--- |
| **Magisk** | `com.topjohnwu.magisk` | Open-source root manager and su provider. |
| **Aegis** | `com.beemdevelopment.aegis` | 2FA token generator with local encrypted backups. |
| **Keyguard** | `com.artemchep.keyguard` | Lightweight native client for Bitwarden. |
| **Tailscale** | `com.tailscale.ipn` | Zero-config mesh VPN client built on WireGuard. |
| **PrivateDNSAndroid** | `ru.karasevm.privatednstoggle` | Quick settings tile to quickly switch private DNS servers. |
| **Syncthing-Fork** | `com.github.catfriend1.syncthingfork` | Advanced Syncthing wrapper with granular run conditions (Wi-Fi, battery, charging) for local-only data sync. |
| **MiXplorer** | `com.mixplorer.beta` | Advanced file manager with network and root access options. |
| **EdgeX** | `com.fan.edgex` | Root-enabled edge gesture and shortcut framework. |
| **Coffee** | `com.github.muellerma.coffee` | Quick settings tile to keep the screen awake. |

### 🧩 microG Framework
| App | Package Name | Description |
| :--- | :--- | :--- |
| **microG Services** | `com.google.android.gms` | FOSS framework for sandboxed Google Play Services and push notifications. |
| **microG Companion** | `com.android.vending` | FakeStore/vending companion facilitating in-app purchases and Store-dependent app functionality. |
| **microG Services Proxy** | `com.google.android.gsf` | Legacy proxy provider allowing GCM push notifications on older frameworks. |

### 🌐 Browsing, Communication & Productivity
| App | Package Name | Description |
| :--- | :--- | :--- |
| **Titanium** | `io.github.jqssun.helium` | Chromium/Titanium-based mobile web browser. |
| **FUTO Keyboard** | `org.futo.inputmethod.latin` | Keyboard with fully offline swipe typing and voice dictation. |
| **Niagram** | `top.nkbe.niagram` | Advanced Telegram client frontend with enhanced privacy modifications. |
| **Gloom** | `dev.materii.gloom` | Material-designed client for GitHub. |
| **RikkaHub** | `me.rerere.rikkahub` | Multi-model AI chat and workspace client for Android. |
| **Etar Calendar** | `ws.xsoh.etar` | Lightweight open-source calendar app. |
| **DAVx⁵** | `at.bitfire.davdroid` | CalDAV/CardDAV sync client for contacts and calendars. |
| **jtx Board** | `at.techbee.jtx` | VJournal-compatible diary, notes, and task board. |
| **Breezy Weather** | `org.breezyweather` | Material You weather app using open data sources. |

### 🎬 Entertainment & Media
| App | Package Name | Description |
| :--- | :--- | :--- |
| **LibreTube** | `com.github.libretube` | Alternative YouTube frontend built to bypass tracking. |
| **Cloudstream** | `com.lagradost.cloudstream3` | Modular media streaming engine. |
| **mpvEx** | `app.marlboroadvance.mpvex` | Gesture-based video player using the MPV core. |
| **VIVI** | `com.vivi.vivimusic` | Open-source music streaming client. |
| **Lissen** | `org.grakovne.lissen` | Dedicated, modern client for self-hosted Audiobookshelf servers. |
| **AntennaPod** | `de.danoeh.antennapod` | Podcast player and subscription manager. |

### 🏠 Self-Hosted, Wearables & Hardware
| App | Package Name | Description |
| :--- | :--- | :--- |
| **Home Assistant Minimal** | `io.homeassistant.companion.android.minimal` | Home automation and management (requires Home Assistant server). |
| **Immich** | `app.alextran.immich` | Self-hosted photo and video backup client. |
| **SparkyFitness** | `com.SparkyApps.SparkyFitnessMobile` | Self-hosted, privacy-first workout tracker, meal logger, and analytics client. |
| **Gadgetbridge** | `nodomain.freeyourgadget.gadgetbridge` | Offline health and fitness tracker companion for wearables. |
| **CAPod** | `eu.darken.capod` | Earbud status monitor for AirPods and alternatives. |
| **LibrePods** | `me.kavishdevar.librepods` | Modern, open-source companion app and battery monitor for AirPods. |

### 🎨 UI Mods, Theming & Icon Packs
| App | Package Name | Description |
| :--- | :--- | :--- |
| **Global Icon Pack** | `com.richardluo.globalIconPack` | System-wide icon routing framework (requires root). |
| **PLEnhanced** | `com.drdisagree.pixellauncherenhanced` | Vector module for Pixel Launcher and Launcher3 customization (requires root/Vector). |
| **HiLight Studio** | `com.hilight.studio` | Notification lighting for Pixel 11 Pro series only (requires root/Shizuku). |
| **Arcticons** | `com.donnnno.arcticons` | Monochromatic line-art icon pack. |
| **Delta** | `website.leifs.delta.fossdc` | Pastel icon pack. |
| **Delta Breezy Weather** | `website.leifs.delta.breezyweather` | Weather icons matched for Breezy Weather. |
