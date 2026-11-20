# 🏰 Fort World
GPS-walking resource game: gather wood, stone, iron and gold in the real world, craft weapons, build and defend a Minecraft-style base. Zero dependencies, plain HTML/JS PWA.

## Deploy (Android)
1. Push this folder to a GitHub repo, then Settings → Pages → deploy from `main` / root.
2. Open `https://<you>.github.io/<repo>/` in Chrome on your phone (GPS needs HTTPS), allow location, then ⋮ → **Install app**.
Local test: `python3 -m http.server` and use 🎮 Sim (arrow buttons) to walk without moving.

## How to play
- Your first GPS fix becomes your 🏰 base. Resources respawn every 10 min. Walk within 30 m and tap them.
- 👹 enemies and 🕳️ caves (150 m+ out) fight back, drop gold and 🔮 crystals. Better weapons = less damage taken.
- At base: 🔨 craft weapons, 🏰 build walls, floors, roofs, windows, gates, doors, signs, beds, tables, chests, one vault, turrets and traps.
- Raiders attack every ~90 s. Defense below raid power = they steal 40% of chests and 10% of the vault. Win = XP, and raids scale with level.
- 📷 AR toggles the camera behind the map. Progress saves in localStorage.

## Roadmap
Real map tiles, multiplayer raids, base visiting, more tiles/furniture, sound, Capacitor APK wrapper.
