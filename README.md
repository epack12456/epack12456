local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/xHeptc/Kavo-UI-Library/main/source.lua"))()

local Window = Library.CreateLib("e_pack script Hub", "Sentinel")
local Tab = Window:NewTab("Main")
local Section = Tab:NewSection("Universal")

Section:NewButton("Aimbot", "Just Aimbot script", function()
loadstring(game:HttpGet("https://raw.githubusercontent.com/Exunys/Aimbot-V2/main/Resources/Scripts/Raw%20Main.lua"))()
end)

Section:NewButton("ESP", "ESP maybe", function()
loadstring(game:HttpGet("https://pastebin.com/raw/BJ2RGZn0"))()
end)

Section:NewButton("Fly", "u can get fly tool", function()
loadstring(game:HttpGet(('https://pastefy.app/FFPvqqiV/raw'),true))()
end)

Section:NewButton("teleport npc", "TELEPORT", function()
loadstring(game:HttpGet("https://pastebin.com/raw/U602iHBs"))()
end)

Section:NewButton("Fling all", "FUCKING OP but only works no user passes", function()
loadstring(game:HttpGet("https://pastebin.com/raw/zqyDSUWX"))()
end)
