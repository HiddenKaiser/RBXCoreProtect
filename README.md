# RBXLuaObfuscator
This is a modified version of [RBXLuaObfuscator](https://github.com/GhostDuckyy/RBXLuaObfuscator) made by **GhostDuckyy**.

## Obfuscation
```lua
local obfuscator = loadstring(game.HttpService:GetAsync("https://raw.githubusercontent.com/PlayerPro342/RBXLuaObfuscator/main/source.lua"))()

obfuscator(
 [===[
  --// Paste your source here
  print("Hello World!")
 ]===],
 "Taurus_", --// Custom Variable
 "Protected" --// WaterMark
)
```
