# 🥚 Combined Auto Easter Egg Farmer for Meet People Across the World

**Created by: 2kNoah / Abyss / OmniVoid**

The ultimate all-in-one Easter Egg farming script. Combines smooth tween movement, anti-sit protection, selective collision, stiff character control, and an intelligent auto-collector with tap system.

---

## ✨ Features

- **Smooth & Natural Movement** – Uses optimized TweenService for fluid walking (150 studs/sec)
- **Anti-Sit & Stiff Character** – Prevents sitting, ragdolling, or weird animations
- **Selective Collision** – Only collides with the mainland baseplate (no falling through map)
- **Smart Auto Tap** – Reliable right-click tapping on eggs within range
- **Intelligent Pathing** – Teleports only when eggs are extremely far, otherwise tweens smoothly
- **Auto Respawn Support** – Re-applies all settings when your character respawns
- **Anti-AFK System** – Keeps you from being kicked while farming
- **Infinite Collection Loop** – Continuously scans for new eggs and collects them automatically
- **Clean & Optimized** – Minimal lag, safe error handling, and well-commented code

---

## 📋 How to Use

1. Join **Meet People Across the World**
2. Execute the full script using your preferred executor (Synapse X, Krnl, Fluxus, Solara, etc.)
3. Wait for the confirmation messages in the console:
   - `✅ Anti-Sit + Selective Collision + Stiff Character ACTIVE`
   - `🚀 Combined Easter Egg Farmer LOADED`
   - `✅ Full combined script running...`

The script will automatically start farming eggs right after loading.

---

## ⚙️ Settings (Easy to Customize)

You can tweak these variables at the top of the script:

```lua
local TWEEN_SPEED = 150          -- How fast the character moves (studs per second)
local TWEEN_SPEED_2 = 80         -- Speed used in the collector section
local TAP_DISTANCE = 12          -- How close to get before tapping
local MAX_WALK_DISTANCE = 300    -- Distance threshold for instant teleport
local TAP_COOLDOWN = 0.3         -- Delay between taps
