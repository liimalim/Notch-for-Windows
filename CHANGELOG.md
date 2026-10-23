# Changelog

All notable changes to Poni (called Notch for Windows up to 1.0.9). The installed (Setup) version updates itself. Releases from 1.1.3 on stay on the [Releases](https://github.com/liimalim/Poni/releases) page; this file is the full history.

## 1.1.5 (2026-10-23)

- New: AI Chat tab. Chat with Google Gemini (paste a free API key from Google AI Studio in Settings > AI Chat & Translate; uses gemini-3.5-flash-lite), Claude, any OpenAI-compatible API or Ollama (GitHub #1)
- New: Wi-Fi networks inside Poni. The Bluetooth & Wi-Fi tab lists nearby networks and joins them, asking for the password right there (GitHub #1)
- New: a clock in the closed notch when nothing else is going on, and the time and date at the top of every tab (Settings > General > Clock)
- New: Translate can use Gemini too
- Times now follow the Windows 24-hour setting
- Improved: album art and visualizer in the closed notch sit evenly, clear of the rounded corners
- Improved: Poni opens as a preview while you drag the Expanded size sliders in Settings

## 1.1.4 (2026-10-22)

- New: "Keep windows below Poni" (Settings > General, on by default): maximized windows start under Poni, so it never covers tabs or title bars
- Fixed: other windows could cover Poni for a few seconds; it now comes back on top right away
- Fixed: Poni stayed visible over some fullscreen apps (VLC, games, video players, fullscreen started from a maximized window)
- Settings, the tray menu and the share sheet now say "Poni" instead of "notch"
- New website: poni.web.id

## 1.1.3 (2026-10-22)

- Fixed: dragging files from Explorer onto the notch (Shelf and drop actions) didn't work

## 1.1.2 (2026-10-22)

- New: Wi-Fi and Bluetooth on/off switches in the Bluetooth tab and the Dashboard quick toggles (GitHub #1)
- New: Connect / Disconnect paired headphones and speakers right from the notch
- New: shortcuts to the Wi-Fi network list and to add a Bluetooth device
- Fixed: Bluetooth connect/disconnect notices now appear right away (they could take up to 30 s)

## 1.1.0 (2026-10-21)

- Notch for Windows is now Poni. Settings, todos, notes and stats move over by themselves on the first start.
- The update replaces the old Notch install; the Start menu shortcut and launch at login now use the name Poni.
- New home: github.com/liimalim/Poni (old links still work).
- Data folder is now %APPDATA%\Poni and the OneDrive drop folder is OneDrive\Poni.

## 1.0.9 (2026-10-21)

- Fixed: hovering the task list under the closed notch made it flicker (it switched to music, shrank, then came back). The notch now keeps what it shows while you hover it.

## 1.0.8 (2026-10-21)

- Todo: tasks due within the hour are now shown together under the closed notch (up to 3, then "+N more"), each with its own countdown. The group still takes turns with music, Focus and other activities.

## 1.0.7 (2026-10-21)

- Todo: when several tasks are due within the hour, the closed notch takes turns showing each one, and tasks due at the same time each get their own alert.

## 1.0.6 (2026-10-21)

- Todo: give a task a due time with the clock button, or end it with "15m", "2h" or "14:30". The closed notch counts down the next task due within an hour and alerts with a chime when it's due.
- Settings: opacity for the closed notch (General) and for the cat (Cat Buddy), so they cover less of the apps behind them.

## 1.0.5 (2026-10-21)

- Fixed: API keys and tokens in Settings weren't saved if you edited another field before clicking Save. Keys now also save as soon as you leave the field or press Enter.

## 1.0.4 (2026-10-21)

- Translate: new "OpenAI-compatible API" provider. Works with OpenAI, OpenRouter, Groq, DeepSeek, Mistral, Gemini, LM Studio, Ollama and more. Set the base URL, API key and model in Settings > Translate.

## 1.0.3 (2026-10-21)

- Fixed: Settings sometimes opened behind other windows (only the taskbar button showed)
- Support page shows the merchant name "Bos Digital"

## 1.0.2 (2026-10-21)

- Support button in the notch: the cup next to the settings gear shows QRIS (Indonesia) and Gumroad (international)
- You can hide it in Settings > About

## 1.0.1 (2026-10-21)

- Support Notch: QRIS (Indonesia) and Gumroad (international) in Settings > About
- Fixed: Reset, Quit and the update toggles on the About page didn't respond
- Updated app description

## 1.0.0 (2026-10-21)

- First public release: Music, Dashboard, Calendar, Todo, Notes, Pomodoro, Weather, Health, Screen Time, Day Progress, Bluetooth, System stats, Translate, GitHub
- Shelf and Drop Actions, Snap Zones, volume/brightness HUD, optional 3D cat
- Automatic updates for the Setup version: Notch checks GitHub and installs signed updates by itself
