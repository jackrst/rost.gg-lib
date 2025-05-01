# 🌟 rost.gg-lib – Roblox GUI Library by Jack

A custom, neon-themed GUI library for Roblox designed for use in script executors. This library includes:

- ✅ Custom draggable window
- ✅ Neon aesthetic (like `orca`)
- ✅ Buttons and toggles
- ✅ Modular and clean code
- ✅ External loading support (via raw GitHub)

---

## 🔧 How to Use

### 1. Load the library in your executor:

```lua
local lib = loadstring(game:HttpGet("https://raw.githubusercontent.com/jackrst/rost.gg-lib/main/script"))()
```
making a window
```
local window = lib:CreateWindow("Spedion GUI")

lib:AddButton(window.Container, "Click Me", function()
    print("Button clicked!")
end)

lib:AddToggle(window.Container, "Toggle ESP", function(state)
    print("ESP is now", state)
end)
```

---

Let me know if you want me to add this file directly to your repo or expand the library with more UI elements.
